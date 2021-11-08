# VIU_TFM_fakenews_timeline
Trabajo fin de Master IA Universidad Internacional de Valencia


Resumen

Castellano:

En este Trabajo de Fin de Master, se pretende alcanzar el origen de una noticia falsa en Twitter, partiendo del mensaje (tweet objetivo) más reciente en esta red social que contenga dicha noticia falsa, para llegar al tweet que dio origen a la expansión de esta noticia falsa en la red social. Para ello se utilizarán las últimas herramientas de inteligencia artificial basadas en el procesamiento del lenguaje natural (PLN), como Transformers BERT y análisis de sentimientos. 
A pesar de las trabas impuestas por el API de Twitter, los resultados alcanzados han sido los de poder trazar una línea temporal que va desde el tweet actual con la noticia falsa, hasta el primer tweet de la red social que la contenía, basando dicha línea temporal en la distancia semántica y el sentimiento predominante de cada mensaje.

Palabras clave: Procesamiento del Lenguaje Natural, Transformers, BERT, Análisis de Sentimientos


Inglés:

In this Master's Thesis, the aim is to reach the origin of fake news on Twitter, starting from the most recent message (target tweet) in this social network that contains said false news, to reach the tweet that gave rise to the spread of this fake news on this social network. For this, the latest artificial intelligence tools based on natural language processing (NLP), such as Transformers BERT and sentiment analysis, will be used. 
Despite the obstacles imposed by the Twitter API, the results achieved have been to be able to draw a timeline that goes from the current tweet with the fake news, to the first tweet of the social network that contained it, basing that temporal line in the semantic distance and the predominant sentiment of each message. 
Keywords: Natural Language Processing, Transformers, BERT, Sentiment Analysis



Introducción

En una sociedad híper-conectada, donde cada día más, la gente se informa a través de las redes sociales, dejando de lado otros medios de comunicación y sobretodo, dejando de lado la maniobra más que necesario de contrastar una determinada noticia a través de otras fuentes, combatir la lacra tecnológica de las noticias falsas en las redes sociales, se hace cada día más necesario. Detectarlas es el primer paso, pero dada la creciente cantidad de éstas, conocer su origen, y por lo tanto su motivación, se presenta como un segundo paso más que necesario.
En este trabajo de fin de máster para la Universidad Internacional de Valencia, vamos a intentar llegar al origen de una noticia falsa en la red social Twitter, partiendo del tweet más actual que contenga dicha falsedad, eso sí, siempre intentando superar todas las barreras que dicha red social impone para poder realizar este tipo de tareas sobre los datos generados por sus usuarios, en principio con la buena intención de evitar otros propósitos no tan encomiables como el nuestro, dada la información que se puede llegar a recopilar de la misma.


Objetivos

El objetivo unívoco es localizar el origen de la noticia falsa en la red social Twitter, para ello habrá de pasar por  objetivos parciales, como:
1.	Recopilar la información usando el API de Twitter.
2.	Pre-procesamiento de los Tweets y su información, incluido el texto, para lograr comprender la información y alcanzar mayor eficiencia a la hora de usar los modelos.
3.	Analizar y comprender las herramientas de proceso del lenguaje natural adecuadas para el problema.
4.	Calcular la distancia semántica entre el tweet objetivo y el resto de tweets almacenados.
5.	Calcular el sentimiento predominante de cada mensaje y establecer una relación entre el tweet objetivo y el resto de mensajes para intentar calcular la motivación.
6.	Trazar una línea temporal de mensajes desde el tweet objetivo hasta el posible origen de la noticia falsa en Twitter.
