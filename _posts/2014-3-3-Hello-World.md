


### Filtrado colaborativo
Los primeros sistemas recomendadores aparecen a comienzos de los 90’s (Tapestry, e-mail XEROX). Una de sus principales desvetajas es el problema de cold start (cuando los usuarios tienen muy poca actividad en el sistema) y new item (cuando hay productos en el catálogo que tienen muy pocas interacciones), por lo que se tiene como alternativa el filtrado basado en contenido.

### Modelos Latentes
Representan a los usuarios como vectores, así como también a los ítems, que se pueden representar en el espacio vectorial, y de esta forma para predecir el interés de un usuario con algún ítem, basta con realizar el producto punto entre los vectores.

Existen 10 grandes problemas en los sistemas de recomendación:
#### Filtros Burbuja
Es un problema abierto y complejo cuya interrogativa en su solución sería aumentar la exposición a contenido diverso con los algortimos de recomendación.
#### La inteligencia artificial aún no es inteligente
La tarea de aprendizaje continúa siendo labor del ser humano, y la IA no aprende a distinguir contenido bueno del malo
#### Falta de control y transparencia para el usuario
#### Si las recomendaciones son justas
Lo cual es difícil de regular ya que el sesgo puede provenir del mundo, de la fuente de datos, de los modelos y entrenamiento, de la evaluación del mismo y de la interpretabilidad de los resultados
#### Métricas
Se deben tener en cuenta qué es lo que se está evaluando. Son diferentes en Academia, industria y Utilidad para el usuario, por lo cual alinearlas se encuentra en líneas de investigación.
#### Interactividad y múltiples fuentes de datos
#### Reproducibilidad de los resultados de investigación
#### Conductismo
Los sistemas de recomendación pasaron de los mini algoritmos de factorización matricial a sistemas que impactan la vida de los usuarios
#### Sistemas Recomendadores para audiencias no tradicionales
#### Privacidad en Sistemas Recomendadores

Se define como red un concepto abstracto de cualquier colección de objetos en los cuales alguno de los pares de objetos está conectado, en tanto grafo, es una forma de representar una red. Consiste en un conjunto de objetos llamados nodos con ciertos pares de esos objetos conectados por líneas llamadas enlaces.
Es natural modelar el problema de recomendación como un problema de grafos, es más, existen numerosas bases de datos orientadas a grafos en el mercado (BDOG) como OrientDB, AllegroGraph y Neo4j, entre muchoas otras.
El algoritmo que empezó usando Google para ordenar los resultados de su buscador pertenece a este tipo de aprendizaje mediate grafos, llamado Pagerank y funciona de la siguiente manera:
-	Primero asigna peso o importancia a las páginas web en función de el número de páginas web que apuntan a esta y la importancia de las páginas que apuntan a esta)
-	Luego representa las relaciones existentes entre páginas mediante una matriz
-	Finalmente, utiliza una propiedad de las matrices y calcula el autovector de dicha matriz cuyo autovalor es 1
Este autovector es el que contienen la importancia de las páginas y determina el orden en el que se muestran en cada búsqueda.


