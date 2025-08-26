1)Descarga de datos
Se utilizan los precios de cierre diarios de Apple desde el 1 de enero de 2018 hasta el 31 de diciembre de 2024, descargados directamente con yfinance.

2)Exploración de Datos (EDA)
Revisión de la información general (.info()) y valores faltantes.
Estadísticas descriptivas básicas (.describe()).
Visualización de la evolución histórica de los precios.

3)Análisis Técnico
Cálculo de medias móviles simples (SMA): 50 y 200 días.
Visualización de SMA sobre el precio de cierre para identificar tendencias.
Pronóstico de Precios
Se aplicó el modelo Holt-Winters (Exponential Smoothing) con tendencia aditiva.
Se generó un pronóstico a 60 días hábiles mostrando la tendencia futura del precio.
La línea roja del pronóstico se visualiza junto a la serie histórica.

4)Visualización Final

Gráfico combinado del precio histórico y pronóstico.
SMA50 y SMA200 para complementar el análisis técnico.
