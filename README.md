<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/4712/4712109.png" />

# 🤖 SistemaIAJARVIS

### Sistema de Inteligencia Artificial General basado en LLMs y modelos especializados 🚀

<p align="center">
  <b>JARVIS</b> (HuggingGPT) es una plataforma experimental desarrollada por Microsoft Research que conecta modelos de lenguaje de gran escala con cientos de modelos especializados de Hugging Face para resolver tareas complejas de Inteligencia Artificial.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/JARVIS-HuggingGPT-blueviolet?style=for-the-badge">
  <img src="https://img.shields.io/badge/LLM-Orchestration-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/HuggingFace-AI-yellow?style=for-the-badge&logo=huggingface&logoColor=black">
  <img src="https://img.shields.io/badge/Microsoft-Research-0078D4?style=for-the-badge&logo=microsoft&logoColor=white">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-arquitectura">Arquitectura</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-modos-de-ejecución">Ejecución</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**JARVIS (HuggingGPT)** es una arquitectura de Inteligencia Artificial que utiliza un LLM como controlador principal capaz de coordinar múltiples modelos especializados para resolver tareas complejas.

El objetivo del proyecto es acercarse al concepto de:

- 🧠 Inteligencia Artificial General (AGI)
- 🤖 Automatización de tareas complejas
- 🔗 Orquestación de modelos IA
- 🖼️ Procesamiento multimodal
- 🎙️ Voz, texto e imágenes
- ⚡ Integración con Hugging Face

---

# ✨ Características

## 🧠 Controlador Inteligente

- Análisis de instrucciones
- Comprensión contextual
- Planeación automática
- Gestión de modelos IA

---

## 🤖 Orquestación de Modelos

- Selección automática de modelos
- Coordinación entre herramientas
- Ejecución paralela
- Integración de resultados

---

## 🖼️ IA Multimodal

- Procesamiento de imágenes
- Procesamiento de texto
- Generación de imágenes
- Reconocimiento visual

---

## ⚡ Automatización

- Descomposición de tareas
- Planificación inteligente
- Ejecución autónoma
- Respuestas generadas automáticamente

---

# 🏗️ Arquitectura

## 1️⃣ Task Planning

El LLM analiza la solicitud del usuario y divide el problema en múltiples subtareas.

### Funciones

- Comprensión de intención
- Desglose de procesos
- Planificación automática

---

## 2️⃣ Model Selection

JARVIS selecciona automáticamente los modelos adecuados desde Hugging Face.

### Funciones

- Evaluación de capacidades
- Selección inteligente
- Compatibilidad automática

---

## 3️⃣ Task Execution

Los modelos seleccionados ejecutan cada tarea asignada.

### Funciones

- Procesamiento distribuido
- Ejecución multimodal
- Integración de resultados

---

## 4️⃣ Response Generation

El LLM recopila los resultados y genera una respuesta final.

### Funciones

- Interpretación de resultados
- Generación de respuestas
- Comunicación natural

---

# 🚀 Capacidades

## 📝 Procesamiento de Texto

- Resúmenes
- Traducción
- Preguntas y respuestas
- Extracción de entidades

---

## 🖼️ Visión Computacional

- Detección de objetos
- Clasificación de imágenes
- Captioning
- Segmentación

---

## 🎨 Generación de Imágenes

- Stable Diffusion
- ControlNet
- Image-to-Image
- Text-to-Image

---

## 🎙️ Audio e Inteligencia Multimedia

- Reconocimiento de voz
- Procesamiento de audio
- Generación multimedia
- Conversión multimodal

---

# 🛠️ Tecnologías utilizadas

## 🤖 Inteligencia Artificial

<p>
  <img src="https://skillicons.dev/icons?i=python" />
</p>

- OpenAI GPT
- Hugging Face
- Transformers
- ControlNet
- Stable Diffusion

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=python,fastapi" />
</p>

- Python
- APIs REST
- Servidor de modelos
- Orquestación de tareas

---

## 🌐 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,react" />
</p>

- React
- Node.js
- Web Client
- Gradio

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,docker" />
</p>

- Git
- GitHub
- Docker
- VS Code

---

# 📂 Estructura del proyecto

```bash
SistemaIAJARVIS/
│
├── server/
│   ├── configs/
│   ├── models/
│   ├── awesome_chat.py
│   └── models_server.py
│
├── web/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── hugginggpt/
│   ├── assets/
│   └── docs/
│
├── taskbench/
├── easytool/
├── Dockerfile
└── README.md
```

---

# ⚡ Requisitos

## Configuración recomendada

- Ubuntu 16.04+
- GPU NVIDIA
- VRAM 24GB+
- RAM 16GB+
- Disco 284GB+

---

## Configuración ligera

- Ubuntu 16.04+
- Conexión a Hugging Face
- Sin modelos locales

---

# 🚀 Instalación

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/SistemaIAJARVIS.git
```

---

## 2️⃣ Entrar al proyecto

```bash
cd SistemaIAJARVIS
```

---

## 3️⃣ Crear entorno virtual

```bash
conda create -n jarvis python=3.8
conda activate jarvis
```

---

## 4️⃣ Instalar PyTorch

```bash
conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia
```

---

## 5️⃣ Instalar dependencias

```bash
pip install -r requirements.txt
```

---

# 🔑 Configuración

Agregar credenciales:

```env
OPENAI_API_KEY=YOUR_KEY
HUGGINGFACE_ACCESS_TOKEN=YOUR_TOKEN
```

o modificar:

```yaml
server/configs/config.default.yaml
```

---

# 🖥️ Modos de ejecución

## 🌐 Server Mode

Ejecuta la API principal.

```bash
python models_server.py --config configs/config.default.yaml

python awesome_chat.py \
--config configs/config.default.yaml \
--mode server
```

---

## 💻 CLI Mode

Uso desde terminal.

```bash
python awesome_chat.py \
--config configs/config.default.yaml \
--mode cli
```

---

## 🌍 Web Mode

Cliente web basado en React.

```bash
cd web

npm install

npm run dev
```

---

## 🎛️ Gradio Mode

Interfaz rápida para pruebas.

```bash
python models_server.py \
--config configs/config.gradio.yaml

python run_gradio_demo.py \
--config configs/config.gradio.yaml
```

---

# 📡 API REST

## Endpoints principales

### 🧠 HuggingGPT

```http
POST /hugginggpt
```

Servicio completo.

---

### 📋 Tasks

```http
POST /tasks
```

Obtiene planificación de tareas.

---

### ⚙️ Results

```http
POST /results
```

Obtiene resultados intermedios.

---

# 🧠 Casos de uso

## Automatización Inteligente

- Análisis documental
- Procesamiento multimedia
- Generación de imágenes
- Asistentes virtuales

---

## Investigación IA

- Sistemas multiagente
- AGI experimental
- Coordinación de modelos
- Tool Learning

---

## Aplicaciones Empresariales

- Automatización de procesos
- Asistentes corporativos
- Análisis de datos
- Generación de contenido

---

# 📊 Proyectos relacionados

## 🔧 EasyTool

Herramienta para simplificar el uso de herramientas por agentes LLM.

---

## 📈 TaskBench

Benchmark para evaluar automatización de tareas mediante modelos de lenguaje.

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- Más modelos open source
- Mejor planificación de tareas
- Integración con nuevos LLMs
- Agentes autónomos avanzados
- Mayor soporte multimodal

---

# 📚 Publicaciones

## HuggingGPT

```bibtex
@inproceedings{shen2023hugginggpt,
title={HuggingGPT},
year={2023}
}
```

---

## TaskBench

```bibtex
@article{shen2023taskbench,
title={TaskBench},
year={2023}
}
```

---

## EasyTool

```bibtex
@article{yuan2024easytool,
title={EasyTool},
year={2024}
}
```

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes - FullStack Developer

Investigación avanzada en sistemas multimodales, agentes autónomos e Inteligencia Artificial General.

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source destinado a investigación y desarrollo de sistemas avanzados de Inteligencia Artificial.

---

<div align="center">

### 🤖 SistemaIAJARVIS — conectando LLMs con cientos de modelos IA para acercarnos a la AGI 🚀

</div>
