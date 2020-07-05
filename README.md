MODELO DE CONSUMO 
-------------------------------------
_________________________________________

Descarga los datos .xls y .csv
Descarga el archivo R Markdown .RMD
---------------------------------------
Aparte puedes encontrar una hermosa presentacion en .HTML hecha con R knit
---------------------------------------
En el siguiente repositoriose encontrara con el analisis estadistico de un modelo de consumo de cerveza en donde se obtienen los estimadores de minimos cuadrados OLS, se hace un  a prueba de normalidad con los cuantiles teoricos y los muestrales, la prueba de nrmalidad Jarque-Bera, una prueba de los residuales estandarizados para hallar datos atipicos (Cooks) y los residuales estandarizados frente a losvalores ajustados (Por el metodo Matricial)

De igual forma se ajusta el modelo de regresion para obtener os estimadores por medio del comando lm() y luego se hace un analisis de significancia de los estimadores del modelo con un nvel de significalcia alpha del 5% usando el P-Valor, se hace la prueba de significancia de la regresion usando tambien el P-Valor con la estaistica de prueba F (Fisher-Snecdor) con 4 y 48 grados de libertad, y finalmente con lo anterior se determina el coeficiente de determinacion R_Cuadrado y R_cuadrado ajustado con 48 grados de libertad.

Se analisa la suma de cuadrados totales, la suma de cuadrados residuales y la suma de cuadrados esperados y luego se hace la prueba TSS=ESS + RSS del modelo en niveles y del modelo en diferencias donde se observa una igualdad entre ambos modelos estimados.

Se hace un analisis de la varianza y la desviacion estandar de los estimadores y del modelo para poder mediante la estadistica de prueba t-student hacer pruebas de significancia individual y de significancia de la regresion.

Finalmente se construyen los intervalos de confianza de los estiadores del modelo OLS por medio de la estadistica t-student y las desviaciones estandar

En la segunda parte se observa la prueba de restricciones lineales beta_2+2*Beta_4=0 y Beta_5=1/1000 sobre el modelo y se estima finalmente el modelo restringido y la significancia de sus estimadores para establecer si las restricciones son aceptadas.





