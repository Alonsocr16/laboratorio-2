# laboratorio-2
laboratorio2 
esto es una prueba Alonso
Test Rabase Andrew
Guía de comandos básicos de Git

git add
Este comando se utiliza para agregar archivos al área de preparación (staging area), antes de realizar un commit. Permite seleccionar qué cambios se incluirán en la siguiente confirmación. Por ejemplo, git add archivo.txt agrega un archivo específico, mientras que git add . agrega todos los cambios del directorio actual.

git commit -m
Crea un nuevo commit con los archivos que se encuentran en el área de preparación. Cada commit debe tener un mensaje que describa claramente los cambios realizados. Un ejemplo sería git commit -m "actualizar documentación".

git push
Envía los commits del repositorio local al remoto, como GitHub. Se usa después de confirmar los cambios localmente para que queden reflejados en línea. Por ejemplo, git push origin main sube los cambios a la rama principal.

git pull
Descarga los últimos cambios del repositorio remoto y los integra con tu copia local. Es útil para mantener el proyecto actualizado antes de hacer nuevos commits. Por ejemplo, git pull origin main trae los cambios más recientes de la rama principal.

git rebase
Permite reestructurar el historial de commits moviendo los cambios de una rama sobre otra. Se usa para mantener un historial más limpio y lineal. Por ejemplo, git rebase origin/main actualiza tu rama aplicando tus commits sobre la versión más reciente de la rama principal.

git rebase -i HEAD~x hace un rebase interactivo, que te permite combinar, editar o eliminar los últimos commits. Se usa para limpiar el historial antes de subir los cambios. Por ejemplo, git rebase -i HEAD~3 te deja revisar y modificar los tres últimos commits.

git status
Muestra el estado actual del repositorio: qué archivos han cambiado, cuáles están listos para commit y cuáles no están rastreados por Git. Es uno de los comandos más usados para verificar el progreso antes de confirmar los cambios.

git log
Muestra el historial de commits realizados en el repositorio, con información como el autor, la fecha y el mensaje de cada commit. Con la opción --oneline --graph --decorate se puede ver un resumen visual más compacto y ordenado.

git diff
Muestra las diferencias entre el contenido del repositorio local y el último commit. Sirve para revisar qué líneas se modificaron antes de agregarlas o confirmarlas. Por ejemplo, git diff muestra los cambios sin agregar, y git diff --staged muestra los que ya están listos para commit.

git branch
Permite crear, listar y eliminar ramas. Con git branch puedes ver las ramas existentes, y con git branch nombre-rama crear una nueva. Las ramas se utilizan para desarrollar funcionalidades de manera aislada sin afectar la rama principal.

git branch -D
Elimina una rama local de manera forzada. Este comando es útil cuando una rama ya fue fusionada o no se necesita más. Por ejemplo, git branch -D feature/login borra la rama llamada feature/login del entorno local.

git checkout
Sirve para cambiar de rama o restaurar archivos a un estado anterior. Por ejemplo, git checkout main cambia a la rama principal, y git checkout -b nueva-rama crea una nueva rama y cambia a ella. También se puede usar git checkout -- archivo.txt para descartar cambios locales en un archivo.