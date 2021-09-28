# Identificador-de-medio

  En el marco del curso Laboratorio de Datos dictado en la FCEyN-UBA desarrollamos en conjunto con [Ailen Gomez-Mayol] (https://github.com/mailengm) un proyecto que tome como objeto de estudio los titulares de noticias de los principales medios de información del país. Los mismos fueron utilizados en dos etapas: una de sentiment analysis y detección de tópicos para explorar si los distintos medios presentaban diferencias cuantitativas a la hora de expresar sus titulares; y otra que consistió en entrenar un modelo de machine learning que sea capaz de distinguir de qué medios procedían dichos titulares. 

  Habiendo identificado que cada medio informativo publicita las notas que publica a través de sus redes sociales, utilizamos la API de Twitter para extraer los titulares de las notas que allí postearon en el periodo 27 Jun. ~ 3 Jul.

  La adquisición de los datos, consistentes en varios archivos .json  por cada medio con toda la información que constituye a los tweets, estuvo a cargo de mi compañera. En los presentes notebooks muestro entonces los scripts desarrollados para extraer de los archivos el texto de los tweets, limpiarlos y preprocesarlos; y luego la etapa final del proyecto donde utilizamos los datos para entrenar un clasificador Naive-Bayes que sea capaz identificar la procedencia de nuevos titulares. La etapa anterior sobre sentiment analysis y detección de tópicos también estuvo a cargo de mi compañera, por lo que aparecerán aquí.
