# Curso de programación en Python

Este repositorio contiene el material de la asignatura de Informática de primer curso del grado en Ingeniería Aeroespacial de la UPM. Para acceder a la web, se puede hacer click en el siguiente botón:

[![Jupyter Book Badge](https://jupyterbook.org/badge.svg)](https://mathetsiae.github.io/InformaticaGIA/intro.html)

## Uso local del libro con el material del curso

### Pasos para ejecutar el libro

Para desarrollar localmente el libro, se deben realizar los siguientes pasos:

1. Clonar este repositorio (idealmente utilizando `git clone`)
2. Ejecutar `pip install -r requirements.txt` en la carpeta del archivo (es recomendable hacer esto en un entorno virtual de Python para no generar conflictos con el entorno existente)
3. (Opcional) Editar los Jupyter notebooks dentro del directorio `book/notebooks`
4. Ejecutar `jupyter-book clean book/` para eliminar cualquier construcción previa del libro
5. Ejecutar `jupyter-book build book/` para generar el libro con el material del curso

Una versión completamente renderizada del libro en HTML se generará en `book/_build/html/`. Se puede ejecutar en cualquier navegador
