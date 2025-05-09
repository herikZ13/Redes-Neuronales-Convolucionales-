# Redes-Neuronales-Convolucionales-
El conocimiento de la CNN paso a paso

# Tabla de Contenido: Segmentación Semántica con Redes Neuronales Convolucionales (CNN)

##  Introducción

### Diferencia entre una NN y CNN en imagenes 
- Usar una imagen en NN
  
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1RJKOaMHe1_11tGaG3E8CVuAqrxo_gUe9?usp=sharing) Comprobar si una Red neuronal MLP puede identificar fotos 


##  Redes Neuronales Convolucionales (CNN)

### 🔹 Operación de Convolución
- Relleno con ceros
- Cómo obtener diferentes o mismas dimensiones de salida
- [![Open In Colab](https://colab.research.google.com/drive/1Z-Ybvw_PrUTeFeJbeA21WSuIlo5EIxbv?usp=sharing) Operacion de convolucion y tipos de padding

### 🔹 Agrupamiento (Pooling)
- Diferentes tipos de pooling

### 🔹 Convolución Aritmética
- Transposición
- Zero-padding
- Full padding

### 🔹 Operaciones Básicas de CNN
- Convoluciones dilatadas, no lineales, 1D, 2D, 3D
- Técnicas para evitar sobreajuste: Weight Decay y Dropout
- Normalización

### 🔹 Compartición de Parámetros
- Diferencias entre CNN y una red neuronal tradicional

## 🏗️ Arquitecturas de CNN
- Transfer Learning
- Xception
- GoogLeNet

## 🧩 Segmentación Semántica con CNN

### 🔹 Introducción
- Justificación de la segmentación semántica
- Diferencias con otras estrategias
- Normalización y etiquetado

### 🔹 Módulo de Atención
- Squeeze-and-Excitation (SE)
- Atrous Spatial Pyramid Pooling (ASPP)

### 🔹 Arquitecturas para Segmentación Semántica
- U-Net
- DeepLab
- Fully Convolutional Network (FCN)

## 💡 Propuesta
- U-Net asimétrica con ASPP y Squeeze-and-Excitation (SE)

-  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Xpds6dZAJp3WUjKxSCxZDLcM7sENCASG?usp=sharing) 

## 📊 Métricas y Visualización
- Visualización de resultados
- Funciones de activación: Softmax, Sigmoid, ReLU




# Dataset utilizados:
### Aerial Image 
-[Dataset original](https://drive.google.com/drive/folders/1b8x8gcbLaAOrkQkrd_NwwDtAM1IsfE6i?usp=drive_link)

### Imagenes etiquetadas: 
- [images](https://drive.google.com/drive/folders/1WEA1YBhYZTqzvI33has5lVzKrWWR-p7z?usp=sharing)
- [mask](https://drive.google.com/drive/folders/1SOjdx6cr-rytFdPGxf3H55oEvFfoxTDc?usp=sharing)

### Resized images 144*256
- Contenido con "Data augumentation" aplicado.
  
- [Train images](https://drive.google.com/drive/folders/17u7ic4yVK5OKAgUNxaavA_MYDV43hlSB?usp=sharing)
- [Train mask](https://drive.google.com/drive/folders/17r4BFINRYrp-IQW4R4slPWqb2RBbwWEU?usp=sharing)
- [Test images](https://drive.google.com/drive/folders/17vhfswQkh9ABQly2H2nDIQBoX0Gebe4e?usp=sharing)
- [Test mask](https://drive.google.com/drive/folders/17w541LC2OM-0ABVaaTfNgTbPzBv8tqaH?usp=sharing)
