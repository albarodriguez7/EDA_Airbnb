![alt text](src/img/logoAirbnb.png)

Este proyecto sobre un **Análisis Exploratorio de Datos (EDA)** de Airbnb trata de dar respuesta a preguntas que todos nos hemos planteado alguna vez a la hora de elegir un lugar donde alojarnos cuando salimos de nuestra casa.

Con este análisis queremos ayudar a las personas a comprender cómo varían los precios de los alojamientos y qué factores influyen en ellos. Muchos de estos factores son clave a la hora de establecer los precios y no solo están relacionados con el alojamiento en sí, sino también con factores externos que no siempre son visibles y resultan muy determinantes.

A continuación, se presenta una serie de hipótesis que servirán para conocer la realidad detrás de los precios y así entender qué factores influyen tanto en el precio de los alojamientos como en su nivel de demanda y satisfacción. De esta forma, podremos evitar precios abusivos.

---

## Hipótesis planteadas

- ¿Hay diferencias de precio entre barrios?
- ¿Cómo cambia el precio según el tipo de habitación (`room_type`)?
- ¿Los alojamientos con mayor capacidad (`accommodates`) tienen un precio más alto?
- ¿Un precio alto implica mejores puntuaciones?
- ¿Los anfitriones con perfil verificado (`host_identity_verified`) reciben mejores valoraciones?
- ¿A mayor número de noches, el precio medio por noche es inferior?

---

## Tecnologías utilizadas

- Numpy  
- Pandas  
- Matplotlib.pyplot  
- Seaborn

---

## Estructura del repositorio

La estructura del repositorio es la siguiente:

```plaintext
📁 src
 ├─ 📁 data
 │   ├─ EDA_data_airbnb_madrid.csv
 │   ├─ airbnb_madrid_clean_final.csv
 │   └─ data_airbnb_madrid.csv
 ├─ 📁 img
 ├─ 📁 notebooks
 │   ├─ Creacion_data_airbnb_madrid.ipynb
 │   ├─ Gráficas_más_visuales.ipynb
 │   ├─ Limpieza_datos.ipynb
 │   └─ Seaborn.ipynb

---

## Instrucciones de reproducción

*(Por definir)*

---

## Principales conclusiones

- El precio de los alojamientos varía significativamente según el barrio, confirmando la influencia de la localización.
- El tipo de alojamiento es un factor determinante: las viviendas completas presentan precios más elevados que las habitaciones.
- Los alojamientos con mayor capacidad tienden a tener precios más altos.
- Existe una relación moderada entre precio y valoraciones, aunque no es especialmente fuerte.
- Los anfitriones verificados suelen ofrecer alojamientos con precios más elevados.
- El número mínimo de noches influye en el precio por noche del alojamiento.

---

## Autores

- **Carlos D'Olhaberriague** → <https://github.com/Carlos72293>
- **Alba Rodríguez** → <https://github.com/albarodriguez7>
- **Francisco Rubio** → <https://github.com/franrubiorubio>
