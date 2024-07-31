# Download Manager

Este es un sencillo gestor de descargas en Python que permite descargar archivos desde una URL específica. Soporta descargas tanto secuenciales como paralelas utilizando múltiples hilos.

## Requisitos

- Python 3.x
- `requests` (puedes instalarlo con `pip install requests`)
- `tqdm` (puedes instalarlo con `pip install tqdm`)

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/nombre_del_repositorio.git
   cd nombre_del_repositorio

2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt

## Uso
```bash
python CMD-DownloadManager.py

El programa te pedirá la URL del archivo, el nombre con el que deseas guardarlo y la ubicación donde quieres almacenarlo. También te dará la opción de descargar el archivo utilizando múltiples hilos para acelerar el proceso.

