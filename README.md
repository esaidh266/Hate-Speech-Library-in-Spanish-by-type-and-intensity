# Hate-Speech-Library-in-Spanish-by-type-and-intensity
Hate libraries according to intensity and types in digital news media in Spain, the result of the "Hatemedia" project (project PID2020-114584GB-I00), financed by MCIN/ AEI /10.13039/501100011033.

The database used to train the classification algorithm models developed in the Hatemedia project identified 6,273 simple and compound lemmas associated with messages with hate expressions identified by each of the intensities and types of hate studied in this project. The hate libraries by intensity and type of hate consist of 2,706 and 3,567 simple and compound words, respectively.

By intensity of hate:
-	Intensity 1 – Hate associated with uncivil messages: 1,000 simple and compound lemmas.
-	Intensity 2 – Hatred associated with poorly intended messages or abusive expressions: 364 simple and compound lemmas.
-	Intensity 3 – hatred associated with insults: 1,110 simple and compound lemmas.
-	Intensity 4 – Hatred associated with veiled or explicit threats: 232 simple and compound lemmas.
  
By type of hate:
-	General hatred: 1,001 simple and compound lemmas.
-	Misogynistic hate: 505 simple and compound lemmas.
-	Political hatred: 1,235 simple and compound lemmas.
-	Sexual hatred: 160 simple and compound lemmas.
-	Xenophobic hatred: 666 simple and compound lemmas.
  
Once these lemmas were collected, the following process was carried out:
-	LABELING OF EXPRESSIONS AND EXTRACTION OF LEMMAS. Stop-words were eliminated from the total number of identified messages, and anomalous data were identified (that did not belong to a known language or were diminutives of it). Subsequently, they were separated based on their intensity and type of hatred. This separation identified simple and independently composed words for each intensity and type of hatred.
-	IDENTIFICATION OF DUPLICATES: In the first phase, two lists were made, the first of simple lemmas and the second of compound lemmas. The first step was to filter these two lists to identify repeated lemmas, obtaining these two libraries where each lemma appears only once.
-	BBDD INTEGRATION: Next, in the third phase, both libraries were joined to build a final library that integrated all the lemmas, both simple and compound. Finally, a final filtering was performed to ensure the lemmas were not repeated.
Once the described process was completed, each of the identified lemmas was manually reviewed to eliminate those that did not refer to expressions of hate due to the context or meaning of the term. Finally, the following list of lemmas was left according to intensity and type of hate. The hate libraries by intensity and type of hate consist of 1,140 and 1,673 simple and compound lemmas, respectively.

By intensity of hate:
-	Intensity 1 – Hate associated with uncivil messages: 401 simple and compound lemmas.
-	Intensity 2 – Hatred associated with poorly intended messages or abusive expressions: 99 simple and compound lemmas.
-	Intensity 3 – hatred associated with insults: 542 simple and compound lemmas.
-	Intensity 4 – Hatred associated with veiled or explicit threats: 98 simple and compound lemmas.
  
By type of hate:
-	General hatred: 463 simple and compound lemmas.
-	Misogynistic hate: 239 simple and compound lemmas.
-	Political hatred: 579 simple and compound lemmas.
-	Sexual hatred: 74 simple and compound lemmas.
-	Xenophobic hatred: 319 simple and compound lemmas.

How to cite: 
- Said-Hung, E., Montero-Diaz, . julio ., Blanco, X., Ruiz-Iniesta, A., Pérez Palau, D., De Gregorio Vicente, O., & José Cubillas, J. (2024). Librerías de odio según intensidad y tipos en medios informativos digitales en España (Hate libraries according to intensity and types in digital news media in Spain) (Version 1). figshare. https://doi.org/10.6084/m9.figshare.26197931.v1

References to recommended documents for review:
- Said-Hung, E., Montero-Diaz, . julio ., Blanco, X., Ruiz-Iniesta, A., Pérez Palau, D., De Gregorio Vicente, O., & José Cubillas, J. (2024). Dataset usado para entrenamientos de modelos de algoritmos de clasificación de odio, por tipos e intensidades (Dataset used to train hate classification algorithm models by types and intensities) (Version 1). figshare. https://doi.org/10.6084/m9.figshare.26085700.v1

- Said-Hung, E., Montero-Diaz, J., Blanco, X., Ruiz-Iniesta, A., Pérez Palau, D., De Gregorio Vicente, O., & José Cubillas, J. (2024). Informe de librerías de odio por intensidad y tipos en medios informativos digitales en España (Report on hate libraries by intensity and types in digital news media in Spain) (Version 1). figshare. https://doi.org/10.6084/m9.figshare.26197934.v1

More info: https://www.hatemedia.es/

---

Librerías de odio según intensidad y tipos en los medios informativos digitales en España, resultado del proyecto "Hatemedia" (proyecto PID2020-114584GB-I00), financiado por MCIN/ AEI /10.13039/501100011033.

A partir de la BD usada para el entrenamiento de los diferentes modelos de algoritmos de clasificación desarrollados en el proyecto Hatemedia, se extranjeron 6.273 lemas simples y compuestos, asociados a los mensajes con expresiones de odio identificados por cada una de las intensidades y tipos de odio estudiados en este proyecto. Las librerías de odio por intensidad y tipo de odio, están conformadas por un total de: 2.706 y 3.567 lemas simples y compuestos, respectivamente.

Por intensidad de odio: 
-	Intensidad 1 – Odio asociado a mensajes incívidos: 1.000 lemas simples y compuestos.
-	Intensidad 2 – Odio asociado a mensajes mal intensionados o con expresiones abusivas: 364 lemas simples y compuestos.
-	Intensidad 3 – odio asociado a insultos: 1.110 lemas simples y compuestos.
-	Intensidad 4 – Odio asociado a amenazas veladas o explícitas: 232 lemas simples y compuestos.

Por tipo de odio: 
-	Odio general: 1.001 lemas simples y compuestos.
-	Odio misogino: 505 lemas simples y compuestos.
-	Odio politico: 1.235 lemas simples y compuestos.
-	Odio sexual: 160 lemas simples y compuestos.
-	Odio xenófobo: 666 lemas simples y compuestos.

Una vez recabado estos lemas, se llevó a cabo el siguiente proceso: 
•	ETIQUETADO DE EXPRESIONES Y EXTRACCIÓN DE LEMAS. Del total de mensajes identificados se eliminaron stop-words, se identificaron datos anómalos (que no pertenecían a un idioma conocido o eran diminutivos de éste), separándolos posteriormente en función de su intensidad y su tipo de odio. A partir de esta separación, se identificaron tanto los lemas simples como compuestos de forma independiente para cada intensidad y tipo de odio.
•	IDENTIFICACIÓN DE DUPLICADOS: En la primera fase se realizaron dos listados, el primero de lemas simples y el segundo de lemas compuestos. El primer paso fue filtrar estas dos listas para identificar lemas repetidos, obteniendo estas dos bibliotecas donde cada lema aparece una sola vez.
•	INTEGRACIÓN BBDD: A continuación, en la tercera fase, se procedió a unir ambas bibliotecas para construir una biblioteca final que integrara todos los lemas, tanto simples como compuestos. Finalmente, se realizó un filtrado final para asegurar que no se repitan los lemas.

Una vez hecho el proceso descrito, se revisó manualmente cada uno de los lemas identificados, con el fin de eliminar aquellos que no aludían a expresiones de odio, por motivo de contexto o significado del término, quedando finalmente la siguiente relación de lemas, según intensidad y tipo de odio. Las librerías de odio por intensidad y tipo de odio, están conformadas por un total de: 1.140 y 1.673 lemas simples y compuestos, respectivamente.

Por intensidad de odio: 
-	Intensidad 1 – Odio asociado a mensajes incívidos: 401 lemas simples y compuestos.
-	Intensidad 2 – Odio asociado a mensajes mal intensionados o con expresiones abusivas: 99 lemas simples y compuestos.
-	Intensidad 3 – odio asociado a insultos: 542 lemas simples y compuestos.
-	Intensidad 4 – Odio asociado a amenazas veladas o explícitas: 98 lemas simples y compuestos.

Por tipo de odio: 
-	Odio general: 463 lemas simples y compuestos.
-	Odio misogino: 239 lemas simples y compuestos.
-	Odio politico: 579 lemas simples y compuestos.
-	Odio sexual: 74 lemas simples y compuestos.
-	Odio xenófobo: 319 lemas simples y compuestos.

Cómo citar: 
- Said-Hung, E., Montero-Diaz, J., Blanco, X., Ruiz-Iniesta, A., Pérez Palau, D., De Gregorio Vicente, O., & José Cubillas, J. (2024). Librerías de odio según intensidad y tipos en medios informativos digitales en España (Hate libraries according to intensity and types in digital news media in Spain) (Version 1). figshare. https://doi.org/10.6084/m9.figshare.26197931.v1

Referencias de documentos recomendados para su revisión:
- Said-Hung, E., Montero-Diaz, . julio ., Blanco, X., Ruiz-Iniesta, A., Pérez Palau, D., De Gregorio Vicente, O., & José Cubillas, J. (2024). Dataset usado para entrenamientos de modelos de algoritmos de clasificación de odio, por tipos e intensidades (Dataset used to train hate classification algorithm models by types and intensities) (Version 1). figshare. https://doi.org/10.6084/m9.figshare.26085700.v1

- Said-Hung, E., Montero-Diaz, . julio ., Blanco, X., Ruiz-Iniesta, A., Pérez Palau, D., De Gregorio Vicente, O., & José Cubillas, J. (2024). Informe de librerías de odio por intensidad y tipos en medios informativos digitales en España (Report on hate libraries by intensity and types in digital news media in Spain) (Version 1). figshare. https://doi.org/10.6084/m9.figshare.26197934.v1

Más información en: https://www.hatemedia.es/





