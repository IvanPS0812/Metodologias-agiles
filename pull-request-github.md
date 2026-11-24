# Pasos para hacer una Pull Request en GitHub

Una Pull Request (PR) es una herramienta de GitHub que permite proponer cambios realizados en una rama para incorporarlos a otra rama, normalmente `main`. Antes de integrar los cambios, otros compañeros pueden revisar el código o el contenido y sugerir modificaciones.

### 1. Crear una rama nueva
Acceder al repositorio y crear una rama nueva desde main para trabajar sin modificar directamente la rama principal.

### 2. Realizar los cambios
Crear o editar los archivos necesarios dentro de la nueva rama y guardar el trabajo realizado.

### 3. Hacer un commit
Guardar los cambios mediante un commit con un mensaje descriptivo que explique qué se ha modificado.

### 4. Subir los cambios a GitHub
Publicar la rama en el repositorio remoto para que los demás miembros del equipo puedan consultar los cambios.

### 5. Crear la Pull Request
Entrar en la pestaña **Pull requests**, pulsar **New pull request**, seleccionar la rama de origen y la rama de destino (`main`).

### 6. Añadir una descripción
Escribir un título y una descripción explicando los cambios realizados. También hay que añadir `Closes #3` para vincular la Pull Request con el Issue correspondiente.

### 7. Revisar los cambios
Otro miembro del equipo debe entrar en **Files changed**, comprobar las modificaciones y dejar comentarios o sugerencias. El autor no puede aprobar su propia Pull Request.

### 8. Aprobar y hacer Merge
Cuando los cambios estén revisados y aprobados por otro compañero, se puede pulsar **Merge pull request** para incorporar los cambios a la rama principal.

### Conclusión
Las Pull Requests permiten trabajar en equipo de forma organizada, revisar las modificaciones antes de incorporarlas al proyecto y mantener un historial de los cambios realizados.
