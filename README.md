# SHARK ATTACK ANALYSIS

                       ![labs](INPUT/labs.png?raw=true "Title")


Bien es sabido que el estado de Florida, USA, destaca por un clima cálido, con altas temperaturas y sol a lo largo del año. Aunque los inviernos son mas fríos, siguen siendo temperaturas suaves. 

Aun considerando lo anterior, la intuición me lleva a pensar que el turismo del surf en la zona se intensifica en primavera y verano, lo que me lleva a suponer que existe una mayor cantidad de ataques de tiburón en estas estaciones. 

Para descubrir si mi hipótesis tiene sentido, he realizado un exhaustivo estudio sobre un amplio registro de dichos ataques.

***

Para la limpieza del Dataset he realizado las siguientes técnicas:

- REDUCCIÓN DEL NÚMERO DE COLUMNAS A LAS QUE SON INTERESANTES PARA EL ESTUDIO
- COMPROBACIÓN DE VALORES NULOS EN LA COLUMNA "DATE" Y ELIMININACIÓN DE ESTOS
- PRIMER BARRIDO DE REGISTROS DUPLICADOS¶
- ESTUDIO DE VALORES NULOS A LO LARGO DEL DATAFRAME¶
- ELIMINACIÓN DE LA COLUMNA DE "LOCATION", YA QUE NO SERÁ NECESARIA EN ADELANTE
- REDUCCIÓN EL DATAFRAME A LAS ACTIVIDAD DE "SURFING" EN FLORIDA (USA)
- TRATAMIENTO DEL CAMPO "DATE", PARA EXTRAER LOS MESES 
- ELIMINACIÓN LA COLUMNA "DATE", YA QUE NO SERÁ NECESARIA EN ADELANTE

***

El análisis ha consistido en categorizar los meses en temporada Primavera-Verano y Otoño-Invierno. Representando la suma de estos valores he llegado a la conclusión que *mi hipótesis se confirmaba*.


![image.jpg](INPUT/grafico.jpg?raw=true "Title")








![image.jpg](INPUT/image.jpg?raw=true "Title")






