# Facultad de Estudios Superiores Acatlán

## Tarea


**Fecha de entrega**

* Fecha límite de entrega: jueves 11 de noviembre de 2021 a las 11:59 pm.
* Entregable: Archivo word, pdf o html con los resultados y comentarios. 
* Enviar solución al mail: leonardo.marintellez@gmail.com y en el asunto poner **muestreo2021_tarea09**


El objeivo de la tarea es que resulevan ejemplos prácticos de manipulación de datos dado que es muy común que al trabajr con datos una parte de importante del tiempo se lo lleva el preprocesamiento de los mismos.



**Ejercicio 1**

Utilizar los datos de [sucursales](https://github.com/leonardomarintellez/muestreo_2021/tree/master/datos/sucursales)  para identificar los bancos que tienen presencia en municipios donde ningun otro banco tiene una sucursal, es decir, para cada banco identificar el número de municipios donde son los unicos que tienen alguna sucursal. Notar que habrá bancos que no cumplan con este criterio. Proporcionar una tabla con el nombre del banco y el número de municipios donde sólo ellos tienen sucursales.


**Ejercicio 2**

Utilizar los datos de [ratings de películas](https://github.com/leonardomarintellez/muestreo_2021/tree/master/datos/MovieLens) para calcular lo siguiente:


- Número de usuarios y número de películas
- Las 3 películas con mejor promedio y las 3 películas con peor promedio
- La película con el mayor número de calificaciones y cuantás son.
- El usuario que ha calificado un mayor número de películas y cuántas ha calificado.
- El número promedio de evaluaciones por película.

Para el siguiente punto intenten resolver la parte de identificar el año usando expresiones regulares (regular expressions).

- Calcular el número de pelícilas por año

Noten que para resolver un par de puntos deben unir la información de las tablas _data_ e _item_


**Ejercicio 3**

Utilizar los datos del [censo 2010](https://github.com/leonardomarintellez/muestreo_2021/tree/master/datos/censo_2010) de la tabla de persnas del Estado de México para crear una grafica de dispersión de la edad de la persona vs la edad de su madre. Para identificar las variables que les ayudarán para este ejercicio consulten el diccionario de del cuestionario ubicado en el mismo vínculo que los datos. No a todas las personass podrán asignarles la edad de su madre, sólo conserven os registros donde tengan dato tanto de la persona como de su madre.



**Ejercicio 4**

Utilizar los datos que hemos visto en clase de [House Prices](https://github.com/leonardomarintellez/muestreo_2021/tree/master/datos/HousePrices). A esa tabla de datos deben crearle una variable adicional que tenga 2 categorías 'train' y 'test'. El 70% de los registros deben estar arcados con la categoría 'train' y el restante 30% con la categoría 'test'. Es decir, creen una muestra aleatoria de aproximadamente el 70% de los datos y a los ids que correspondan a los ids de la muestra asignenles la categoría 'train' y a los ids restantes asignenles la categoría 'test'. En su mail de entrega de tarea adjuntar una tabla con 2 variables, el id de la casa y la categoría. 


Para esta tarea incluyan su código o archivos de construcción.



