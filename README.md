# promoE-modulo1-proyecto1-equipo4-MonicaNataliaVictoriayCatalina

## Descripción
Este proyecto contiene el código en Python necesario para hacer una transformación digital de una empresa donde nos entregan unos datos sin limpiar para posteriormente tener una base de datos estructurada.


## Integrantes
* Natalia Barquín Urbistondo
* Catalina Tomás Jaume Miquel
* Mónica Serrano Lorenzo
* Victoria Suarez Mascareño

## Motivación para la realización de este proyecto

 Estamos trabajando para una empresa en pleno proceso de transformación digital. Quieren hacer un estudio de los datos que tienen, para ello nos piden que nos creemos unas clases realice una serie de acciones sobre esos datos, pero además que sirvan para otro tipo de datos.

## Estructura de las carpetas 

 El presente repositorio está estructurado de la siguiente manera:

 - README

 - clases_transformacion_digital: fichero jupyter donde se encuentran tres clases: dos de apertura y limpieza de archivos txt y xml, y una clase de operaciones con SQL de creación de tablas e inserción de datos, todo totalmente automatizado.

 - Carpeta datos: en esta carpeta se encuentran todos los datos que el cliente nos ha ofrecido para crear la base de datos.

 - carpeta sprint_review_1: en esta carpeta se encuentra la diapositiva utilizada en el sprint 1 del proyecto.


## Lenguajes utilizados
* Python
* SQL

## Librerias utilizadas
* import re
* import os
* import xml.etree.ElementTree as ET
* import mysql.connector

## Estructuras utilizadas
* Python:
    * Clases
    * Funciones
    * Constructor
    * Rutas relativas
    * Condicionales If
    * Bucles for
    * Apertura y lectura de ficheros
    * Listas
    * Tuplas
    * Diccionarios
    * REGEX
    * Métodos de strings
    * Métodos de listas
    * Métodos de tuplas
    * Métodos de diccionarios
    * Try...except
    * mysql.connector
    * Contol de errores
    * Código defensivo

* SQL:
    * CREATE TABLE
    * CREATE SCHEMA
    * Tipos de datos
    * AUTO_INCREMENT
    * NOT NULL
    * PRIMARY KEY
    * FOREIGN KEY
    * REFERENCES
    * INSERT INTO
    * VALUES

## Parámetros del constructor en Python

Clase Archivo_txt y Archivo_xml:
* 2 parámetros:
    * ruta: la ruta relativa.
    * nombre_archivo: valor predeterminado.

* Clase Operaciones_SQL:
    * valor_password: contraseña del servidor.
    * valor_database: nombre de la base de datos.
    * valor_user = 'root': nombre del usuario, predeterminado como 'root'.
    * valor_host = '127.0.0.1': nombre del host, predeterminado como '127.0.0.1'.