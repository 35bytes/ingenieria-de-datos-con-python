<div align="center">
  <h1>Introducción al Pensamiento Computacional con Python</h1>
</div>

<div align="center"> 
  <img src="readme_img/logo.webp" width="15%">
</div>

# Introducción al documento

El contenido de este documento esta basado en el curso del mismo nombre dictado por [David Aroesti](https://github.com/jdaroesti) en [Platzi](https://platzi.com/r/karlbehrens/).

# Tabla de contenido
- [Introducción](#Introducción)
    - [¿Qué es la Ciencia e Ingeniería de Datos?](#¿Qué-es-la-Ciencia-e-Ingeniería-de-Datos?)
    - [Roles](#Roles)
    - [Instalación de Anaconda](#Instalación-de-Anaconda)
    - [Comandos de Anaconda](#Comandos-de-Anaconda)

# Introducción

## ¿Qué es la Ciencia e Ingeniería de Datos?

La **Ciencia de Datos** es la disciplina que se encarga de extraer conocimiento de los datos disponible. Casi siempre cuando te realizas una pregunta sobre datos estas fuentes se encuentran escondidas, ocultas o de difícil acceso. A nuestro alrededor hay datos en tu computadora, mesa, reloj, etc.

**Los datos están por todas partes.**

La Ciencia de datos es multidisciplinaria. A diferencia de muchos otros ámbitos profesionales dentro del mundo de la tecnología cuando hablamos de un científico de datos es una persona que sabe de matemáticas, ingeniería de software y sabe de negocios.

Se apoya en la _Computer science_, Matemáticas (Regresiones e Inferencias), y también se auxilia de:

- Bases de Datos.
- Análisis de texto y procesamiento de lenguaje natural.
- Análisis de redes.
- Visualización de datos.
- Machine learning e Inteligencia Artificial.
- Análisis de señales digitales.
- Análisis de datos en la nube (Big Data).

## Roles

Existen por lo menos tres diferentes roles para tener un _pipeline_ completo de ciencia de datos. Este curso trata sobre el primer rol:

- **Data engineer:** Se encarga de obtener los datos, limpiarlos y estructurarlos para posterior análisis, crear _pipelines_ de análisis automatizado, utilización de herramientas en la nube, análisis descriptivo de los datos.

- **Data scientist:** Una vez tiene los datos se encarga de generar el análisis matemático de ellos, encontrar las relaciones entre las variables, las correlaciones, las causas y por último genera los modelos predictivos y prescriptivos.

- **Machine Learning engineer:** Se encarga de llevar las predicciones a escala, de subirlos a la nube y allí generar muchas predicciones. Se encarga de mantener la calidad del modelo.

## Instalación de Anaconda

Para esta guía haremos uso de [Anaconda](https://www.anaconda.com/), la cual es una instalación de Python que ya trae preinstalado todos los paquetes necesarios para tu labor en la Ciencia de Datos, tiene más de **1400 paquetes**. Nos permite configurar ambientes virtuales para poder utilizar diferentes versiones de nuestros paquetes. Procura instalar [Anaconda](https://www.anaconda.com/) en tu computadora.

## Comandos de Anaconda

### Versión de Anaconda

Luego de haber instalado [Anaconda](https://www.anaconda.com/) en nuestra máquina, abriremos la terminal y veremos que anaconda este instalado ejecutando el comando:

```
conda --version
```

Y veremos la versión de [Anaconda](https://www.anaconda.com/) que tenemos instalado.

<div align="center"> 
  <img src="readme_img/conda-version.png" width="80%">
</div>

### Desactivar ambiente de Anaconda

Si lograste observar bien nuestra terminal esta inicia con un **ambiente de anaconda** de forma **predeterminada.** Si la queremos **desactivar** lo haremos con el siguiente comando.

```
conda deactivate
```

<div align="center"> 
  <img src="readme_img/conda-deactivate.png" width="80%">
</div>

### Activar ambiente de Anaconda

Para volver **activar** el ambiente ejecutamos.

```
conda activate
```

<div align="center"> 
  <img src="readme_img/conda-activate.png" width="80%">
</div>

### Comandos de Conda

Para listar los **comandos** de conda utilizaremos:

```
conda --help
```

<div align="center"> 
  <img src="readme_img/conda-help.png" width="80%">
</div>

### Listar paquetes instalados

Podemos listar todos los **paquetes instalados** en nuestra computadora.

```
conda list
```

<div align="center"> 
  <img src="readme_img/conda-list.png" width="80%">
</div>

### Crear ambientes virtuales

Es una buena práctica crear un ambiente virtual para cada proyecto. Para ello Anaconda ya cuenta con un comando para crear ambientes.

```
conda create --name nombre_ambiente libreria_1 libreria_2 libreria_n
```

<div align="center"> 
  <img src="readme_img/conda-crear-ambiente.png" width="80%">
</div>

<div align="center"> 
  <img src="readme_img/conda-crear-ambiente-terminado.png" width="80%">
</div>

### Activar ambientes virtuales

Luego de crear el **ambiente virtual** para nuestro proyecto, lo podemos **activar** haciendo referencia a su nombre.

```
conda activate nombre_ambiente
```

<div align="center"> 
  <img src="readme_img/conda-activate-ambiente.png" width="80%">
</div>

### Desactivar ambientes virtuales

Para **desactivar** ambiente virtual ejecutamos el siguiente comando.

```
conda deactivate
```

<div align="center"> 
  <img src="readme_img/conda-deactivate-ambiente.png" width="80%">
</div>

### Listar ambiente virtuales

Si queremos **listar** todos los ambientes virtuales creados en nuestra computadora.

```
conda env list
```

<div align="center"> 
  <img src="readme_img/conda-env-list.png" width="80%">
</div>

### Eliminar ambiente virtual

Si deseamos **eliminar** un ambiente con todos sus paquetes ejecutamos el siguiente comando.

```
conda remove --name nombre_ambiente --all
```