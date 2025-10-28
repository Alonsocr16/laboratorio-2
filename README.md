# laboratorio-2
@"
# Comandos básicos de Git

## ¿Qué es un commit?
Un commit es un guardado de los cambios del proyecto en tu computadora. Representa una versión específica del código con una descripción de qué cambió.

¿Cómo se hace?
git add .
git commit -m "Descripción de los cambios"

## ¿Qué es un push y cómo se hace?
Push envía tus commits al repositorio remoto (GitHub).
git push

## ¿Qué es un pull y cómo se hace?
Pull descarga cambios del remoto a tu máquina.
git pull

## ¿Qué es un checkout y cómo se hace?
Checkout te mueve entre ramas o versiones.
git checkout nombre-de-la-rama
Ejemplo:
git checkout main
"@ | Set-Content -Encoding UTF8 README.md

git status
