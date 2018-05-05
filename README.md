# Introducción a Flask

https://github.com/categulario/curso_flask

Repositorio creado para el taller de Flask en la FEI el 5 de mayo del 2018

## ¿Por qué fĺask?

* es compacto y modular
* puedes empezar con los componentes mínimos y añadir más en el camino

## ¿En dónde flask?

* si quieres gran flexibilidad en un proyecto
* si quieres el poder de un framework sin la complicación de todas sus posibles
  herramientas
* Como backend para una Single Page Application o para una aplicación movil

## ¿Qué cosas cool has hecho con flask?

* https://getfleety.com
* https://github.com/tracsa/cacahuate

## ¿Cómo flask?

* python 3
* virtualenv, siempre, virtualenv
* ten un archivo requirements.txt
* organiza el proyecto

    proyecto/
        tlacuache/
            views/
            models/
            templates/
            __init__.py
        test/
            api_test.py
        setup.py

* nunca olvides la documentación oficial http://flask.pocoo.org/

## Extensiones, ¡las quiero!

http://flask.pocoo.org/extensions/

## Testing

__El código sin tests está roto por defecto__

pytest

## Ok, va, te lo compro, ¿Cómo lo mandamos a producción?

* nginx + gunicorn + systemd
