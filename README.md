# 🎨 SDXL Image Generator WebUI (Google Colab)

Generador interactivo de imágenes fotorrealistas y conceptuales basado en **Stable Diffusion XL Turbo** y la librería `diffusers` de Hugging Face, con interfaz web integrada mediante **Gradio** y almacenamiento directo en Google Drive.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gorkals04-cmyk/sdxl-image-generator-colab/blob/main/sdxl_image_generator.ipynb)

---

## 🚀 Características
- **Inferencia en GPU:** Optimizado para ejecutarse en entornos Google Colab (GPU T4 o superior).
- **Interfaz WebUI:** Controles para prompts, pasos de inferencia, guidance scale y control determinista por semilla (*seed*).
- **Autoguardado en la nube:** Exportación y respaldo automático de cada render en Google Drive con marca de tiempo (*timestamp*).
- **Enlace público:** Generación de URL temporal para compartir la aplicación sin exponer el código.

## 🛠️ Tecnologías y Librerías
- **Python 3.10+**
- **PyTorch** (aceleración por CUDA)
- **Diffusers** & **Transformers** (Hugging Face)
- **Gradio** (Frontend interactivo)

## 📖 Cómo ejecutarlo
1. Haz clic en la insignia **Open in Colab** superior.
2. Cambia el entorno de ejecución a GPU (*Entorno de ejecución > Cambiar tipo de entorno de ejecución > GPU*).
3. Ejecuta las celdas en orden secuencial.
4. Abre el enlace local o la URL pública generada por Gradio para empezar a crear imágenes.
