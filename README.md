# Laboratorio 6: ETL - P1
Este proyecto consiste en la creación de un programa que procesa información contenida en un archivo de datos, filtra las filas que contienen valores nulos en cierta columna, y guarda los datos restantes en un archivo XML dentro de una carpeta específica.

## Objetivo
El objetivo de esta práctica es familiarizarse con la lectura, procesamiento y almacenamiento de datos mediante un enfoque estructurado. La práctica permite reforzar el uso de estructuras de datos en memoria y la manipulación de archivos en distintos formatos. Además este ejercicio sirve para ilustrar el inicio del proceso ETL.

## Descripción
El ejercicio fue realizado utilizando un notebook con kernel de Python, el cuál resulta útil para documentar con precisión cada porción del código al mismo tiempo que proporciona la capacidad de desarrollar las ideas clave mediante el uso de Markdown.

### Procesamiento de la información:

Las filas en las que el valor de la columna state está vacío (o es null) son eliminadas y los datos restantes se mantienen en memoria para su posterior procesamiento y almacenamiento en un archivo XML
