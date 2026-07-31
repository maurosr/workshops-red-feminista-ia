# Workshops del Eje de Innovación

Copyright (c) 2026, Mauro Schilman, Luciana Benotti

### Red Feminista en IA para Latinoamérica y el Caribe

---

# Español (Português mais abaixo)

## Los workshops

Cada workshop es un notebook **autocontenido**: instala todos sus paquetes al ejecutar su primera celda de código. Los requisitos y pasos de instalación de abajo son los mismos para todos.

| Workshop | Tema | Notebook (español) | Notebook (português) |
| -------- | ---- | ------------------ | -------------------- |
| **1º** | Pequeños Modelos de Lenguaje Abiertos | `TallerPequeñosModelosDeLenguajeAbiertos.ipynb` | `SeminarioPequenosModelosDeLinguagemAbertos.ipynb` |
| **2º** | Retrieval-Augmented Generation (RAG) | `TallerGeneracionAumentadaPorRecuperacion.ipynb` | `SeminarioGeracaoAumentadaPorRecuperacao.ipynb` |

## Requisitos previos

Para ejecutar los notebooks solo necesitás instalar dos cosas:

| Requisito      | Versión mínima  |
| -------------- | --------------- |
| **Python**     | 3.12 o superior |
| **JupyterLab** | última versión  |

> JupyterLab instala `ipykernel` automáticamente.

> Cada notebook instala automáticamente todos los demás paquetes (torch, transformers, llama-index, etc.) al ejecutar su primera celda de código.

---

## Instalación

### Linux

**Paso 1 — Verificar si ya tenés Python 3.12+**

Abrí una terminal y ejecutá:

```bash
python3 --version
```

Si la respuesta es `Python 3.12.x` o mayor, saltá al Paso 3.

**Paso 2 — Instalar Python 3.12**

En Ubuntu / Debian:

```bash
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update
sudo apt install python3.12 python3.12-venv python3.12-distutils
```

**Paso 3 — Crear un entorno virtual (recomendado)**

Un entorno virtual mantiene los paquetes de este taller separados del resto de tu sistema.

```bash
python3.12 -m venv venv
source venv/bin/activate
```

Vas a ver `(venv)` al inicio de la línea de comandos: eso significa que el entorno está activo.

**Paso 4 — Instalar JupyterLab**

```bash
pip install jupyterlab
```

---

### macOS

**Paso 1 — Verificar si ya tenés Python 3.12+**

Abrí la aplicación **Terminal** y ejecutá:

```bash
python3 --version
```

Si la respuesta es `Python 3.12.x` o mayor, saltá al Paso 3.

**Paso 2 — Instalar Python 3.12**

La forma más sencilla es usar [Homebrew](https://brew.sh). Si no lo tenés instalado:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Luego instalá Python:

```bash
brew install python@3.12
```

Alternativa: descargá el instalador gráfico desde [python.org/downloads/macos](https://www.python.org/downloads/macos/).

**Paso 3 — Crear un entorno virtual (recomendado)**

```bash
python3.12 -m venv venv
source venv/bin/activate
```

Vas a ver `(venv)` al inicio de la línea de comandos.

**Paso 4 — Instalar JupyterLab**

```bash
pip install jupyterlab
```

---

### Windows

**Paso 1 — Verificar si ya tenés Python 3.12+**

Abrí **PowerShell** o el **Símbolo del sistema** (cmd) y ejecutá:

```powershell
python --version
```

Si la respuesta es `Python 3.12.x` o mayor, saltá al Paso 3.

**Paso 2 — Instalar Python 3.12**

1. Entrá a [python.org/downloads/windows](https://www.python.org/downloads/windows/).
2. Descargá el instalador de la versión 3.12 (o superior).
3. Ejecutá el instalador y **marcá la opción "Add Python to PATH"** antes de continuar.

**Paso 3 — Crear un entorno virtual (recomendado)**

```powershell
python -m venv venv
venv\Scripts\activate
```

Vas a ver `(venv)` al inicio de la línea de comandos.

**Paso 4 — Instalar JupyterLab**

```powershell
pip install jupyterlab
```

---

## Abrir el notebook con JupyterLab

**Paso 5 — Iniciar JupyterLab**

Con el entorno virtual activo, ejecutá desde la carpeta del proyecto:

```bash
jupyter lab
```

Se abrirá automáticamente una pestaña en tu navegador. Si no se abre, copiá la URL que aparece en la terminal (empieza con `http://localhost:8888/...`) y pegala en el navegador.

**Paso 6 — Abrir y ejecutar el notebook**

1. En el panel izquierdo, hacé doble clic en el notebook del workshop que vayas a hacer (ver la tabla de arriba), por ejemplo `TallerGeneracionAumentadaPorRecuperacion.ipynb`.
2. Ejecutá la primera celda de código — instalará automáticamente todos los paquetes necesarios.

---

## Autoría y atribución

Este proyecto fue creado por:
* **Mauro Schilman**
* **Luciana Benotti**

### Cómo atribuir este trabajo
Si modificás o compartís este trabajo, por favor atribuilo de la siguiente manera:
> "Workshops de IA del Eje de Innovacion 2026" de Mauro Schilman y Luciana Benotti, usado bajo licencia CC BY-NC-SA 4.0

---

---

# Português

## Os workshops

Cada workshop é um notebook **autocontido**: instala todos os seus pacotes ao executar sua primeira célula de código. Os requisitos e passos de instalação abaixo são os mesmos para todos.

| Workshop | Tema | Notebook (espanhol) | Notebook (português) |
| -------- | ---- | ------------------- | -------------------- |
| **1º** | Pequenos Modelos de Linguagem Abertos | `TallerPequeñosModelosDeLenguajeAbiertos.ipynb` | `SeminarioPequenosModelosDeLinguagemAbertos.ipynb` |
| **2º** | Retrieval-Augmented Generation (RAG) | `TallerGeneracionAumentadaPorRecuperacion.ipynb` | `SeminarioGeracaoAumentadaPorRecuperacao.ipynb` |

## Pré-requisitos

Para executar os notebooks você só precisa instalar duas coisas:

| Requisito      | Versão mínima    |
| -------------- | ---------------- |
| **Python**     | 3.12 ou superior |
| **JupyterLab** | última versão    |

> O JupyterLab instala o `ipykernel` automaticamente.

> Cada notebook instala automaticamente todos os outros pacotes (torch, transformers, llama-index, etc.) ao executar sua primeira célula de código.

---

## Instalação

### Linux

**Passo 1 — Verificar se você já tem Python 3.12+**

Abra um terminal e execute:

```bash
python3 --version
```

Se a resposta for `Python 3.12.x` ou maior, pule para o Passo 3.

**Passo 2 — Instalar Python 3.12**

No Ubuntu / Debian:

```bash
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update
sudo apt install python3.12 python3.12-venv python3.12-distutils
```

**Passo 3 — Criar um ambiente virtual (recomendado)**

Um ambiente virtual mantém os pacotes deste workshop separados do restante do seu sistema.

```bash
python3.12 -m venv venv
source venv/bin/activate
```

Você verá `(venv)` no início da linha de comando: isso significa que o ambiente está ativo.

**Passo 4 — Instalar o JupyterLab**

```bash
pip install jupyterlab
```

---

### macOS

**Passo 1 — Verificar se você já tem Python 3.12+**

Abra o aplicativo **Terminal** e execute:

```bash
python3 --version
```

Se a resposta for `Python 3.12.x` ou maior, pule para o Passo 3.

**Passo 2 — Instalar Python 3.12**

A forma mais simples é usar o [Homebrew](https://brew.sh). Se ainda não o tiver instalado:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Depois, instale o Python:

```bash
brew install python@3.12
```

Alternativa: baixe o instalador gráfico em [python.org/downloads/macos](https://www.python.org/downloads/macos/).

**Passo 3 — Criar um ambiente virtual (recomendado)**

```bash
python3.12 -m venv venv
source venv/bin/activate
```

Você verá `(venv)` no início da linha de comando.

**Passo 4 — Instalar o JupyterLab**

```bash
pip install jupyterlab
```

---

### Windows

**Passo 1 — Verificar se você já tem Python 3.12+**

Abra o **PowerShell** ou o **Prompt de Comando** (cmd) e execute:

```powershell
python --version
```

Se a resposta for `Python 3.12.x` ou maior, pule para o Passo 3.

**Passo 2 — Instalar Python 3.12**

1. Acesse [python.org/downloads/windows](https://www.python.org/downloads/windows/).
2. Baixe o instalador da versão 3.12 (ou superior).
3. Execute o instalador e **marque a opção "Add Python to PATH"** antes de continuar.

**Passo 3 — Criar um ambiente virtual (recomendado)**

```powershell
python -m venv venv
venv\Scripts\activate
```

Você verá `(venv)` no início da linha de comando.

**Passo 4 — Instalar o JupyterLab**

```powershell
pip install jupyterlab
```

---

## Abrir o notebook com JupyterLab

**Passo 5 — Iniciar o JupyterLab**

Com o ambiente virtual ativo, execute a partir da pasta do projeto:

```bash
jupyter lab
```

Uma aba será aberta automaticamente no seu navegador. Se não abrir, copie a URL que aparece no terminal (começa com `http://localhost:8888/...`) e cole no navegador.

**Passo 6 — Abrir e executar o notebook**

1. No painel esquerdo, dê um duplo clique no notebook do workshop que você vai fazer (ver a tabela acima), por exemplo `SeminarioGeracaoAumentadaPorRecuperacao.ipynb`.
2. Execute a primeira célula de código — ela instalará automaticamente todos os pacotes necessários.

---

## Autoria e atribuição

Este projeto foi criado por:
* **Mauro Schilman**
* **Luciana Benotti**

### Como atribuir este trabalho
Se você modificar ou compartilhar este trabalho, por favor atribua da seguinte forma:
> "Workshops de IA del Eje de Innovacion 2026" de Mauro Schilman e Luciana Benotti, usado sob a licença CC BY-NC-SA 4.0
