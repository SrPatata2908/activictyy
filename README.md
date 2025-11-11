# activictyy

# Actividad: Aprendiendo Git y GitHub

## ¿Qué aprendí del video?
Git es un sistema de control de versiones. Piensa en él como un sistema para "guardar partidas" de tu código. Te permite registrar el historial de cambios, ver quién cambió qué, y volver a una versión anterior si algo se rompe. Funciona en tu computadora local.
GitHub es una plataforma remota (en la nube). Es un lugar para guardar tus repositorios de Git en internet. Sirve principalmente para:
Tener una copia de seguridad de tu código.
Colaborar con otras personas en el mismo proyecto.
El flujo básico: El proceso más común es:
Haces cambios en tus archivos.
Preparas los cambios que quieres guardar.
Guardas esos cambios permanentemente en el historial de tu computadora.
Subes esos "commits" a GitHub para que otros los vean o para tener tu copia de seguridad (haces un Push con git push).



## Comandos Usados
* `git clone` - Para descargar el repositorio.
* `git add` - Para preparar los archivos para el commit.
* `git commit` - Para guardar los cambios en mi historial local.
* `git push` - Para subir mis cambios a GitHub.

## Dificultades y Soluciones
Error de autenticación al hacer git push: Es el problema #1. GitHub ya no permite usar tu contraseña simple desde la terminal.
Solución común: Necesitas crear un "Token de Acceso Personal" (PAT) en la configuración de tu cuenta de GitHub y usar ese token como si fuera tu contraseña en la terminal.

Confundir git add con git commit:
Dificultad: Es común pensar que git commit guarda todo, pero solo guarda lo que le dijiste con git add primero.
Solución: Siempre usar git status para ver qué está "preparado" (staged) y qué no, antes de hacer commit.
