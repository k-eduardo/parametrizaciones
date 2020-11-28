# parametrizaciones
Visualización en Julia para visualización de curvas y superficies.

## Windows

1. Instalen Conda [liga aquí.](https://www.anaconda.com/products/individual#Downloads)
1. Sigan las instrucciones de [este video.](https://www.youtube.com/watch?v=dycl0bntMwo) (Gracias Mario por la referencia.)
1. Agregar el kernel de Julia
    Abrir Julia y poner:
    
    `using Pkg`
    
    `Pkg.add("IJulia")`
1. Clonar el proyecto (pueden no usar git para esto porque para algunos fue complicado).
![Alt text](https://github.com/ocampo/parametrizaciones/blob/main/imagenes/1.png?raw=true "Clonar el proyecto.")
![Alt text](https://github.com/ocampo/parametrizaciones/blob/main/imagenes/2.png?raw=true "Clonar el proyecto.")

1. Buscar en las carpetas el programa.
![Alt text](https://github.com/ocampo/parametrizaciones/blob/main/imagenes/3.png?raw=true "Clonar el proyecto.")
1. Darle play.

## Mac y Linux
Jupyter es un ambiente de programación bastante útil porque nos permite hacer muchas cosas simultáneamente:
1. Escribir código.
1. Documentarlo.
1. Observar los resultados del código.
1. Redactar anotaciones y observaciones del projecto, pudiendo adjuntar imágenes y eso...

### Para instalar Jupyter(Lab):

Revisen si tienen instalado python 3 en una versión superior a 3.4, si no lo tienen; [instálenlo](https://www.python.org/downloads/). A continuación el detalle de esta instrucción por si es requerido.

#### En Mac
Abran el programa _Terminal_ y escriban __python__. Si aparece la versión y cambia la consola, adelante. (Es muuuy probable que esté instalado y bien configuradas las ligas simbólicas, de lo contrario, en la página de python pueden descargar de nuevo el intérprete.)
#### En Linux
Seguro tienen ya python :), sólo hagan un update de sus respositorios y verifiquen que tengan python3, de lo contrario, un apt-get, yum o parecido para python3 servirá.

Termina el detalle.

#### Instalar Jupyter(lab):
`pip install jupyterlab`

### Agregar el kernel de Julia
Abrir Julia y poner:

`using Pkg`

`Pkg.add("IJulia")`

## Obtener los programas del curso
Chequen el clonado de la sección de Windows y el resto de las instrucciones.



## Opcional: Instalación de Git
#### Linux
En la terminal, escribir:

`sudo apt install git-all` Ubuntu-s
`sudo yum install git-all` Debian-s
`sudo dnf install git-all` Fedora-s

#### Windows y MacOs
Instalar [GitHub Desktop](https://desktop.github.com)
