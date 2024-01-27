# Blog App

Esta es una aplicación de blog que te permite crear, leer, actualizar y eliminar publicaciones de blog.
También permite comentarlas, buscar por trigrams, feeds de RSS y alguna opción más. Al ser un ejercicio
guiado, más adelante le añadiré las opciones que pueda necesitar.

## Características

- Creación de nuevas publicaciones
- Lectura de publicaciones existentes
- Actualización de publicaciones existentes
- Eliminación de publicaciones existentes
- Creación de comentarios en las publicaciones
- Actualización de comentarios en las publicaciones
- Eliminación de comentarios en las publicaciones
- Feed de RSS, sitemap, Búsqueda por palabras clave en postgresql etc.

## Tecnologías utilizadas

- Django
- PostgreSQL

## Instalación

1. Clona este repositorio.
2. Navega a la carpeta del proyecto.
3. Ejecuta el siguiente comando para instalar las dependencias:

    ``` pip install requirements.txt
    ```

4. Configura las variables de entorno en un archivo `.env`.
5. Ejecuta el siguiente comando para iniciar la aplicación:

    ``` python3 manage.py runserver
    ```

## Contribución

Si deseas contribuir a este proyecto, sigue los siguientes pasos:

1. Haz un fork de este repositorio.
2. Crea una rama con tu nueva funcionalidad: `git checkout -b nueva-funcionalidad`.
3. Realiza los cambios necesarios y realiza un commit: `git commit -m "Agrega nueva funcionalidad"`.
4. Haz push a la rama: `git push origin nueva-funcionalidad`.
5. Abre una pull request en este repositorio.

Aunque no es necesario, es un ejercicio de Django y sólo está para usarlo en el futuro de ser necesario.

## Licencia

Este proyecto está bajo la Licencia Apache2.0. Para más detalles, consulta el archivo [LICENSE](LICENSE).
Al ser realizado por Antonio Melé, realmente estaría bajo la Licencia MIT, todavía estoy trasteando con las licencias,
qué nos van a volver locos.
