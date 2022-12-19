# Clase 8 - Interactive and Conversational Recommender Systems

Entre los sistemas de recomendación, tenemos el basado en críticas, donde la recomendación se inicia con una propuesta inicial que es refinada a través de críticas (o interacción) del usuario (por ejemplo el sitio Dell permite subir o bajar los features, dependiendo de su presupuesto, para tener mayor control sobre la recomendación). 

Un sistema conversacional es un sistema recomendador que da sugerencias personalizadas a través de diálogos en lenguaje natural (escrito o hablado) con un sistema. Los cuales permiten al usuario interactuar con máquinas para obtener cierta información, conducir transacciones o desarrollar algunas otras tareas orientadas a la solución de un problema determinado.

Estos sistemas tienen 2 modalidades, lo que se refiere a cuantos recursos tienen el usuario y el sistema para comunicarse entre ellos, los cuales pueden ser unimodales o multimodales:

#### Sistemas unimodales
En un sistema conversacional la computadora es capaz de entender la entrada hablada de la persona y generar una salida hablada para el usuario. Estos sistemas son sistemas de entrada – salida unimodales, es decir, utilizan información representada como habla y nada más en su comunicación con el usuario.

#### Sistemas multimodales
La interacción multimodal se define como la existencia de múltiples vías de interacción sobre un sistema, permitiendo que un usuario utilice distintas herramientas de entrada y salida de información. Es por ello que un sistema multimodal es el que permite que los usuarios interactúen por varios canales (audio, video, texto), y no únicamente por un único canal, para realizar una tarea concreta.

Es importante diferenciar una IA Conversacional vs Chatbots, Las aplicaciones de IA conversacional se pueden programar con diferentes niveles de complejidad, lo que da como resultado productos finales radicalmente diferentes, que se pueden usar como asistentes personales, para facilitar las conversaciones entre clientes y empresas, y dentro de las empresas para automatizar operaciones.

El uso de técnicas aprendizaje reforzado y Deep learning han permitido que estos sistemas conversacionales sean usables por usuarios finales (tales como Alexa o Siri) y sirven para extraer de manera dinámica más feedback el usuarios y patrones de uso, lo que conlleva a más datos que permiten mejoras más aún estos modelos conversacionales.

Un sistema recomendador conversacional tiene como entreda las últimas N interacciones con el sistema, así como también de forma opcional, las preferencias del usuario e información adicional de ítems; y como salida, la próxima respuesta del sistema, así como también los ítems recomendados para el usuario (de forma opcional, una explicación).

Un ejemplo de esto es el Chat GPT, desarrollado por OpenAI, diseñado específicamente para su uso en chatbots y otras aplicaciones de IA conversacionales donde puede generar respuestas similares a las humanas. Utiliza una arquitectura de Transformers, tiene una capacidad para aprender de grandes cantidades de datos y capacidad para adaptarse a diferentes contextos y situaciones:

#### Transformer Architecture
Se adapta especialmente bien a las tareas de procesamiento de lenguaje natural como la traducción de idiomas y la generación de texto, como consecuencia de su capacidad para procesar de manera eficiente largas secuencias de datos. Consta de capas de autoatención que permiten que el modelo sopese la importancia de diferentes palabras o frases en cada entrada, lo que permite que el modelo comprenda mejor el contexto y el significado de la entrada de modo que genere respuestas más coherentes. Además de las capas de autoatención, incluye capas feed-forward y conexiones residuales, lo que permite que el modelo capture mejor las relaciones entre diferentes palabras o frases.

#### Pre-entrenamiento a gran escala
Chat GPT tiene la capacidad para aprender de grandes cantidades de datos. Está previamente entrenado en un conjunto de datos masivo de texto, lo cual permite comprender los patrones y la estructura del lenguaje natural.

#### Casos de uso:
-	Creción de chatbots para conversar con los usuarios
-	Traducción de idiomas
-	Resumen de texto
-	Creación de contenido

#### Limitaciones
-	Dependencia de un gran conjunto de datos de texto para el enrenamiento
-	Dependencia de los algoritmos de aprendizaje automático, es decir, si los datos de entrenamiento están sesgados o contienen errores, Chat GPT puede reproducir esos sesgos o errores en sus respuestas
-	Complejidad y demandas computacionales

