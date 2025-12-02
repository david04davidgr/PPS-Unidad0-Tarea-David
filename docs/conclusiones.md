# Conclusiones

Finalmente realizamos la tarea y hemos conseguido un repositorio en `GitHub`, el cuál mediante una pipeline que se ejecuta automáticamente tras ralizar un push al repositorio, tras este push, es la pipeline la encargada de recoger los archivos de documentación subidos al repositorio y mediante la ejecución de `MkDocs`, generar esta web automática y organizar e incrustar los archivos de documentación

## Resultados clave

* **Documentación Automatizada con MkDocs:** Se configuró y desplegó una estructura de documentación profesional y navegable, asegurando la consistencia del contenido.
* **Pipeline CI/CD Funcional:** Se implementó un *workflow* de `GitHub Actions` que automatiza la generación y el despliegue de la documentación en **GitHub Pages** ante cada *push* a la rama principal.
* **Entorno de Despliegue Reproducible:** Se utilizó `Docker` para crear un contenedor Nginx que puede servir la documentación de manera local y reproducible, validando la documentación antes del *deploy* final.
* **Flujo de Trabajo Estándar de Git:** Se mantuvo un control de versiones y un flujo de trabajo claro desde la clonación del repositorio hasta la confirmación y subida de cambios.

## Opinión

A través de esta tarea, se puede comprender de manera práctica lo necesaria que es la automatización y cómo la seguridad puede llegar a integrarse de forma automática desde el inicio del ciclo de desarrollo de software (DevSecOps).

Además de poner en práctica el uso y montaje de dockers, en este caso para desplegar la web mediante un servicio Nginx de forma local.

