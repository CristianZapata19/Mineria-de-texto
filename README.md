## Descripción del trabajo

Este proyecto realiza un análisis de minería de texto sobre dos artículos en español relacionados con el cambio climático.  
El primero, titulado *“Efectos del cambio climático en materias primas”*, examina las implicaciones económicas y productivas del fenómeno climático sobre sectores clave.  
El segundo, *“Récords climáticos en 2023”*, recopila datos y eventos meteorológicos extremos ocurridos a nivel mundial durante ese año.

A lo largo del trabajo, se aplicaron técnicas de **procesamiento de lenguaje natural (NLP)** utilizando Python y la biblioteca *spaCy*, que permitieron extraer, limpiar y analizar el contenido textual de forma estructurada.

## Metodología aplicada

1. **Carga y normalización** de los textos para eliminar etiquetas, URLs, emojis y puntuación innecesaria.  
2. **Tokenización, remoción de stopwords y lematización**, con el fin de obtener las palabras base más representativas de cada texto.  
3. **Cálculo de frecuencias y generación de nubes de palabras** para visualizar los términos más dominantes.  
4. **Etiquetado gramatical (POS tagging)** para identificar los sustantivos, verbos y adjetivos más utilizados.  
5. **Extracción de tripletas Sujeto–Verbo–Objeto (SVO)**, lo que permitió reconocer relaciones y patrones discursivos relevantes.  

## Principales hallazgos

- En el **Texto 1 (Materias Primas)** predominan términos como *riesgo, producción, empresa* y *cambio*, lo que refleja una narrativa **económica y preventiva**, centrada en cómo el cambio climático altera la estabilidad de los mercados y la productividad.  
- En el **Texto 2 (Récords Climáticos 2023)** se destacan palabras como *temperatura, nivel, mar* y *hielo*, mostrando un discurso **científico y descriptivo**, enfocado en los datos empíricos y los eventos extremos.  
- Los patrones gramaticales evidencian que el primer texto enfatiza la acción humana (*empresa enfrenta riesgo*), mientras que el segundo resalta fenómenos naturales (*mar eleva nivel*, *temperatura alcanza récord*).  

## Conclusión

El análisis demuestra que la minería de texto es una herramienta poderosa para **entender el enfoque y la intención de los discursos**, incluso cuando abordan un mismo tema.  
Mientras uno comunica la preocupación económica, el otro retrata la magnitud física del cambio climático. En conjunto, ambos textos permiten apreciar la **interconexión entre economía y medio ambiente**, mostrando que el cambio climático no solo transforma ecosistemas, sino también decisiones productivas y políticas globales.
