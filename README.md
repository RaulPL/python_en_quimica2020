# Curso de Python

## Instalación
En esta sección vamos a instalar __miniconda__. Debes de bajar el script 
de instalación de la siguiente página https://docs.conda.io/en/latest/miniconda.html.

Después debes de seguir las instrucciones específicas para tu sistema 
operativo, en este link se encuentra la guía https://conda.io/projects/conda/en/latest/user-guide/install/index.html

Una vez que miniconda esté instalado en tu computadora vamos a crear un 
entorno virtual en donde instalaremos los paquetes necesarios para el
curso. Lo primero que vas a a hacer es abrir una terminal y ejecutar
la siguiente línea de código:
```
conda create --name pyquimica python=3.7 jupyterlab ipywidgets
```
Esta línea creara un entorno virtual con el nombre pyquimica e instalará
la lista de dependencias especificadas. Finalmente sólo debes de activar
tu entorno de la siguiente manera:
```
conda activate pyquimica
```

Una de las lecciones consiste en crear visualizaciones de datos y 
para eso es necesario instalar y configurar la paquetería. 
Ejecuta los siguientes comandos en orden:

```
conda install -c bokeh jupyter_bokeh
jupyter labextension install @jupyter-widgets/jupyterlab-manager
jupyter labextension install @bokeh/jupyter_bokeh
jupyter labextension install @pyviz/jupyterlab_pyviz
```

## Recursos adicionales
Links a recursos en donde pueden seguir aprendiendo sobre Python:
* [Documentación oficial](https://docs.python.org/3/)
* [Tutorial de Python](https://docs.python.org/3/)





