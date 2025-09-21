# Entregable 2: Comparación de distintos espacios de color en imágenes digitales

Este proyecto presenta un análisis completo de diferentes espacios de color y sus aplicaciones prácticas en visión por ordenador.

## Contenidos

- [Descripción](#descripción)
- [Instalación](#instalación)
- [Uso](#uso)
- [Estructura del Proyecto](#estructura-del-proyecto)

## Descripción

Este proyecto examina seis espacios de color fundamentales en visión por ordenador:

- **RGB** - Red, Green, Blue
- **HSV** - Hue, Saturation, Value
- **CIELAB** - Lightness, a*, b* 
- **YCrCb** - Luminance, Chrominance
- **Escala de Grises** - Para aplicaciones binarias
- **XYZ** - CIE 1931 color space

## Instalación

### Requisitos Previos
- Python 3.8 o superior
- pip (gestor de paquetes de Python)


### Versiones de las librerías usadas: 

opencv-python>=4.8.0
numpy>=1.24.0
matplotlib>=3.7.0
jupyter>=1.0.0
ipykernel>=6.25.0
pillow>=10.0.0

### Instalación de Dependencias

```bash
# Clonar o descargar el proyecto
cd UA2_AA1.-Comparaci-n-de-distintos-espacios-de-color-en-im-genes-digitales

# Instalar dependencias
pip install -r requirements.txt
```

### Verificación de la Instalación

```python
import cv2
import numpy as np
import matplotlib.pyplot as plt
print("✓ Todas las librerías instaladas correctamente")
```

## Uso

### Ejecución del Notebook Principal

```bash
# Iniciar Jupyter Notebook
jupyter notebook espacios_color.ipynb
```

## 📁 Estructura del Proyecto

```
UA2_AA1.-Comparaci-n-de-distintos-espacios-de-color-en-im-genes-digitales/
├── espacios_color.ipynb    # Notebook principal
├── requirements.txt        # Dependencias del proyecto
├── README.md              # Documentación (este archivo)
└── data/                  # Imágenes generadas automáticamente
    ├── gradiente_rgb.png  # Gradientes de colores primarios
    ├── colores_saturados.png # Colores puros 
    ├── codigo_barras.png  # Patrón para análisis binario
    └── tonos_piel.png     # Tonos para detección YCrCb
    └── espectro_hsv.png    # Espectro completo de HSV
    └── formas_geometricas.png  # Formas geometricas de diferentes colores y formas
```

**Antonio García Alcón** | **Sistemas de percepción** | **2025**
