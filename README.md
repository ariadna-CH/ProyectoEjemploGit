# Práctica 1: Introducción a Git

## Descripción
La práctica tiene como objetivo aprender los comandos básicos de Git, como crear un repositorio, realizar commits, ignorar archivos, crear archivos y subir cambios a un repositorio remoto.
El proyecto contiene un programa básico en Python que imprime un mensaje en la consola, contiene el archuvo debug.log que es un ejemplo para que podamos ignorar ese tipo de archivos con ayuda del archivo .gitignore.

## Instrucciones de uso para incluir cómo ejecutar el programa HolaMundo.py.
1. Clona el repositorio desde GitHub.
2. Accede a la carpeta `ProyectoEjemploGit`. Con cd copias la dirección 
"Ejemplo: C:\Users\arybo\OneDrive\Desktop\Sistemas Distribuidos\ProyectoEjemploGit "
3. Ejecuta el programa en gitbash con el siguiente comando:

   python HolaMundo.py

## Comandos utilizados
1. mkdir ProyectoEjemploGit
2. git init
3. git add
4. git commit
5. touch debug.log
6. echo "*.log" > .gitignore
7. git status
8. git remote set-url origin https://ariadna-CH@github.com/ariadna-CH/ProyectoEjemploGit.git
9. git push
10. git config --global user.name "Ariadna Cruz"
11. git config --global user.email "ariadna.cruz@cua.uam.mx"
12. git remote -v

## Notas sobre el archivo .gitignore
El archivo .gitignore fue creado para evitar que archivos de tipo .log se suban al repositorio. En este caso, el archivo que se creó llamado debug.log fue ignorado, esto quiere decir que no aparece en el repositorio remoto.
Para corroborar que el archivo debug.log no se subió, se puede comprobar en GitHub en el listado de archivos y vefiricar que no aparezca.