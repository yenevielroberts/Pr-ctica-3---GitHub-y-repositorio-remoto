## **Actividad: Remoto y repaso de comando anteriores**

*Acividad en la cual repasamos el uso de diferentes ramas en git desde la terminal
con comandos como git branch, git checkout... com tambien el uso del lenguaje 
MARKDOWN.*

#### **¿Qué es gitignore y para qué sirve?**
Es un archiv que podemos usa para evitar ncluir archivos no deseados en
nuestro git repositorio.
# Pr-ctica-3---GitHub-y-repositorio-remoto

#### **¿Qué pasa al crear un repositorio con un archivo README.md?**
*Se crea un reposotorio con el archivo README.md y aparece como título dentro
del readme elnombre del repositorio.*

#### **¿Qué pasa al crear un repositorio sin el archivo README.md?**
*Se crea un repositorio vacio,sin ningun archivo. Además te dice las opciones
 que puedes elegir para agregar archivos al repositorio.*

#### **Comando que me da Git Hub al crear un repositorio nuevo**
- echo "# Pr-ctica-3---GitHub-y-repositorio-remoto" >> README.md

- git init

- git add README.md

- git commit -m "first commit"

- git branch -M main

- git remote add origin https://github.com/yenevielroberts/Pr-ctica-3---GitHub-y-repositorio-remoto.git

- git push -u origin main

#### **Comands alias que he usado**
Mi comando a es igual a git add . 
comando s es igual a git status --short
comando log es igual a git log

### **Parte1: preparación del proyecto**


- Creacion de la carpeta GitRobertsYeneviel2425 con el comando mkdir
![creacion-de-la-carpeta](Ex3/creacion-de-la-carpeta.png)

- Creación de la carpeta src con el comndo mkdir
![creacion-de-la-carpeta-src](Ex3/creacion-de-la-carpera-src.png)

- Creación del archivo README.md con el comando cat
![Creacion-del-README](Ex3/Creacion-del-README.png)

- Inicialización del repositorio con el comando git init
- Creación del archivo .gitignore con el comando touch
![git-init-y-creacion-de-gitignore](Ex3/git-init-y-creacion-de-gitignore.png)

- Configuración delarchivo ,gitignore
![gitignore-configurado](Ex3/gitignore-configurado.png)

- Creación de los archivos index.hmtl, style.css y main.js con el comando
touch.
![creacion-del-archivo-html-css-y-js](Ex3/creacion-del-archivo-html-css-y-js.png)

- Primer git add y commit

![primer-git-add](Ex3/primer-git-add.png)
![primer-git-status](Ex3/prime-git-status.png)
![primer-commit](Ex3/primer-commit.png)

### **Parte 2: colaboración en equipo**

- Entra en git hub y crea un repositorio
- Repositorio con archivo readme
![repositorio-con-readme](Ex3/repositorio-con-readme.png)

- repositorio sin archivo readme
![creacion-del-repositorio-sin-readme](Ex3/creacion-del-repositorio-sin-readme.png)

- Vinculación del repositorio remoto con el local con los comandos:
git add remote url
git push origin main
![vinculacion-repositorio-remoto-y-local](Ex3/vinculacion-repositorio-remoto-y-local.png)

- Creación de la rama feature/documentacion con el comando git branch
![creacion-rama-featureDocumentacion](Ex3/creacion-rama-featureDocumentacion.png)

- Creación del archivo docs.md con el comando touch
![creacion-del-archivo-dcs-en-la-rama-feature](Ex3/creacion-del-archivo-dcs-en-la-rama-feature.png)

- Primer commit en la rama feature/documentacion con el comando git commit -m""

![primer-commit-rama-feature](Ex3/primer-commit-rama-feature.png)
![commit-rama-feature](Ex3/commit-rama-feature.png)

- Git pull desde la rama main con el comando git pull origin main
![git-pull](Ex3/git-pull.png)


### **Parte 3: Gestión de Archivos y Cambios**
- Creación del archivo src/app.py con el comando cat
- Git add y commit con los comandos git add . git commit -m""

![git-add-archivo-src.py.png](Ex3/git-add-archivo-src.py.png)
![status-y-commi-archivo-src-app-py](Ex3/status-y-commi-archivo-src-app-py.png)

- Visualización del historial de commit con log con un alias
![Log-de-commits-con-alias](Ex3/Log-de-commits-con-alias.png)

- Eliminación del archivo src/app.py con el comando rm -f
![borro-el-archivo-src.app.py](Ex3/borro-el-archivo-src.app.py.png)

- Recuperación del archivo eliminado con el comando git restore
![recupero-el-archivo-src-py.png](Ex3/recupero-el-archivo-src-py.png)

- Merge de las ramas desde la rama main con el comando git checkout main y luego git merge feature/documentacion
![merge-de-las-dos-ramas-desde-el-main](Ex3/merge-de-las-dos-ramas-desde-el-main.png)

- Verificar los cambios realizados y el historial con el alias log
![historial](Ex3/historial.png)

### **Parte 4: Entrega del Proyecto**
- Push final con el comando git push origin main
![push-final](Ex3/push-final.png)

- Eliminación de la rama feature/documentacion con el comando git branch -d nom_rama -f
![eliminacion-de-la-ramafeature](Ex3/eliminacion-de-la-ramafeature.png)

- Listar el contenido de cada directorio
![lista-de-los-directorios](Ex3/lista-de-los-directorios.png)

- Contenido de los últimos archivos con el comando cat
![contenido-html](Ex3/contenido-html.png)
![contenido-css](Ex3/contenido-css.png)
![contenido-mainjs](Ex3/contenido-mainjs-png)
![contenido-docs](Ex3/contenido-docs.png)


-Mostrar el contenido de cada directorio
![]()
