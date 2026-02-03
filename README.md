# Práctica 101 - Introducción al Machine Learning y las herramientas de trabajo

Guadalupe Maldonado Ordaz

## Introducción

El desarrollo de esta práctica permitirá elaborar un proyecto introductorio de Machine Learning utilizando Python y GitHub. En este contexto, GitHub funciona como una plataforma de control de versiones y alojamiento de repositorios, donde es posible almacenar el código y los archivos del proyecto, registrar los cambios realizados a lo largo del tiempo y mantener un historial claro de su evolución. Este proyecto servirá como base para las prácticas futuras del curso y facilitará la comprensión del flujo de trabajo con el que se gestionan proyectos profesionales de Machine Learning, incluyendo organización del código, documentación y seguimiento de avances.

La práctica consiste en desarrollar un proyecto sencillo que funcione como portafolio, con el objetivo de demostrar de manera clara y ordenada el dominio básico de GitHub (creación del repositorio y documentación), el uso correcto de ambientes virtuales en Python para gestionar librerías que el proyecto necesite, y la visualización de datos mediante herramientas como Pandas y Seaborn, integrando un análisis exploratorio básico y gráficos representativos que faciliten la interpretación de la información.

## Resultados 
Para el desarrollo de esta práctica se realizaron los siguientes pasos.
Paso 1: Creación de cuenta y de un repositorio en Github.
En este paso fue necesario crear una cuenta de Github, posteriormente se creo un repositorio público el cual se le nombro p101, se descargó Github Desktop y después se clono el repositorio en el escritorio.
Paso 2: Repositorio en Visual Code.
Abrimos el repositorio clonado en Visual Code. Ahí creamos un archivo llamado .gitignore y agregamos la de texto ml-env/ que ignorará el entorno virtual y no se suba al repositorio.
Después se editó el archivo README.md para crear la portada del repositorio. 
Paso 3: Abrir la terminal integrada
Se abre la terminal integrada con CTRL + J, dentro de la terminal se creo un entorno virtual llamado ml-env, después se activo el entorno virtual. 
Paso 4: Instalar los paquetes panda y seaborn
Se instalan los paquetes y luego se congelaron los requerimientos.
Paso 5: Crear una libreta de Python llamada test
Se creo un archivo test.ipynb para crear la libreta de Python con Jupyter. Se abrió el archivo, se instaló Jupyter. Después se verifico que el Kernel de la libreta de Python sea el entorno virtual. Después en la libreta en una celda de código se escribió 2+2, se ejecuto y mostro como resultado 4.
Paso 6: Crear libreta llamada p101.ipynb
Se creo una libreta con nombre p101.ipynb, después en una celda de código se importaron las librerías de pandas y seaborn. Se descargo los datos del titanic y se coloco junto a las libretas en Visual Code.
Paso 7: Cargar el DataFrame
Se utilizo titanic = pandas.read_csv("titanic.csv") para cargar el DataFrame y después se mostro la información. 
Paso 8: Descripción estadística del titanic.
Se utilizo titanic.describe() para describir las columnas, número de registros, nombre y tipos de datos. 
Después mostramos las primeras 10 filas y las últimas 10 filas de los pasajeros del titanic.
Paso 9: Crear variables x1, y & g
Se crearon las variables x1, y & g siendo las columnas edad, tarifa y sexo respectivamente.
Paso 10: Grafica los puntos x1 y y usando Seaborn
Usando seaborn.scatterplot(x=x1, y=y) se grafico la edad con respecto a la tarifa.
Paso 11: Grafica los puntos x1 y y segmentados por g usando Seaborn
Usando seaborn.scatterplot(x=x1, y=y, hue=g) se grafico la edad con respecto a la tarifa segmentado por el sexo.

