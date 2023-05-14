# The last climb

## Análisis exploratorio de datos (EDA)

## Índice

1. [✍️ Descripción](#descripcion-del-proyecto)
2. [🏔️ Objetivo](#objetivo)
3. [🌀 Análisis](#analisis)
4. [🧗‍♀️ Conclusiones](#conclusion)
5. [🧊 Estructura](#estructura)


## ✍️ Descripción:<a name="descripción"/>

Proyecto EDA como Data Analyst en Ironhack. 

Con este proyecto se propone la práctica de análisis tipo EDA. Para ello, hemos escogido analizar las muertes registradas desde el 1895 en los 14 ochomil, las 14 montañas más altas de la Tierra donde cada año intrépidos aventureros y aventureras las intentan conquistar.

## 🏔️ Objetivo:<a name="objetivo"/>

El riesgo de conquistar alguna de las 14 ochomil es muy alto, las condiciones meteorológicas, las complicaciones y xxxxxxx son motivos cruciales a la hora de superarlo o no. Lamentablemente, cada año se quedan en el camino para siempre muchos de sus montañistas. De ellas, es el Everest el que más motañistas tiene al año llegando a las 800 visitas pero tenemos más dudas al respecto que nos disponemos a analizar para intentar esocger cuándo y cómo es más seguro hacer el ascenso:

- ¿Cuál es la montaña con más riesgo de fallecimiento?
- ¿Según qué época es mas letal subirlas? ¿Y cada una de ellas?
- ¿Hay alguna nacionalidad que se pone más en riesgo al intentar llegar a la cumbre?
- ¿Cuáles son las causas de muerte más comunes?
- ¿Puede haber alguna relación entre la causa de muerte y la nacionalidad?


## 🌀 Análisis:<a name="analisis"/>

En primer lugar, hemos decido crear un mapa para situar cada una de las cumbres.

![dashboard](./images/map.png)

En el siguiente dashboard podemos observar un resumen del conjunto total de los datos. Contiene un slider con el cual se puede seleccionar el rango de años del cual queremos obtener la información. Según ello, se puede saber cuales fueron los meses con más fallecimientos, las cinco causas de muerte más habituales, en qué montaña ha fallecido más gente y de qué diez nacionalidades eran esas personas.

La imagen muestra esos resultados filtrados desde el 1980 al 2003.

![dashboard](./images/5003.png)


El segundo dashboard lo hemos enfocado al análisis de cada una de las cumbres por separado. Para ello hemos creado un selector interactivo mediante el cual se puede elegir la montaña deseada. De ella obtendremos la información de su altura, su localización en el mapa, cuántos fallecidos hay en total, en qué meses han ocurrido los desastre y cuáles han sido las 7 causas más comunes.

En esta imagen podemos ver toda esta selección de la montaña K2, conocida por ser la más peligrosa.

![dashboard](./images/k2.png)



## 🧗‍♀️ Conclusiones:<a name='conclusion'/>





## 🧊 Estructura:<a name="estructura"/>

```
Proyecto 
|__ DATA/                         # contiene datos limpios de jupyter notebook y los csv limpios
|
|__ IMAGES/                       # contiene imagénes referentes al proyecto y de los dashboards   
|
|
|__ .gitignore                    # archivo gitignore     
|
|__ README.md                     # información del proyecto
```