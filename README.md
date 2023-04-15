# Laboratorio de Git

Pruebas con Git y Github, para ver como funciona Git. He enlazado el proyecto a este repositorio y he realizado varias acciones con git desde local: he modificado archivos, creado commits, una rama nueva y un merge, y he ido subiendo los cambios al repositorio.

### Pasos y comandos usados.

1.  Crear el repositorio en local.

2.  Desde la terminal de Visual Estudio Code (la terminal a partir de ahora) he escrito:
    ```
    git init
    ```
3.  He añadido los archivos al stage, desde la terminal con:
    ```
    git add .
    ```
4.  Desde la terminal he creado un commit con:
    ```
    git commit -m "aquí he añadido mi texto"
    ```
5.  He creado en Github, este repositorio.

6.  He enlazado mi proyecto local con el repositorio de Github, con el link SSH. En el terminal he escrito:
    ```
    git remote add origin (seguido de este espacio pego el link sin paréntesis)
    ```
7.  Ahora queda enlazar las ramas de local y remoto, para ello desde la terminal he ejecutado:
    ```
    git push --set-upstream origin main
    ```
8.  He comprobado que se ha subido correctamente yendo al repositorio de Github.

9.  En local he creado un archivo nuevo, el archivo README.md que estás leyendo. Lo he añadido al stage como anteriormente y he añadido un commit nuevo para este cambio. Al terminar he subido los cambios al repositorio con:

    ```
    git push
    ```

10. Desde local he creado una nueva rama llamada "development" con:

    ```
    git branch development
    ```

11. Después he cambiado a la rama que he creado con:

    ```
    git switch development
    ```

12. En esta rama he cambiado el h1, he subido los cambios al stage, he creado un commit y he vuelto a la rama "main", y he subido los cambios al repositorio.

13. Desde la rama "main" he realizado un merge de la rama "development" con:

    ```
    git merge development
    ```

14. En el merge no ha habido conflictos, por lo que después he hecho un push de los cambios al repositorio.

15. Durante el proceso he visto como iban los cambios en la terminal con:

    ```
    git status (ver el estado de los cambios)
    git git log --oneline --decorate --graph --all (ver las ramas con los commits de forma visual en la terminal)
    git branch (ver las ramas creadas)
    ```

16. Por último he subido cambios a este Readme.md. Como sólo eran modificaciones de un archivo y no había ningún archivo nuevo, he añadido las modificaciones al stage en un commit con:

        ```
        git commit -am "aquí el texto"
        ```

    Después he hecho un push de los cambios.

17. Muchos de estos cambios los podría haber realizado con la parte visual de git en Visual Studio Code, como estoy más familiarizada con ese proceso he preferido realizarlo a través de la terminal de este.

Con este ejercicio he entendido mejor como funciona Git, y he aprendido nuevos comandos para trabajar desde la terminal.
