# 🤖 JARVIS AI
### Asistente Virtual Inteligente desarrollado con Python, IA y Procesamiento de Lenguaje Natural

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-Artificial%20Intelligence-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>

---

## 📖 Descripción

**JARVIS AI** es una biblioteca desarrollada en Python que permite crear asistentes virtuales inteligentes de forma rápida y sencilla. Utiliza tecnologías modernas de Inteligencia Artificial, Machine Learning y Procesamiento de Lenguaje Natural para interpretar comandos y responder de manera natural.

El objetivo principal es proporcionar una base sólida para desarrollar asistentes virtuales personalizados sin necesidad de construir toda la infraestructura desde cero.

---

# ✨ Características

### 🎙️ Reconocimiento de Voz

- Entrada mediante voz utilizando Google Speech Recognition.
- Soporte para Whisper ASR.
- Procesamiento de lenguaje natural.

### 🔊 Síntesis de Voz

- Respuestas mediante:
  - pyttsx3
  - gTTS

### 🧠 Inteligencia Artificial

- Comprensión de comandos en lenguaje natural.
- Identificación automática de intenciones.
- Procesamiento NLP.
- Arquitectura basada en IA y Machine Learning.

### ⚡ Fácil Integración

- Configuración rápida.
- Personalización mediante funciones propias.
- Compatible con aplicaciones de escritorio.

### 🌐 Automatización

- Apertura de sitios web.
- Consulta de información.
- Automatización de tareas básicas.

---

# 🏗️ Arquitectura

La arquitectura de JARVIS AI se divide en dos componentes principales.

## 👤 Cliente

Responsable de:

- Capturar entrada del usuario.
- Procesar voz o texto.
- Enviar solicitudes al servidor.
- Mostrar respuestas.

## ☁️ Servidor

Responsable de:

- Interpretar comandos.
- Procesar lenguaje natural.
- Gestionar modelos de IA.
- Generar respuestas inteligentes.

---

# 🚀 Instalación

## Requisitos

- Python 3.6 o superior
- Pip

### Instalar JARVIS AI

```bash
pip install JarvisAI
```

---

## Dependencias Opcionales

### PyAudio

#### Windows

Descargar la versión correspondiente desde:

```text
https://www.lfd.uci.edu/~gohlke/pythonlibs/
```

Instalar:

```bash
pip install PyAudio.whl
```

#### Linux

```bash
sudo apt-get install portaudio19-dev
pip install pyaudio
```

#### macOS

```bash
brew install portaudio
pip install pyaudio
```

---

### pycountry

```bash
sudo apt update
sudo apt install python3-pycountry
```

---

### Visual C++ Redistributable

Instalar Microsoft Visual C++ Redistributable para Visual Studio 2022.

---

# 💻 Uso Básico

```python
import JarvisAI

def custom_function(*args, **kwargs):
    command = kwargs.get("query")
    entities = kwargs.get("entities")

    print("Entidades:", entities)

    return command + " Ejecutado"

jarvis = JarvisAI.Jarvis(
    input_mechanism="voice",
    output_mechanism="both",
    backend_tts_api="pyttsx3",
    use_whisper_asr=False,
    display_logs=False,
    api_key="TU_API_KEY"
)

jarvis.start()
```

---

# ⚙️ Configuración

## Entrada

### Texto

```python
input_mechanism="text"
```

### Voz

```python
input_mechanism="voice"
```

---

## Salida

### Texto

```python
output_mechanism="text"
```

### Voz

```python
output_mechanism="voice"
```

### Voz + Texto

```python
output_mechanism="both"
```

---

# 🎯 Funcionalidades

JARVIS AI puede comprender comandos como:

### ⏰ Utilidades

- Consultar hora
- Consultar fecha
- Obtener información general
- Noticias
- Clima

### 🎭 Entretenimiento

- Contar chistes
- Recomendaciones
- Juegos

### 🌐 Internet

- Abrir sitios web
- Buscar información
- Reproducir videos en YouTube

### 📱 Comunicación

- Enviar correos
- WhatsApp

### 📷 Herramientas

- Tomar capturas de pantalla
- Tomar fotografías
- Medir velocidad de Internet

### 📍 Ubicación

- Buscar lugares cercanos
- Obtener ubicación actual

---

# 🔥 Ventajas

✅ Fácil de implementar

✅ Compatible con Python

✅ Reconocimiento por voz

✅ Respuestas por voz

✅ Inteligencia Artificial integrada

✅ Personalizable

✅ Código abierto

---

# 🛠️ Tecnologías Utilizadas

- Python
- TensorFlow
- PyTorch
- Transformers
- NLP
- Speech Recognition
- Whisper
- pyttsx3
- gTTS

---

# 📂 Estructura del Proyecto

```text
JarvisAI/
│
├── Core/
├── NLP/
├── Speech/
├── Models/
├── Utilities/
├── APIs/
└── Examples/
```

---

# 👨‍💻 Desarrollador

<div align="center">

## ISAI REYES PEÑA

### Ingeniero en Desarrollo de Software

💻 Desarrollo Web

🖥️ Aplicaciones de Escritorio

📱 Aplicaciones Móviles

🤖 Inteligencia Artificial

☁️ Backend y APIs

🗄️ Bases de Datos

🔐 Ciberseguridad

</div>

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas.

1. Realiza un Fork.
2. Crea una nueva rama.
3. Implementa tus mejoras.
4. Envía un Pull Request.

---

# 📜 Licencia

Este proyecto se distribuye bajo la licencia **MIT License**.

---

<div align="center">

### ⭐ Si te gusta este proyecto, no olvides darle una estrella ⭐

### Desarrollado por ISAI REYES PEÑA 🚀

</div>
