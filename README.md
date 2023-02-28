# tp-final-seminario

Trabajo práctico final de la materia "Seminario Intensivo de Tópicos Avanzados en Datos Complejos", materia de la Maestría en Ciencia de Datos del ITBA. 

Este Trabajo consiste en la creación de un proyecto end to end de datascience utilizando un entorno ya creado de Docker y tecnologías de Big Data como Spark.

Integrantes:
- Manuel Cassiani
- Juan Pablo Casal

## Problema a resolver

Los canales de reserva de hoteles en línea han cambiado radicalmente las posibilidades de reserva y el comportamiento de los clientes. Un número significativo de reservas de hotel se anulan por cancelaciones o por no presentarse. Los motivos típicos de las cancelaciones son cambios de planes, conflictos de horarios, etc. A menudo, esto se ve facilitado por la posibilidad de hacerlo de forma gratuita o, preferiblemente, a bajo coste, lo cual es beneficioso para los clientes del hotel, pero supone un factor menos deseable y que posiblemente disminuya los ingresos con los que tienen que lidiar los hoteles.

El objetivo de este trabajo es armar un modelo que pueda predecir los clientes que van a cancelar su reserva, de manera de que otro cliente pueda aprovechar esa habitación vacía y que no se transforme en una pérdida económica.

dataset utilizado: https://www.kaggle.com/datasets/ahsan81/hotel-reservations-classification-dataset?resource=download

proyecto: jupyter/notebook/hotel_reservations.ipynb

## Contenido del notebook:
* 1 - Importacion dataset y configuracion Schema
* 2 - Primer EDA
* 3 - Valores Nulos y Constantes
* 4 - Ingeniería de atributos
* 5 - Preparación de datos para realizar modelos ML
* 6 - Árbol de decisión
* 7 - Random Forest
* 8 - Postgres

### 1 - Importacion dataset y configuracion Schema

En esta etapa se crea la sesión de spark y se levanta el dataset hotel_reservations.csv
Además se define el esquema de la tabla, columnas de tipo entero, columnas de tipo flotante y columnas del tipo categórico.

### 2 - Primer EDA

En este primer análisis de datos se realizaron los siguientes estudios:

* Mapa de calor (correlación entre variables)

 ![mapa_de_calor](./images/img1.png)

* Distplot
* Countplot


### 3 - Valores Nulos y Constantes
### 4 - Ingeniería de atributos
### 5 - Preparación de datos para realizar modelos ML
### 6 - Árbol de decisión
### 7 - Random Forest
### 8 - Postgres



