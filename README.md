# Taller1_Gesti-n_Datos

Integrantes:</br></br>
Juan Sebastian Pineda</br></br>
Camilo Cano Ortega</br></br>
Daniel Duque</br></br>

Enlace video: https://www.youtube.com/watch?v=jrPXW-PpDG4

</br></br>
Revisar notebook Taller_1_Gestión_de_Datos.ipynb para todo el desarrollo. 

</br></br>
Puntos a Desarrollar
</br></br>
1. Seleccione al menos 4 conjuntos de datos y realice un perfilamiento de cada uno. Describa los hallazgos encontrados en cada conjunto de datos. No
olvide mencionar su estructura y aspectos relevantes de calidad como campos
nulos, departamentos mal escritos, formatos de fechas incorrectos, entre otros.
Si no evidencia ningún problema de calidad de datos, también mencionelo.
</br></br>

2.1 ¿Cuáles han sido los departamentos (TOP 3) más afectados en
términos de cantidad de delitos cometidos en los últimos 5 años?

</br></br>

<b>Accidentes de transito</b>

</br></br>

Se tiene que en primer lugar, la sección de antioquia, excluyendo medellin tienen una concentración muy grande de registros de accidentes; el top 10 de municipios, tiene alrededor del 57% del total de casos; en donde sobresalen a lo largo del tiempo la región andina, con la mayor concentración.

</br></br>

<b>Hurto</b>
</br></br>
Los Departamentos más afectados fueron Cesar, Meta y Cundinamarca
</br></br>
<b>Violencia Intrafamiliar</b>
</br></br>
Los Departamentos más afectados fueron Valle, Antioquia y Cundinamarca
</br></br>
<b>Delitos sexuales</b>
Los Departamentos más afectados fueron Valle, Antioquia y Cundinamarca
</br></br>

2.2 Para los casos en los que aplique, ¿cuál ha sido el arma o medio
más común para cometer el delito?
</br></br>

<b>Accidentes de transito</b>
</br></br>
Se tiene que los medios mas usados son vehiculo y moto.
</br></br>

<b>Hurto</b>
</br></br>
Principalmente se han realizado delitos de violencia intrafamiliar con armas contundentes, luego sin empleo de armas, no repartado, arma cortopunzante y escopolamina
</br></br>
<b>Violencia Intrafamiliar</b>
</br></br>
<b>Delitos sexuales</b>
</br></br>
De acuerdo a la información correspondiente a los ultimos 5 años los delitos de indole sexual se cometen sin ningún tipo de Armas, sin embargo en el caso en que son usadas las más usadas son las de tipo contundente
</br></br>
2.3 Para los casos en los que aplique, ¿cómo ha sido la proporción de
géneros y grupos etarios que han estado involucrados en este tipo de
delito? ¿Han variado con el paso de los años?
</br></br>

<b>Accidentes de transito</b>
</br></br>
Más del 91% de los casos fueron generados por adultos, dando una pequeña porción a menores y adolecentes con cerca del 4% en ambos casos.
Cerca del 80% de los homicidios estaban involucrados hombres.
</br></br>
<b>Hurto</b>
</br></br>
Al principio eran un poco mayores los crimenes relacionados con personas masculinas que femeninas. Esto permanece en el tiempo, pero aumentan la cantidad de crimenes en ambos casos
</br></br>
<b>Violencia Intrafamiliar</b>
</br></br>
La mayoría de personas afectadas son femeninas, esta tendencia se mantiene por toda la serie de tiempo, aunque hay fluctuaciones en la proporción.
</br></br>
<b>Delitos sexuales</b>
</br></br>
Se ve que el grupo etario mas afectado son mujeres y menores de 14 años
</br></br>

2.4 ¿Se evidencia alguna tendencia para cometer dicho delito en algún
mes particular del año?
</br></br>

<b>Accidentes de transito</b>
</br></br>
Se evidencia que a lo largo de los años se han presentado un aumento en la cantidad de accidentes de transitos, en el unico año que se presenta una disminución marcada, fue en el año 2020, producto de los cierres de pandemia, sin embargo la cifra de muertos en accidentes de transito ha crecido en mas de un 50%, tomando como base los datos de la ultima década.
</br></br>
Se evidencia que los días con mayor número de accidentes se encuentran entre el viernes y el domingo; en donde los dias con mayor cantidad de eventos fueron los sábados y domingos.
</br></br>
Los meses de diciembre y enero, son los meses con mayor cantidad de homicidios, esto puede estar relacionados con la temporada alta.
</br></br>
Se evidencia que en el valle y Medellín, son los lugares con mayores datos relacionados con una Moto. Reacionado con los vehiculos  las ciudades (Bogotá, Valle y Antioquía) son las ciudades con mayor cantidad de accidentes.
</br></br>
<b>Hurto</b>

<b>Violencia Intrafamiliar</b>

<b>Delitos sexuales</b>

2.5 Para los casos en los que se disponga del detalle del delito o de una
descripción, como por ejemplo en delitos sexuales y secuestro, ¿cuáles
son las descripciones o modalidades más comunes?
</br></br>

<b>Accidentes de transito</b>
</br></br>
Se tiene que en primer lugar, la sección de antioquia, excluyendo medellin tienen una concentración muy grande de registros de accidentes; el top 10 de municipios, tiene alrededor del 57% del total de casos; en donde sobresalen a lo largo del tiempo la región andina, con la mayor concentración.

</br></br>
<b>Hurto</b>
</br></br>
El primer mes del año tiene muchos mas casos que los demás por lo que es posible que haya alguna tendencia fuerte para enero, o la gente este mas deseperada por robar
</br></br>
Solo hay dos, y en ambos casos son bastantes similares la cantidad de hurtos que hay tanto a entidades comerciales como a residencias
</br></br>

<b>Violencia Intrafamiliar</b>
</br></br>
2.5 para este dataset no se encuentran este tipo de información
</br></br>
<b>Delitos sexuales</b>
</br></br>
Los delitos mas columnes son:</br></br>
ACTOS SEXUALES CON MENOR DE 14 AÑOS </br></br>
ACCESO CARNAL ABUSIVO CON MENOR DE 14 AÑOS</br></br>
ACCESO CARNAL VIOLENTO</br></br>
ACTO SEXUAL VIOLENTO</br></br>
ACOSO SEXUAL
</br></br>
3. A partir de alguno de los conjuntos de datos seleccionados, visualice una
serie de tiempo por año y mes que permita comparar la cantidad de delitos
cometidos para los departamentos con mayor ocurrencia durante los últimos 5
años. Para que los resultados entre departamentos sean comparables, es
importante que normalice las cantidades obtenidas por cantidad de habitantes.
En este archivo puede encontrar la población por departamento para el año
2018. Asuma que la población no ha cambiado con el paso de los años.

</br></br>

Nos encontramos que los departamentos con mas hurtos son
"HUILA","PUTUMAYO","CASANARE","SANTANDER","BOYACA" por 10000 habitantes,
después de visualizar la  gráfica nos damos cuenta que los datos van decreciendo
progresivamente y que Casanare en particular ocupa el primer puesto para enero 2021

</br></br>
4. A partir de los conjuntos de datos seleccionados, construya un único
dataset que integre la totalidad de los delitos ocurridos por departamento y
municipio. Muestre los valores normalizados por cantidad de habitantes
realizando un proceso similar al del punto anterior. En este archivo puede
encontrar proyecciones anuales de las poblaciones por departamento. Utilice la
proyección para el año en curso. Considere solamente los municipios con más
de 1 millón de habitantes.
</br></br>
De mantenerse los crimenes seleccionados, se presentan crecimientos mayores al 12% en un rango entre 2021-2035. La ciudad con mas crimenes es Bogotá, aunque el mayor crecimiento se da en la ciduad de Medellín. Con respecto a Cartagena es la ciudad principal con un nivel menor al 10% en los 15 años.

