# Creación de una carpeta por voz utilizando Vosk

Si quieres aprender a utilizar Vosk para llevar a cabo más acciones a parte de crear un carpeta por voz consulta el siguiente archivo [004-mas-acciones.md](https://github.com/verybboy/EcoEco-Accessible-OS/blob/main/virtual-environment-vosk/tutorial-ES/004-mas-acciones.md)

## Paso 1: Script en Python que estará escuchando continuamente y creará una carpeta cada vez que detecte la frase "crear carpeta <nombre_de_la_carpeta>"

**¡IMPORTANTE!** Aunque los nombres de los scripts estén en inglés, hay diferentes versiones para cada idioma.

Descarga el archivo [voice_folder_creator.py](https://github.com/verybboy/EcoEco-Accessible-OS/blob/main/virtual-environment-vosk/tutorial-ES/scripts/voice_folder_creator.py)

## Paso 2: Activamos nuestro entorno virtual y ejecutamos el script

Activar entorno virtual:

```bash
source ~/vosk_env/bin/activate
```

Ejecutar script:

```bash
python3 ~/voice_folder_creator.py
```

## Ejemplo de salida

