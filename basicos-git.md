# Básicos de Git

## ¿Qué es Git?
**Git** es un sistema de control de versiones distribuido que registra los cambios realizados en los archivos de un proyecto a lo largo del tiempo. Permite trabajar en equipo, recuperar versiones anteriores si algo falla y desarrollar nuevas funciones sin romper el código principal.

## Conceptos clave
- **Repositorio:** Carpeta del proyecto que guarda todos los archivos y su historial completo de cambios.
- **Commit:** Punto guardado del historial con un mensaje descriptivo que indica qué cambios se hicieron.
- **Rama (*Branch*):** Línea de trabajo independiente para desarrollar una tarea sin afectar a la rama principal (`main`).
- **Pull Request (PR) y Merge:** Una PR solicita revisar e integrar los cambios de una rama en otra; el *Merge* une esos cambios definitivamente.

## Comandos básicos
- `git status`: Muestra qué archivos han cambiado o están listos para guardarse.
- `git checkout -b <rama>`: Crea una rama nueva y cambia a ella.
- `git add .`: Prepara los archivos modificados para el siguiente commit.
- `git commit -m "mensaje"`: Guarda los cambios preparados en el historial.
- `git push`: Sube tus commits al repositorio remoto en GitHub.
- `git pull`: Descarga y actualiza los cambios más recientes del repositorio remoto.
