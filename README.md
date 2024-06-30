Clase 11 Actividad en Python
Hoy vamos a hacer actividad en Python en un día como programadores:

Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

Creamos una carpeta o directorio:

mkdir python-final
Entramos en ella:

cd python-final
Iniciamos el repositorio:

git init
Creamos un archivo:

touch finales.py
Abrimos VSC:

code .
En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:

python -V

python3 -V
Creamos el entorno virtual en Python:

python3 -m venv venv #Creamos el entorno virtual
Activamos el entorno virtual:

source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows
Hacemos actualización del pip de Python

python3 -m pip install --upgrade pip #Actualizamos el pip
Investigar ¿Qué es el pip y porque lo actualizamos?

'pip' es el sistema de gestión de paquetes para Python. Permite instalar y gestionar bibliotecas y paquetes adicionales que no están incluidos en la biblioteca estándar de Python. Con pip, puedes descargar e instalar paquetes desde el Python Package Index (PyPI), que es un repositorio de software para el lenguaje de programación Python.

¿Por qué actualizamos pip?

Mejoras y nuevas características: Las nuevas versiones de pip a menudo incluyen mejoras en el rendimiento, nuevas características y mejoras en la usabilidad.
Seguridad: Actualizar pip ayuda a garantizar que se estén utilizando versiones con los últimos parches de seguridad. Esto es crucial para evitar vulnerabilidades que podrían ser explotadas.
Compatibilidad: Las nuevas versiones de pip a menudo incluyen soporte para nuevas versiones de Python y para nuevos estándares y prácticas en el desarrollo de software. Esto asegura que pip siga siendo compatible con la infraestructura de desarrollo más reciente.
Corrección de errores: Actualizar pip puede corregir errores y problemas conocidos de versiones anteriores, proporcionando una experiencia más estable y confiable.
Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.
