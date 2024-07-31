# Download Manager

Este es un sencillo gestor de descargas en Python que permite descargar archivos desde una URL específica. Soporta descargas tanto secuenciales como paralelas utilizando múltiples hilos.

## Requisitos
 - Python 3.x
 - `requests` (puedes instalarlo con `pip install requests`)
 - `tqdm` (puedes instalarlo con `pip install tqdm`) 

## Instalación 
 1. Clona este repositorio: 

    ```bash
    git clone https://github.com/soyangelromero/CMD-Downloader.git 
    cd CMD-Downloader

 2. Instala las dependencias:

    ```bash
    pip install -r requirements.txt

 3. Uso
 Ejecuta el script en tu terminal o símbolo del sistema:
	 ```bash
	 python CMD-DownloadManager.py

El programa te pedirá la URL del archivo, el nombre con el que deseas guardarlo y la ubicación donde quieres almacenarlo. También te dará la opción de descargar el archivo utilizando múltiples hilos para acelerar el proceso.

## Contribuir
Si deseas contribuir a este proyecto, por favor, abre un issue o envía un pull request con tus cambios.

## Licencia
Este proyecto está licenciado bajo la Licencia MIT.
