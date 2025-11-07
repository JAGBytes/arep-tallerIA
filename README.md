# Taller de Inteligencia Artificial

Este repositorio contiene material y ejemplos prácticos para el taller de Inteligencia Artificial, incluyendo notebooks de Jupyter con ejemplos de uso de diferentes herramientas y bibliotecas de IA.

## 📋 Requisitos Previos

Antes de comenzar, asegúrate de tener instalado lo siguiente:

- Python 3.8 o superior
- Jupyter Notebook o JupyterLab
- pip (gestor de paquetes de Python)

## 🚀 Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/arep-tallerIA.git
   cd arep-tallerIA
   ```

2. Crea y activa un entorno virtual (recomendado):
   ```bash
   # En Windows
   python -m venv .venv
   .venv\Scripts\activate
   
   # En macOS/Linux
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. Instala las dependencias necesarias:
   ```bash
   pip install openai python-dotenv jupyter notebook
   ```

4. Configura tus variables de entorno:
   - Crea un archivo `.env` en la raíz del proyecto
   - Agrega tus claves de API necesarias (por ejemplo, para OpenAI)
   ```
   OPENAI_API_KEY=tu_clave_aqui
   ```

## 📂 Estructura del Proyecto

- `hello_ai/`: Directorio con scripts de Python
  - `hello_ai.py`: Script de ejemplo para interactuar con OpenAI

- `hello_ai_vscode/`: Directorio con notebooks de Jupyter
  - `Guia3_IntroAPIsAI_Notebook.ipynb`: Introducción a las APIs de IA
  - `Guia4_Introduccion_LangChain_OpenAI.ipynb`: Introducción a LangChain con OpenAI
  - `Guia5_HuggingFace_Intro.ipynb`: Introducción a Hugging Face
  - `hello_ai.ipynb`: Notebook de ejemplo
  - `setup_hello_ai.ipynb`: Configuración inicial del entorno

## 🚀 Cómo Ejecutar

1. Asegúrate de tener todas las dependencias instaladas
2. Para ejecutar los notebooks de Jupyter:
   ```bash
   jupyter notebook
   ```
   O con JupyterLab:
   ```bash
   jupyter lab
   ```
3. Navega hasta el notebook que deseas ejecutar y ábrelo
4. Ejecuta las celdas en orden

