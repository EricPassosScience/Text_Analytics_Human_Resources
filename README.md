# Text Analytics en Recursos Humanos

En este experimento de minería de texto, vamos a determinar cómo califican los empleados a Amazon y Google.

Determinemos qué empresa tiene el mejor equilibrio entre el trabajo y la vida y pague de acuerdo con las reseñas de los empleados recopiladas en el sitio de trabajo Glassdoor.

Usaremos dos conjuntos de datos para varias actividades de minería de texto y análisis de datos (Text Analytics) y al final emitiremos nuestra conclusión. ¿Qué empresa tiene el mejor equilibrio trabajo-vida?

Todos los detalles están dentro del script R.

Se adjuntan ambos archivos.

## Comentarios positivos referentes a Amazon:

![imagem_2023-06-13_225916201](https://github.com/EricPassosScience/Seq2seq_NLP_LanguageTranslator/assets/97414922/27b5357b-8baf-42ba-8eb5-2ef1c6d8a1c6)

## Nube de palabras para reseñas positivas de Amazon:

![imagem_2023-06-13_230203141](https://github.com/EricPassosScience/Seq2seq_NLP_LanguageTranslator/assets/97414922/eea424b5-e40c-4952-81e5-4d545e2284c5)

## Nube de palabras para reseñas negativas de Amazon:

![imagem_2023-06-13_230458721](https://github.com/EricPassosScience/Seq2seq_NLP_LanguageTranslator/assets/97414922/0f925241-1157-48a9-bb51-e00af0731f31)

Parece haber una fuerte indicación de largas horas de trabajo y equilibrio entre el trabajo y la vida en las calificaciones. Como técnica de agrupación simple, realicemos una agrupación jerárquica y creemos un dendrograma para ver cómo se conectan estas calificaciones.

## Dendograma:

![imagem_2023-06-13_230844630](https://github.com/EricPassosScience/Seq2seq_NLP_LanguageTranslator/assets/97414922/b9e99027-4c80-4bf7-a029-15a8c15f4a70)

## Palabras comunes entre las reseñas positivas de Amazon y Google:

![imagem_2023-06-13_231434312](https://github.com/EricPassosScience/Seq2seq_NLP_LanguageTranslator/assets/97414922/5a796ddc-c36b-4b2d-b7bc-9ff7caeb11c2)

Los empleados de Amazon mencionaron el "equilibrio entre el trabajo y la vida" como algo positivo. En ambas organizaciones, la gente mencionó "cultura" y "gente inteligente", por lo que hay algunos aspectos positivos similares entre las dos empresas.

## Palabras comunes entre las reseñas negativas de Amazon y Google:

![imagem_2023-06-13_232018669](https://github.com/EricPassosScience/Seq2seq_NLP_LanguageTranslator/assets/97414922/d81e8cd0-b69b-48dd-8a5a-9640b22c882d)

## Usaremos la nube de elementos comunes para mostrar lo que es común entre Amazon y Google con el tokenizador Unigram, Bigram y Trigram para identificar más información.
## Unigram:

![imagem_2023-06-13_232333151](https://github.com/EricPassosScience/Seq2seq_NLP_LanguageTranslator/assets/97414922/a275e8a9-70e6-428b-baaf-7d1436cbd924)

## Bigram:

![imagem_2023-06-13_232424827](https://github.com/EricPassosScience/Seq2seq_NLP_LanguageTranslator/assets/97414922/4495eb2b-00de-4f25-8d98-2c9bf91ca07a)

## Trigam:

![imagem_2023-06-13_232529425](https://github.com/EricPassosScience/Seq2seq_NLP_LanguageTranslator/assets/97414922/8d365b00-7d16-4d0b-bcd8-7b0221f479e0)

## Palabras más frecuentes en los comentarios de los empleados:

![imagem_2023-06-13_232803541](https://github.com/EricPassosScience/Seq2seq_NLP_LanguageTranslator/assets/97414922/bf72c67d-ee4c-41fa-8063-4c0b8e1bf739)

A partir de ahora, te adelanto que Google tiene el mejor balance.

## Recomendación

Si desea saber más sobre "Corpus" puede acceder al trabajo "***A Construção de wordnets terminológicas com base em corpus***" escrito por Ariani Di Felippo (UFSCar) ariani@ufscar.br

Archivo -> http://www.nilc.icmc.usp.br/nilc/download/ariani/DiFelippo_Ontobras_2010.pdf
