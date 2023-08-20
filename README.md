# vincular_vscode_github
Este es un tutorial básico de como subir un archivo desde visual studio code a github
TITULO: Vincular Visual Studio Code con Github
AUTOR: Uriel Alvarez
MOTIVO: El presente tutorial surge por algunas preguntas que suelen hacerme mis alumnos. Voy a tratarlo de explicar de una forma sencilla. No es la unica forma pero es la que yo uso para subir mis archivos a github desde el editor de código Visual Studio Code.

# Tutorial Basico de como subir archivos desde Visual Studio Code a GitHub

## Pasos
**Paso 1:** Instalar Git y Configurar GitHub:
Si aún no tienes Git instalado en tu sistema, descárgalo e instálalo desde el sitio oficial de Git. Luego, crea una cuenta en GitHub si aún no tienes una.

**Paso 2:** Crear un Repositorio en GitHub:
Inicia sesión en tu cuenta de GitHub y crea un nuevo repositorio vacío. Asegúrate de tomar nota de la URL del repositorio.

**Paso 3:** Crear un Proyecto en Visual Studio Code:
Crea una carpeta en tu sistema para tu proyecto. Abre Visual Studio Code y abre la carpeta recién creada como proyecto.

**Paso 4:** Inicializar el Repositorio Git:
Abre una terminal en Visual Studio Code. Puedes hacerlo yendo a View > Terminal. En la terminal, navega a la carpeta de tu proyecto y ejecuta los siguientes comandos:

git init

**Paso 5:** Agregar Archivos al Repositorio:
Agrega los archivos de tu proyecto al repositorio Git utilizando el comando:
git add .

**Paso 6:** Hacer un Commit:
Haz un commit de los cambios utilizando el comando:
git commit -m "Primer commit"

**Paso 7:** Conectar con GitHub:
Conecta tu repositorio local con tu repositorio en GitHub utilizando el comando:

git remote add origin URL_del_repositorio_en_GitHub

Sustituye URL_del_repositorio_en_GitHub por la URL del repositorio que creaste en GitHub.

**Paso 8:** Subir al Repositorio en GitHub:
Sube tus cambios al repositorio en GitHub utilizando el comando:

git push -u origin master

Si estás utilizando una rama diferente a master, asegúrate de reemplazar master con el nombre de tu rama.

**Paso 9:** Sincronizar Cambios Futuros:
Después de realizar cambios en tu proyecto, puedes seguir estos pasos para hacer nuevos commits y sincronizar con GitHub utilizando los comandos git add, git commit y git push.
