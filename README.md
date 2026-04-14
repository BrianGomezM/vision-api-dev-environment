# Object Detection - Entorno de Desarrollo (A7)

## Descripción
Este proyecto corresponde a la configuración del entorno de desarrollo para un sistema de detección de objetos. Se establecen las herramientas, librerías y estructura necesarias para ejecutar modelos de visión por computador y desarrollar una API.

## Tecnologías utilizadas

* Python 3.10.11
* PyTorch
* Ultralytics (YOLOv8)
* OpenCV
* FastAPI
* Pandas
* Matplotlib
* Psutil

## Estructura del proyecto

app/
routes/
services/
utils/

test_images/

venv/
run.py
requirements.txt
README.md


## Instalación
1. Clonar el repositorio:
    git clone https://github.com/BrianGomezM/vision-api-dev-environment.git
    Ingresar al proyecto:
    cd vision-api-dev-environment
2. Crear entorno virtual:
    python -m venv venv

4. Activar entorno:
    Windows:
    venv\Scripts\activate

5. Instalar dependencias:
    pip install -r requirements.txt


## Ejecución
Ejecutar el entorno de desarrollo:
python run.py


## Control de versiones
Se utilizó Git para el control de versiones y GitHub para el almacenamiento del repositorio. Se incluyó un archivo .gitignore para excluir archivos innecesarios como el entorno virtual, resultados y archivos temporales.


## Objetivo
Configurar un entorno de desarrollo funcional y organizado que permita ejecutar modelos de detección de objetos y facilitar el desarrollo de futuras implementaciones.
