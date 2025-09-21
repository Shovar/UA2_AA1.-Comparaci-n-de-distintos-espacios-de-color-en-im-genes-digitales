# Entregable 2: Comparación de distintos espacios de color en imágenes digitales

Este proyecto presenta un análisis completo de diferentes espacios de color y sus aplicaciones prácticas en visión por ordenador.

## Contenidos

- [Descripción](#descripción)
- [Espacios de Color Analizados](#espacios-de-color-analizados)
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

Cada espacio se analiza con ejemplos prácticos, visualizaciones comparativas y aplicaciones reales en visión por ordenador.

## Espacios de Color Analizados

### RGB (Red, Green, Blue)
- **Aplicaciones**: Visualización, captura de imágenes, processing básico
- **Ventajas**: Intuitivo, estándar en dispositivos
- **Análisis**: Separación de canales, histogramas, correlaciones

### HSV (Hue, Saturation, Value)
- **Aplicaciones**: Segmentación por color, detección de objetos
- **Ventajas**: Robusto a cambios de iluminación
- **Análisis**: Segmentación automática, tracking de colores

### CIELAB (L*a*b*)
- **Aplicaciones**: Control de calidad, diferencias perceptuales
- **Ventajas**: Uniforme perceptualmente, Delta E preciso
- **Análisis**: Cálculo de diferencias de color, matching cromático

### YCrCb
- **Aplicaciones**: Detección de piel, compresión de video
- **Ventajas**: Separación luminancia/cromaticidad
- **Análisis**: Detección de tonos de piel, análisis Cr-Cb

### Escala de Grises
- **Aplicaciones**: OCR, códigos de barras, análisis estructural
- **Ventajas**: Máxima eficiencia computacional
- **Análisis**: Métodos de conversión, binarización, detección de bordes

### XYZ (CIE 1931)
- **Aplicaciones**: Calibración, investigación, estándares
- **Ventajas**: Referencia absoluta, independiente del dispositivo
- **Análisis**: Temperatura de color, coordenadas de cromaticidad

## Instalación

### Requisitos Previos
- Python 3.8 o superior
- pip (gestor de paquetes de Python)

### Instalación de Dependencias

```bash
# Clonar o descargar el proyecto
cd Entrega2

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
Entrega2/
├── espacios_color.ipynb    # Notebook principal
├── requirements.txt        # Dependencias del proyecto
├── README.md              # Documentación (este archivo)
└── data/                  # Imágenes generadas automáticamente
    ├── gradiente_rgb.png  # Gradientes de colores primarios
    ├── colores_saturados.png # Colores puros para HSV
    ├── codigo_barras.png  # Patrón para análisis binario
    └── tonos_piel.png     # Tonos para detección YCrCb
```

**Antonio García Alcón** | **Sistemas de percepción** | **2025**# UA2_AA1.-Comparaci-n-de-distintos-espacios-de-color-en-im-genes-digitales
