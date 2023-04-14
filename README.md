# Laboratorio de Git

Pruebas con git y github, para ver como funciona git. He enlazado el proyecto a este repositorio y he realizado varias acciones con git desde local: he modificado archivos, creado commits, una rama nueva y un merge, he ido subiendo los cambios al repositorio.

## Pasos y comandos usados.

1. Crear el repositorio en local
2. Desde la terminal de Visual Estudio Code (la tarminal a partir de ahora) he escrito:
   ```
   git init
   ```
3. He añadido los archivos al stage, desde la terminal con:
   ```
   git add .
   ```
4. Desde la terminal he creado un commit con:
   ```
   git commit -m "aquí he añadido mi texto"
   ```
5. He creado en Github, este repositorio.
6. He enlazado mi proyecto local con el repositorio de Github, con el link SSH. En el terminal he escrito:
   ```
   git remote add origin (seguido de este espacio pego el link sin paréntesis)
   ```
7. Ahora queda enlazar las ramas de local y remoto, para ello desde la terminal he ejecutado:
   ```
   git push --set-upstream origin main
   ```
8. He comprobado que se ha subido correctamente llendo al repositorio de Github.
9. En local he creado un archivo nuevo el archivo README.md que estás leyendo. Lo he añadido al stage como anteriormente y he añadido un commit nuevo para este cambio. Al terminar he subido los cambios al repositorio con:
   ```
   git push
   ```
10.
