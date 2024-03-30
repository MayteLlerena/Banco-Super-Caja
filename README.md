# <h1 align="center"> Análisis del riesgo relativo para el sector financiero  </h1>

El equipo de análisis de crédito del banco "Super Caja" enfrenta una carga de trabajo abrumadora, debido al aumento en las solicitudes de préstamos dada la reciente disminución de las tasas de interés en el mercado. La metodología manual actual para procesar solicitudes de préstamo se ha demostrado ineficiente y lenta, lo que afecta negativamente la eficacia y la rapidez del proceso. Además de la creciente preocupación por la tasa de incumplimiento en la industria financiera añade presión a los bancos para identificar y mitigar los riesgos asociados con el crédito.

## Objetivo del proyecto

Armar un score crediticio a partir de un análisis de datos y la evaluación del riesgo relativo que pueda clasificar a los solicitantes en diferentes categorías de riesgo basadas en su probabilidad de incumplimiento. Esta clasificación permitirá al banco tomar decisiones informadas sobre a quién otorgar crédito, reduciendo así el riesgo de préstamos no reembolsables. Además, la integración de la métrica existente de pagos atrasados fortalecerá la capacidad del modelo para identificar riesgos, lo que en última instancia contribuirá a la solidez financiera y la eficiencia operativa del banco.

## Insumos

▪️ El conjunto de datos está disponible para descargar en este enlace 'https://bit.ly/3PATJdK'

## Herramientas que se usaron para el análisis

### Herramientas:

▪️ BigQuery

▪️ Looker studio 

▪️ Google Cloud

▪️ Google Colab

▪️ Pitch

### Lenguajes:

▪️ SQL

▪️ Python

## ¿Cuál fue el proceso de trabajo?

▪️ Procesar y preparar la base de datos, esto implica identificar, corregir o eliminar errores, inconsistencias y valores atípicos en los conjuntos de datos.

▪️ Análisis exploratorio:

    ▫ Utilizar gráficos de barras en LookerStudio para visualizar variables categóricas.
  
    ▫ Aplicar medidas de tendencia central y de dispersión.
  
    ▫ Creación de histogramas o boxplot en LookerStudio para visualizar variables numéricas.
  
    ▫ Cálculo de cuartiles en BigQuery (SQL).
  
    ▫ Cálculo de correlación de variables numéricas en BigQuery (SQL).
    
▪️ Técnica estadística:

    ▫ Calcular el riesgo relativo en cada grupo (Mal pagador, Buen pagador) de cada variable con respecto a la variable “default”.

    ▫ Validación de hipótesis en Python:

       - Los más jóvenes tienen un mayor riesgo de impago.
       - Las personas con más cantidad de préstamos activos tienen mayor riesgo de ser malos pagadores.
       - Las personas que han retrasado sus pagos por más de 90 días tienen mayor riesgo de ser malos pagadores.

▪️ Crear un dashboard en Looker Studio.

▪️ Comunicación de hallazgos con stakeholders.

## Chequea mis consultas en SQL

▪️ Aquí 👉🏻 'https://bit.ly/3PH3KGp'

## Dashboard en Looker Studio

![Análisis de la conducta de pago de clientes](https://raw.githubusercontent.com/MayteLlerena/Banco_Super_Caja/main/An%C3%A1lisis%20de%20la%20conducta%20de%20pago%20de%20clientes.png)
![Predicción del comportamiento de pago](https://raw.githubusercontent.com/MayteLlerena/Banco_Super_Caja/main/Predicci%C3%B3n%20del%20comportamiento%20de%20pago.png)
![Matriz de confusión y regresión logística](https://raw.githubusercontent.com/MayteLlerena/Banco_Super_Caja/main/Matriz%20de%20confusi%C3%B3n%20y%20regresi%C3%B3n%20log%C3%ADstica.png)

