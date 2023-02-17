# Analisis-de-Sueldos-con-Phyton-SysArmy2021

## ¿Qué son las encuestas de SysArmy?
Las encuestas de Sysarmy son realizadas a la comunidad del sector IT de Latinoarmérica y con sus variadas preguntas permiten generar una idea del estado de esa industria en el momento.

## ¿En qué consistió este proyecto?

El proyecto consiste en responder preguntas sobre los resultados obtenidos, pero para esto primero se debe procesar y manipular los datos.

En este proyecto no se utilizó Pandas, una potente herramienta que permite facilitar el trabajo en análisis de Datos, por lo que se requirió demostrar una capacidad de entendimiento de los conceptos más básicos de Phyton para lograr procesar y analizar la información.

Las encuestas correspondientes a Argentina se encuentran separadas en un Archivo csv distinto, por lo que se debió realizar ¨diccionarios¨ para luego unir toda la información en un solo lugar.

La manipulación de los datos llevó un 80% del tiempo invertido, ya que la mayoría de las categorías requerían algún cambio en sus campos para que su análisis fuera de buena calidad, un ejemplo es el sueldo recibido estando en moneda local para cada uno de los encuestados.

Despúes de esto se realizaron comparaciones entre las distintas respuestas, y se armaron diccionarios separados para obtener más información interesante sobre los encuestados.


### En el archivo trabajado se responden una variedad de preguntas, pero estas son las principales concluciones:

## Concluciones en base a los resultados obtenidos:

Una importante cantidad de encuestados respondió las preguntas en broma o de una manera no esperada, por lo que en algunos casos la calidad de la información se vió afectada.

La información enseñada sobre los salarios es la mediana, un estadístico de posición central que parte la distribución en dos, es decir, deja la misma cantidad de valores a un lado que a otro. En este caso, utilizar la mediana será de gran ayuda para poder tener una idea del salario de una persona en promedio ganaría en su posición, género, etc. Debido a que la mediana se ve menos afectada antes elementos muy extremos como sucedió en ocaciones en este estudio.

### Rol y sueldos:

Según la información analizada, los roles mejor remunerados, tienden a pertenecer al sector de la seguridad, como Product Security cuya mediana es, USD 4026 . Entre roles bien remunerados se encuentra el sector de análisis de información y Research al sector de analisis de información , como Research Engineer cuya mediana es USD 13202. Roles que implican responsabilidad y liderazgo, tambíen se encuentran entre los mejor remunerados, como es el caso de Director de DevOps con una mediana de USD15336.

Los roles que se centran en el manejo de Data como DBA-Developer, o roles que requieren una gran experiencia y estuido son favorecidos, también lo son, roles que mezclan las categorias mencionadas anteriormente, con Security Analist siendo el de mayor remuneración reportada, con USD 96127.

En la industria, los roles menor remunerados, parecen ser roles para empleados menos experimentados o de actividades que no implican el uso de la programación, como chef o asistente.

Roles que son menos pagados, también suelen ser funciones que no se pueden realizar facilmente de manera remota. En el análisis de contratos y sueldos, se comprobó que las personas que desempeñaban tareas de manera remota, para empresas extrangeras tenían un salario mayor. Por lo que tener una tarea que no se pueda realizar de manera remota podría implicar potencialmente un menor salario.

![image](https://user-images.githubusercontent.com/74270973/219704178-eafc282c-b402-4991-89a3-2199ba2ed015.png)

En la industria, los roles menos remunerados, parecen ser roles para empleados menos experimentados o de actividades que no implican el uso de la programación, como chef o asistente.

## El Nivel de educación alcanzada y su impacto en sueldos:

En este estudio, nivel primario figura con la mayor mediana de salario, debido a que una sola persona estudió solamente hasta primario, no se podrían sacar concluciones con respecto a este resultado.

La variación de resultados en este caso, no es mucha, por lo que se puede concluir que esta industria favorece el conocimiento y experiencia que se tiene sobre el área y no tanto los diplomas que la persona tenga.

Aún así, juntando la información obtenida en el análisis de roles, tener estudios universitarios, podría implicar un mayor salario.

Sorprendentemente, el nivel con menor mediana salarial es Posdoctorado con USD 1540, lo que se podría deber a el pequeño porcentaje de personas que realizaron posdoctorado en la encuesta, o a que el posdoctorado realizado, sea en un área distinta a la programación.

![image](https://user-images.githubusercontent.com/74270973/219704816-bdac242f-ff7a-457e-85fb-826d42a7c7b3.png)


## Género y sueldos:

Debido a que las respuestas alternativas de género a Varón Cis y Mujer Cis, fueron en su mayoría, respuestas negativas o en broma, no se puede realizar concluciones sobre el campo ¨otros¨ debido a que la calidad de la información se vió afectada.

Según el estudio realizado en este caso, las mujeres ganan aproximadamente 20% menos que los hombres.

![image](https://user-images.githubusercontent.com/74270973/219705065-7d435fb6-a74a-4b02-a27c-327c6f839e0c.png)

También son minoría en esta industria, representando solamente un 16.45% del total.

En los análisis anteriores, se comprobó que el rol desempeñado tiene un gran impacto en el salario obtenido, como las mujeres son minoría, es posible que se les otorgue una menor oportunidad de alcanzar esos roles mejor pagados, que requieren confianza del empleador.

Por lo que según los datos obtenidos, es probable que en esta industria exista una frecuente discriminación hacia las mujeres y otros géneros distintos de hombre, pero para determinarlo se necesesitaría más información.

Para más información: https://en.wikipedia.org/wiki/Gender_pay_gap#:~:text=The%20most%20significant%20factors%20associated,and%20in%20fields%20like%20STEM).

