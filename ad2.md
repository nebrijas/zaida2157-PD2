# ACTIVIDAD DIRIGIDA 2 
Aquí detallo el paso a paso de lo que hicimos para realizar la AD2 

- Acceder a https://github.com/nebrijas/zaida2157-PD2/settings/pages 
- Seleccionar en Source en main y root
- Ir a Add file para crear un nuevo archivo nombrado ad2.md
- Descargar Git Bash y abrirlo
- Escribir: pwd (enter)
- git clone https://github.com/nebrijas/zaida2157-PD2
- cd zaida2157-PD2/ (enter)
- ls (enter) para visualizar los archivos de la carpeta
- git config user.name zaida2157-PD2 (enter)
- git config user.email zaida2157@gmail.com (enter)
- ir a la web: https://github.com/settings/tokens
- "Generate new token" y colocar el nombre en Note (pd2). En expiration ponerle 60 días. En select scopes seleccionar "repo". Y  "Generar token".
- Hay que copiar el token que se crea 
- Volver a Git Bash y escribir:
- echo "copiar el token copiado" > ../.token 
- README.md ad1.md
- nano README.md y modificar el archivo poniéndole un título y dos enlaces uno a ad1.md y otro a ad2.md
- ver la ayuda y para salir CTRL + X 
- git status (enter)
- git add ad1.md (enter)
- git commit -m "añado ad1.md" (enter)
- git push (enter)
