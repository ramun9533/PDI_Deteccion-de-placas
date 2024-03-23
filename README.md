### Captura de Imágenes y Detección de Rectángulos

Este programa en Python utiliza la biblioteca PyQt5 para la interfaz gráfica de usuario y OpenCV para el procesamiento de imágenes. La aplicación permite cargar una imagen desde el sistema de archivos, visualizarla en la interfaz y detectar los rectángulos presentes en la imagen cargada.

### Características

- **Cargar Imagen:** Permite al usuario seleccionar una imagen desde el sistema de archivos.
- **Detección de Rectángulos:** Detecta y resalta los rectángulos presentes en la imagen cargada.
- **Guardado de Imagen:** Permite al usuario guardar la imagen procesada con un nombre único que incluye la marca de tiempo.

### Requisitos

- Python 3.x
- PyQt5
- OpenCV

### Cómo Usar

1. Instale las dependencias necesarias utilizando pip:

   ```bash
   pip install PyQt5 opencv-python
   ```

2. Ejecute el programa ejecutando el script Python `main.py`.

3. Se abrirá una ventana con los siguientes botones:
   - "Cargar Imagen": Seleccione una imagen desde el sistema de archivos.
   - "Guardar": Guarde la imagen procesada con un nombre único.
   - "Salir": Cierre la aplicación.

### Acerca del Código

El código utiliza PyQt5 para cargar la interfaz de usuario desde un archivo `.ui` y establecer la funcionalidad de los botones. OpenCV se utiliza para el procesamiento de imágenes, incluida la detección de contornos y rectángulos en la imagen cargada.

El proceso de detección de rectángulos implica convertir la imagen a escala de grises, aplicar un umbral, encontrar contornos y aproximar los contornos a polígonos. Se detectan los rectángulos que cumplen con ciertos criterios de área y se resaltan en la imagen cargada.

### Contribuciones

Las contribuciones son bienvenidas. Si desea mejorar este programa, no dude en enviar una solicitud de extracción.
