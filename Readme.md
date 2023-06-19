# Procesamiento de lenguaje natural

Los trabajos prácticos descritos a continuación se realizacon en la carrera de especilización de inteligencia artificial de la Facultad de Ingenieria de la Universidad de Buenos Aires (FIUBA)


## Clase 1

En el primera trabajo se implementarion funciones para obtener el vocabulario del corpus y poder realizar una representación del mismo. Se usaron técnicas de representación como  es OneHOtEncoding y vectores de frecuencia y con esto poder obtener una matriz TF_IDF.

Se implementarion funciones que nos ayudan a comarar textos usando la similaridad coseno de sus representaciones.

[Notebook](https://github.com/poldrosky/nlp_ceia/blob/main/clase_1/1a%20-%20word2vec.ipynb)


## Clase 2

En este trabajo se realizo la implementación de un bot. Se realizó dos ejemplos uno tomando un texto de wikipedia y otro tomando com lógica de negocio la mensajería de un e-commerce.

Para la contrucción de los ejemplos se realizaron tareas de preprocesamiento de texto como son: eliminar caracteres especiales, acentos, cifras numéricas, caracteres de puntuación, también se obtuvo la lematización de cada token del corpus, se eliminaron stopwords.

En los notebooks se puede ver tanto el entrenamiento como los ejemplos del bot.

[Notebook QA](https://github.com/poldrosky/nlp_ceia/blob/main/clase_2/2b%20-%20bot_dnn_spacy_esp_modified.ipynb)

[Notebook document wikipedia](https://github.com/poldrosky/nlp_ceia/blob/main/clase_2/2c%20-%20bot_tfidf_nltk_modified.ipynb)

## Clase 3

El objetivo es utilizar documentos / corpus para crear embeddings de palabras basado en ese contexto, para la realización de este problema se tomo como entrada de texto los libros del Señor de los anillos, se realizo un preprocesamiento de texto, luego se crearon los vectores de palabras usando word2vec.

Luego se evaluamos los resultados para ver las 10 palabras más cercanas y visualizamos la agrupación de vectores.


[Notebook](https://github.com/poldrosky/nlp_ceia/blob/main/clase_3/3b%20-%20Custom%20embedding%20con%20Gensim.ipynb)


## Clase 4

En este problema se busca poder predecir la próxima palabra. Para lo que se usaron tambien los textos de los tres libros del Señor de los anillos, se realizo el preprocesamiento del texto y luego se organizo el input y target de modo que con las 3 ultimas palabras se haga la predicción de la siguiente. y luego se realizó la contrucción y entrenamiento del modelo.

Se realizó una funcion de prueba para la predicción de la próxima palabra asi como para generar secuencias nuevas.

[Notebook](https://github.com/poldrosky/nlp_ceia/blob/main/clase_4/tensorflow/4d%20-%20predicci%C3%B3n_palabra-mod.ipynb)

## Clase 5

En este problema se realizó un ejemplo de análisis de sentimiento utilizando Embeddings + LSTM para clasificar las criticas de compradores de ropa. Para este problema se realizaron tareas de limpieza de datos. Se entrenaron 2 modelos 1 con 5 categorias y otro con 3 categorias


[Notebook](https://github.com/poldrosky/nlp_ceia/blob/main/clase_5/5%20-%20clothing_ecommerce_reviews.ipynb)

## Clase 6

Se realizo un BOT utilizando LSTM, para este problema usamos un modelo encoder-decoder. Para este problema realizamos tareas de preprocesamiento de texto, preparación de embedings utilizando los embedings de GLOVE, luego entrenamos el modelo y realizamos la evaluación con algunas inferencias. 


[Notebook](https://github.com/poldrosky/nlp_ceia/blob/main/clase_6/6-%20bot_qa.ipynb)

