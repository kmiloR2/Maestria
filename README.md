# Maestria
**Analisis de retroalimentaciones a empleados.**

Se cuenta con una muestra de datos dummy de textos de retroalimentación a empleados.

- Sobre la muestra se aplican distintos modelos(Robert, BERT, Afinn) para realizar analisis de sentimientos, extrayendo las polaridades(positiva o negativa).

- El modelo Afinn permite extraer, adicional a las polaridades, los tipo de sentimientos (tristeza, alegria, entre otros). Por otra parte proporciona un sentiment score que 
  devuelve una puntuación numérica que representa la polaridad del sentimiento del texto, donde valores positivos indican sentimientos positivos y valores negativos indican sentimientos negativos, 
  entre mayor sean los valores positivos mayor es la puntuación.

- Para complementar el analisis se utiliza la API de OPEN IA que permite extraer las competencias organizacionales identificadas en cada retroalimentación, 
  esto se hace por medio del desarrollo de un prompt dado un contexto previo donde se definieron las competencias.

  El objetivo último de la combinación de los anteriores modelos es tener una herramienta que permita cuantificar y valorar las retroalimentaciones escritas y puedan ser de valor para una compañia 
  al momento de evaluar a sus empleados.
