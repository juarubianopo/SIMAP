# SIMAP
## Integrantes:
### Kishvari Osorio Delgado
### Jose Alvaro Celis Lopez
### Jhian Emmanuel Ramos Lopez
### Juan Alonso Rubiano Portela
# Sistema de Monitoreo de Agua para Piscicultura
#### Plantamiento del problema 


La piscicultura es la crianza de peces.   Esta  actividad  está creciendo en Colombia.   Esto  lo podemos ver   en la gráfica, en donde  su crecimiento  está superando la pesca.    El objetivo  del sector es cubrir  la demanda  de   pescado  a nivel nacional y  generar   exportaciones.En la búsqueda  de hacer competitivo   este sector  primario de la economía. se busca  diseñar un sistema para el monitoreo de piscicultura en  la  especie  de  tilapia,  Que  es la de mayor producción  a  nivel nacional,  en las etapas    de ovas  y larvas que son las de   mayor riesgo e incertidumbre por el alto índice de mortalidad,   Esto  es debido a la sensibilidad a cambios de algunas variables críticas presentes en el agua, tales como oxígeno disuelto, temperatura, turbidez y pH que ocasionan un índice de mortalidad mayor al 70 %. 
![image](https://user-images.githubusercontent.com/70378208/161796310-63fd967b-5a00-49f2-ba95-e944b327d9ab.png)

### Planteamiento de  la solución 


En base a los requerimientos de  la actividad proponemos. el siguiente  diseño   con un sistema  embebido,  unos sensores ( de oxigeno disuelto, temperatura, pH, nitratos y turbidez  en el agua )   y  como actuadores  se podría pensar en una moto  bomba  y  un calentador  para corregir  la temperatura    



### Análisis de  alternativas de los  componentes en el proceso de diseño  


A continuaci´on se realizan los comparativos para cada uno de los elementos
necesarios para el sistema.

### Sistema embebido
|Requisitos  | Arduino mega | EPS32| Raspberry Pi|
| ------------- | ------------- |-------------|-------------|
| Costo | $73.000  | $32.000 | $57.000|
| Puertos | 54  | 32 | ?|
|Velocidad| 16MHz|240MHz| 1GHz|
|Memoria| 256 KB|4MB|512MB|No|
|Bluetooth|Módulo externo|Si
|Voltaje|5V| 5-10V|5V
|Hibernación|Si|Si| Contenido de la celda  |
