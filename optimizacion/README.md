# **Hackathon: Optimización de ubicación de supermercados con *Machine Learning***

## **Descripción del problema**
----------

En este reto, los participantes se enfrentarán a un problema cuyo objetivo será minimizar el coste de dar servicio a todas las viviendas de una zona mediante de uso de algortimos de Machine Learning.

Los datos suministrados se componen de un ejemplo de resultado para cada problema y una instancia sobre la que se aplicarán los algoritmos para obtener la solución. Estas soluciones muestran tanto el formato del resultado final que se ha de obtener al ejecutar el programa como un ejemplo de una solución válida para el problema.

### **Objetivo**
Desarrollar un algoritmo de **Machine Learning** para la minimización del coste de dar servicio a todas las viviendas.


### **Lectura y guardado de archivo JSON**


El programa debera ser capaz de leer los datos desde el **archivo JSON** proporcionado y guardar la solución en otro **archivo JSON** con la misma estructura que la que se proporciona de ejemplo. 

> Se evaluara la correcta extracción y formato de los respectivos **archivos JSON**


### **Elección de problema** 


Se debe de elegir solo **UNO** de los siguientes problemas:

####  **1. Cobertura Mínima de Hogares con Supermercados de Radio Limitado** 

Dada una cuadrícula de $N\times N$, donde la celda $(i,j)$ de fila $i$ y columna $j$ tiene un coste asociado de construcción $C_{ij}$, y un subconjunto de celdas de la cuadrícula $\mathcal{X}$, que representan una serie de **viviendas que hay que abastecer**, determinar las posiciones en las que hay que **construir supermercados** para poder abastecer a todas las viviendas reduciendo el **coste de construcción total**. Cada supermercado tiene un radio de acción de $M$ celdas en ***distancia Manhattan***.


-   Se evaluará por la creacción y codificación de un programa capaz de obtener soluciones para el problema.
    
-   Se evaluará por:
    
    -   **Obtención de soluciones de alta calidad** tanto para la instancia propuesta como para otras de evaluación.
        
    -   **Eficiencia de ejecución** reduciendo costes temporales necesarios para obtener soluciones. Se valorará la capacidad de optimizar el código.

    - **Versatilidad del algoritmo** para poder adaptarse fácilmente a otros problemas similares.






####  **2. Colocación minimal de hospitales en zonas residenciales** 

Tenemos una cuadrícula de $N\times N$, donde la celda $(i,j)$ de fila $i$ y columna $j$ tiene un coste asociado de construcción $C_{ij}$, y un subconjunto de celdas de la cuadrícula $\mathcal{X}$, que representan una serie de **viviendas**. Debemos determinar las posiciones en las que hay que **construir hospitales** para poder abastecer a todas las viviendas reduciendo el **coste de construcción total** y la **distancia Manhattan total** entre cada vivienda y su hospital asociado con las siguientes restricciones:
 - Cada hospital tiene un radio de acción de $M$ celdas en ***distancia Manhattan***.
 - Cada hospital solo puede atender como máximo a 20 ciudades.


-   Se evaluará por la creacción y codificación de un programa capaz de obtener soluciones para el problema.
    
-   Se evaluará por:
    
    -   **Obtención de soluciones de alta calidad** tanto para la instancia propuesta como para otras de evaluación.
        
    -   **Eficiencia de ejecución** reduciendo costes temporales necesarios para obtener soluciones. Se valorará la capacidad de optimizar el código.

    -   **Versatilidad del algoritmo** para poder adaptarse fácilmente a otros problemas similares.






###  **Evaluación competitiva sobre conjunto de test externo (Ranking Top 5)** 

Los modelos desarrollados serán evaluados sobre un conjunto de test externo con muestras no vistas previamente. Se permitirá realizar una evaluación por hora en la mitad de este conjunto de test. Para ello se proporcionará una forma de hacer la submision de un csv y se recibirá la métrica obtenida.

-   Al final de la competición solo los **5 mejores modelos**, bajo la función de coste asociada a cada problema y la satisfacción de las restricciones, **optarán a ser evaluados para la victoria**.
    


> Se requiere el uso de modelos de modelos **Machine Learning** para ser considerado en el ranking.



###  **Graficado del problema y la solución**

Se valorará el graficado de ambos problemas a partir de los datos proporcionados en el problema tanto para la solución.

-   Se evaluará únicamente que:
    
    -   El correcto graficado del problema.
        
    -   El graficado de los radios de tanto hospitales como supermercados.
                
    




## **Entregables**

-   Código fuente completo, limpio y documentado.
    
-   Script funcional de extracción de datos.
    
-   Script Python Entrenamiento reproducible (jupyter notebook o .py)
        
-   JSON con la solución obtenida.
    



## **Notas Finales**

-   Solo los **5 mejores equipos del ranking de clasificación** podrán ser evaluados en las tareas restantes.
    
-   El enfoque debe ser robusto, reproducible, y adaptado a las restricciones de tiempo de una competición de 24h.
    
-   Al tratarse de dos problemas separados, cada problema tendra su propio ranking.

