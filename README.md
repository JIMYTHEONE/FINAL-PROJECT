# 🏔️Himalaya Analysis🏔️

#  OBJETIVOS 🎯 

1. El objetivo es mostrar información relevante sobre las distintas expediciones que se han ido realizando desde 1910 hasta 2020 a través de visualizaciones gráficas.

2. Crear un modelo predictivo que mediante una serie de variables muestre las probabilidades que tiene el usuario de conseguir ascender el pico que desea. 




#  PASOS SEGUIDOS 📋

# 1) Extracción 

Se han extraído datos sobre los ascensos de la base de datos [Himalayan Expeditions](https://www.kaggle.com/datasets/raskoshik/himalayan-expeditions).

Se ha alimentado el dataset con información sobre las coordendas de los picos vía webscraping con Selenium.

Las principales tablas sobre las que se han trabajado los datos son las siguientes:

    - Deaths.csv
    - Expeditions.csv
    - Peaks.csv
    - Summiters.csv

# 2) Transformación 

Una vez extraídos los datos y convertidos a los dataframes pertinentes, se ha procedido a su transformación y limpieza.

La limpieza ha consisitido en cambiar los tipos de datos, crear nuevas columnas y alimentarlas con los datos extraidos, eliminar las columnas que no fueran de utilidad para el análisis, rellenar los valores nulos.






# VISUALIZACIÓN ⇲

Se han generado las siguientes visualizaciones:
  
    1. Muertes acumuladas por estación del años.
    2. Número total de expediciones agrupado por género.
    3. Número de muertos por edades.
    4. Número de expediciones por año.
    5. Número de expediciones por picos.
    6. Top summits por países.
    7. Uso de oxígeno en el ascenso por países.

Para una mejor visualización, a través de Folium se ha generado un mapa con las localizaciones de los picos que distingue entre 3 marcadores distintos:

   1. Color verde con bandera :  Picos conquistados.
   2. Color rojo con ojo tachado:  Picos que no se han conseguido ascender.
   3. Color azul con estrella: Los picos con +8000 metros de altura.


