# Respuestas al Análisis del Dataset de Tweets

### 1. Frecuencia de cuentas (Autores con mayor volumen de tweets)

El dataset cuenta con un total de 20 autores únicos. El Top 10 de autores por cantidad de tweets publicados es:

1. **TheEllenShow:** 3,147 tweets
2. **jimmyfallon:** 3,120 tweets
3. **ArianaGrande:** 3,081 tweets
4. **YouTube:** 3,073 tweets
5. **KimKardashian:** 2,926 tweets
6. **katyperry:** 2,908 tweets
7. **selenagomez:** 2,868 tweets
8. **BarackObama:** 2,863 tweets
9. **rihanna:** 2,852 tweets
10. **britneyspears:** 2,772 tweets

### 2. Análisis temporal (Conversión y distribución temporal)

La columna `date_time` fue convertida exitosamente a tipo `datetime64`. De esta se extrajeron variables de año, mes, hora y día de la semana.

- **Evolución por año:** La actividad de publicaciones mostró un crecimiento continuo desde el año 2009 hasta alcanzar un pico máximo en **2016** con más de 17,500 tweets, decayendo en enero de 2017 al finalizar la recolección del dataset.

### 3. Frecuencia y distribución de hashtags

Se identificaron un total de 25,818 hashtags en el conjunto de datos. Los 10 hashtags más utilizados son:

1. `#fallontonight`: 1,079
2. `#actonclimate`: 277
3. `#tbt`: 234
4. `#dailyfluff`: 215
5. `#lovetwitter`: 166
6. `#ts1989`: 165
7. `#1`: 162
8. `#fallonmono`: 152
9. `#confident`: 149
10. `#doyourjob`: 147

### 4. Conteo y balance de tweets por autor

El dataset procesado consta de **52,257 tweets limpios**. La distribución del volumen de publicación entre los autores principales se encuentra bastante balanceada, manteniéndose en un rango de entre ~2,770 y ~3,150 tweets por cuenta dentro del Top 10.

### 5. Intervalo de observación inicial y final

El rango temporal cubierto por los tweets del dataset es el siguiente:

- **Fecha y hora inicial (primer tweet):** `2009-12-18 07:36:00`
- **Fecha y hora final (último tweet):** `2017-01-24 02:30:00`
