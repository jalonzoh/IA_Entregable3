# IA_Entregable3
# Objetivo del Proyecto
## El proyecto tiene como objetivo:
-   Clasificar y agrupo por importe y cantidad vendida.
-   Predecir monto vendido en base a cantidad, precio unitario y importe

# Algoritmo elegido:
Para el proyecto aurelion se elijo dos modelos

1.- Modelo de regresion Lineal, se tratara de prededir el monto total en base a cantidad, precio unitario y importe para variaciones de precio, cantidad.

2.- Modelo K-means de agrupamiento en base al importe y la cantidad venvida para saber que cantidad es la que genera mas ingreso a la tienda.

# Entradas X y Y

1.- Para el modelo de regresión lineal se tiene las siguientes entradas:
    Y = Importe.
    X = cantidad, precio_unitario y categoria.

2.- Para el modelo de k Means
    X = Importe
    Y = Cantidad Vendida

# Metricas de Evaluación:

1.- Para el modelo de regresion lineal
    Para el este modelo se tuvo un valor de R2=0.87 un valor moderable siendo el valor optimo 1
2.- Para el modelo de k-means
    Para el este modelo se tuvo un valor de Silhouette=0.275 un valor muy lejano de 1 el valor de ideal.
    
# Modelo ML implementado.
El modelo implementado es el de regresión lineal por el valor de R2=0.87 un valor muy cercano a 1

# División train/test y entrenamiento
Del total de datos 333 se dividio el 20% de registros para test y 80% de registros para entrenamiento.

# Predicciones y métricas calculadas
Para el modelo de regresión lineal elegido para una venta total de 10000 unidades, precio unitario de $/. 5, de la categoria limpieza (1):
Venta Total sera $25,511,219

# Resultados en uno o más gráficos
Revisar el archivo ipynb, ahi encontrara todos los graficos.


