# Hackathon ITCL - Universidad de Burgos: Clasificación de la dificultad de ejercicios de navegación.

## Introducción

En este desafío, se busca desarrollar un algoritmo capaz de **clasificar automáticamente la dificultad global** de ejercicios de navegación marítima, basándose en situaciones vividas por un **Barco Principal** al encontrarse con otros barcos, denominados **Barcos Contacto**.


## Descripción de la Competición

Cada ejercicio de navegación está compuesto por **varias situaciones** en las que el Barco Principal se cruza o interactúa con distintos tipos de Barcos Contacto. Estas situaciones deben clasificarse según su **nivel de dificultad** en tres categorías:
- **Alta**
- **Media**
- **Baja**

Una vez evaluadas todas las situaciones de un ejercicio, se asigna una **dificultad global al ejercicio completo**, también clasificada como: Alta, Media o Baja.


## Datos disponibles
Se proporciona un conjunto de **100 ejercicios ya clasificados**, con:
- Las **situaciones individuales** vividas en cada ejercicio.
- El tipo de **Barco Contacto** involucrado en cada situación (puede ser *velero*, *pesquero* o *motor*).
- La **clasificación de dificultad** de cada situación.
- La **clasificación global del ejercicio**.

## Objetivo
A partir de los 100 ejercicios clasifcados, se debe construir un método capaz de **clasificar automáticamente la dificultad global** de **50 ejercicios** para la evaluación, basándose en las dificultades de cada una de las situaciones individuales que los componen.


## Ponderación de cada uno de los apartados.

### 1. Evaluación de situaciones individuales

Se evaluará cada situación clasificada correctamente (*Alta*, *Media*, *Baja*).

### 2. Evaluación de la dificultad global del ejercicio

Se evaluará cada ejercicio cuya dificultad global sea correctamente predicha.

## Resumen de Puntuación Total

Tarea

1. Evaluación situaciones individuales
2. Evaluación global del ejercicio

## Entregables

- Código fuente completo, limpio y documentado con todos los pasos que se han realizado para la clasificación.
- Un **único archivo CSV** que contenga la clasificación de los **50 ejercicios**. Debe tener la misma estructura que los ficheros de ejemplo proporcionados.


