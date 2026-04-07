# ABP 5 - Análisis Exploratorio de Datos (EDA)

## Descripción del proyecto

Este proyecto corresponde al desarrollo de un Análisis Exploratorio de Datos (EDA) aplicado a un conjunto de transacciones comerciales compuesto por 99457 registros y 10 variables.

El objetivo principal fue identificar patrones estadísticos, relaciones entre variables numéricas y categóricas, así como construir modelos básicos de regresión lineal para interpretar el comportamiento del precio total de compra.

## Variables principales analizadas

* invoice_no
* customer_id
* gender
* age
* category
* quantity
* price
* payment_method
* invoice_date
* shopping_mall

## Herramientas utilizadas

* Python
* pandas
* seaborn
* matplotlib
* statsmodels

## Análisis realizados

* Revisión estructural del dataset
* Estadística descriptiva
* Histogramas y boxplots
* Correlación de Pearson
* Pairplot, Jointplot, Violinplot y FacetGrid
* Regresión lineal simple y múltiple
* Evaluación mediante MAE y MSE

## Principales hallazgos

* price presenta distribución asimétrica positiva
* unit_price muestra alta correlación con price
* quantity aporta explicación adicional al modelo
* age presenta baja significancia estadística
* gender y payment_method no muestran diferencias relevantes en distribución de precios

## Contenido del repositorio

* Notebook completo del análisis
* Informe en PDF
* Gráficos exportados
* Código fuente comentado

## Autor

Alejandro González Cayuhan
