# Modelo SIR y ¿Cuál fue la eficacio de las medidas profilápticas tomadas contra la Pandemia del COVID-19 en MX?

## Introducción 
Se utilizaron los datos de contagios de COVID-19 en México (obtenidos de la [página oficial](https://datos.covid-19.conacyt.mx/)) y el modelo SIR para poder calcular la tasa de 
infeccion del virus en diferentes épocas y así poder determinar si las medidas tomadas frenaron la transimisón o no.

## Procedimiento
Primero se leyeron los datos de la página ya mencionda. Posteriormente se hizo un suavizamiento con promedios móviles para visualizar mejor los datos.
IMAGEN DE SUAVIZADOOOO


Se tomaron las primeras dos semanas del inicio de la pandemia y por medio del método de mínimos cuadrados (aplicado al modelo SIR) se hizo una estimación 
de los valores del número de infectados iniciales y la tasa de infección. Se hizo lo mismo para los siguientes intervalos:

* 18 de Marzo del 2020 al 31 de Marzo del 2020. Comienzo de la pandemia en México
* 31 de Marzo del 2020 al 15 de Abril del 2020. Inicio del uso de cubrebocas y sana distancia
* 15 de Abril del 2020 al 30 de Abril del 2020. Incio de la cuarentena
* 30 de Abril del 2020 al 15 de Mayo del 2020.

Despues de ajustar el modelo SIR a cada subintervalo de tiempo, se calculó la aproximación para la tasa de infección

## Resultados
Las aproximaciones obtenidas fueron las siguientes
* 18 de Marzo del 2020 al 31 de Marzo del 2020. $\beta = 20.5586$
* 31 de Marzo del 2020 al 15 de Abril del 2020. $\beta = 20.5624$
* 15 de Abril del 2020 al 30 de Abril del 2020. $\beta = 20.4683$
* 30 de Abril del 2020 al 15 de Mayo del 2020. $\beta = 20.4984$

## Conclusiones

Al comparar la tasa de contagio durante el tercer periodo de tiempo, el cual va del 15 de abril al 15 de mayo del 2020, se concluye que $\beta$ aumenta
(pasa de 20.4683 a 20.4984; es decir, aumenta en un 3.01%). Por lo tanto, al aumentar se puede asegurar que las medidas tomadas no fueron efectivas.
