Taller de análisis de datos
===========================

<p>
El taller tiene como objetivo introducir al análisis de datos con Python, revisar topicos de machine learning, como también de redes sociales. Se propone que en el taller surjan desafíos de análisis para abordar ya sea en grupo o individualmente y documentarlos para la comunidad. 
</p>


Materiales
==========
<ul>
    <li> Python3 </li>
    <li> Jupyter (ipython) </li>
    <li> una api de twitter </li>

</ul>

En el taller se desearía que los y las asistentes utilicen alguna distribución de gnu/Linux, en caso contrario podrían cambiar nombres de algunas librerías o formas de resolver cosas técnicas

**Instalación**

1. Instalar PIP

`
apt-get install python3-pip
`

2. Instalar VirtualEnv

`
pip3 install virtualenv
`

Puede que arroje el siguiente error: *"You are using pip version 8.1.1, however version 9.0.1 is available.
You should consider upgrading via the 'pip install --upgrade pip' command"* - No pasa nada

3. Crear una carpeta "taller_data" con una subcarpeta "venv"

4. Desde la terminal, navegar hasta la carpeta *venv* y crear el entorno virtual haciendo:

`
virtualenv .
`

Esto va a crear varias carpetas en *venv*, entre ellas la carpeta *bin*.

5. Desde la terminal, navegar hasta venv y correr el entorno virtual:

`
source bin/activate
`

Esto va a agregar *(venv)* al inicio del prompt, es decir que estamos dentro del entorno virtual. Tenemos que ver lo siguiente:

`
(venv) user@home:~/taller_data/venv$
`

6. Una vez que estamos en el entorno virtual, instalamos Jupyter:

`
pip install jupyter
`

7. Ejecutamos Jupyter

`
ipython notebook
`


Tópicos
=======

<ul>
    <li> Introducción a Python (sesión 1) </li>
    <li> Numpy y Pndas (sesión 1)</li>
    <li> Visualización con Matplotlib </li>
    <li> Topicos de machine learning </li>
    <li> texto: NLTK </li>
    <li> Api Twitter y analisis </li>
    <li> Despliegue en Gephi </li>

</ul>
<p>
La velocidad con que abordemos los tópicos y profundidad será acorde a lo que como grupo vayamos decidiendo. El taller se comenzará con python como lenguaje base pero es libre elección de los integrantes escoger sus herramientas y compartirlas con el grupo. En el caso de **R-project** sería adecuado tener instalado **Rstudio**. 
</p>

