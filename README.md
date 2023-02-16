![HenryLogo](https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png)
​
# Proyecto Integrador
​
¡Bienvenidos a nuestro proyecto integrador! Durante estos días estarán poniendo en práctica sus habilidades en el campo de la predicción de datos. Deberán explorar bien los datos, entender la problemática, para luego experimentar con nuestros modelos de machine learning, usando las métricas correspondientes para medir la performance del/los modelo/s la cual, a su vez, será usada para elegir los mejores modelos.
​
## Mercado automotor
​​
El mercado automotor esta muy ligado a la cultura de cada país, según los gustos de cada uno, el mercado norteamericano, por ejemplo, valora mucho los motores y vehículos muy grandes, el mercado europeo prefiere el bajo consumo, el mercado latinoamericano, los precios bajos y asi varía según región, país y cultura. Un mismo vehículo puede tener un valor muy distinto de un pais al otro, y no solo por los impuestos o costos de materiales, sino por cómo cotiza el modelo en el mercado.

## Descripción del problema
​
Hemos sido contratados como científico de datos en una consultora de renombre. Nos han asignado a un proyecto de estudio de mercado de una importante automotriz china. Nuestro cliente desea ingresar a nuestro mercado de automóviles, por lo que nos han encomendado analizar las características de los vehículos presentes en el mercado actual. Dado que tienen en su catálogo una amplia colección de modelos de todo tipo, cuyo catálogo está estratificado en gamas según el gusto de cada región, desean saber qué características presentan los vehículos de gama alta y los de gama baja, para poder abarcar todo el mercado ajustándose a toda la demanda y, en base a estos datos, poder cotizar correctamente los vehículos que ofrecerá. 

Para ello, nuestro departamento de datos ha recopilado precios y características de varios de los modelos de vehículos disponibles en nuestro mercado, junto con sus precios de venta al público. Nuestro Data Lead nos ha recomendado que analicemos detalladamente los datos, los preprocesemos debidamente y que diseñemos dos modelos predictivos, uno para el precio y otro para distinguir vehículos de gama alta y de gama baja, utilizando la mediana de los precios como punto de corte. Desean obtener los archivos con las predicciones en formato de texto plano.

Además del análisis detallado de la exploración de los datos, estas son las dos predicciones posibles que les interesaría analizar:
​
1. Implementar un modelo de clasificación con aprendizaje supervisado que permita clasificar el precio de los vehículos en baratos y caros usando la mediana de los precios como punto de corte, utilizando los datos que se han puesto a su disposición.

​2. Implementar un modelo de regresión con aprendizaje supervisado que permita predecir el precio final de los vehículos, utilizando los datos que se han puesto a su disposición.



## Entrega
​
Deben tener el código en un script .py o Jupyter Notebook .ipynb, el cual debe incluir un buen EDA, feature engineerging. Es importante **explicar claramente cada paso realizado** mediante comentarios en el script o textos formato markdown dentro del Notebook, pensar que cualquier persona debe entender de la mejor manera posible cada razonamiento y pasos aplicados.
​
Recuerden, además, que deben crear el repositorio que contenga el proyecto, por lo que es importante que le dediquen tiempo también a esta parte, dejando todo ordenado y con un README acorde, que sirva de introducción al contenido dentro de éste.
​
​
## Métrica a utilizar

El método de evaluación del desempeño, dependerá del modelo que usted decida implementar.
​
1. Para el modelo de aprendizaje supervisado de clasificación, pueden usar la métrica `Accuracy` para los vehículos de precio bajo (low):
​
$$ Recall=\frac{TP+ TN}{TP+TN+FP+FN}$$
​
Donde $TP$ son los verdaderos positivos, $FP$ los falsos positivos, $FN$ los falsos negativos y $FN$ los falsos negativos. 