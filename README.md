Taller de análisis de datos
===========================

<p>
El taller tiene como objetivo introducir al análisis de datos con Python, revisar tópicos de machine learning, como también de redes sociales. Se propone que en el taller surjan desafíos de análisis para abordar ya sea en grupo o individualmente y documentarlos para la comunidad. 
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

Instalaremos *virtualenv* como entorno virtual, otra opción podría ser *anaconda*, sin embargo, esta última instala todas las librerías cientificas, muchas de las cuales no se utilizaran, o dependiendo del proyecto serán unas u otras, por lo que venv  es una buena opción para mantener un entorno de trabajo limpio y pendiente de las  versiones que se están utilizando y con python3


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
taller_datos/venv$ virtualenv .
`

Esto va a crear varias carpetas en *venv*, entre ellas la carpeta *bin*, quedando una estructura como esta.


```
/taller_datos
    |-- README.md
    |-- Taller_data.ipynb    
    |__ /venv
        |__ /bin
            |-- activate
            |__ /include
            |__ /...
    | __ /data    
                    
```



5. Desde la terminal, navegar hasta venv y correr el entorno virtual:



`
venv$ source bin/activate
`

Esto va a agregar *(venv)* al inicio del prompt, es decir que estamos dentro del entorno virtual. Tenemos que ver lo siguiente:

`
(venv) user@home:~/taller_data/venv$
`
y volvemos a taller de datos

`venv$ cd ..
`

`(ven) user@home:~/taller_data/$
`


6. Una vez que estamos en el entorno virtual, instalamos Jupyter:

`
taller_data/$ pip install jupyter
`

7. Ejecutamos Jupyter

`
taller_data/$ ipython notebook
`
Se abrirá un explorador y pinchamos el archivo *Taller_data.ipynb* 


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

