## Mantenimiento Predictivo en máquinas de envasado mediante Inteligencia Artificial

Autora: Maria Teresa Gilabert Ramón

Trabajo Final de Máster realizado para finalizar los estudios del Máster en Inteligencia Artificial impartido por la Universidad Internacional de Valencia (VIU).

En esta plataforma se comparte el conjunto de datos utilizado así como el código Python implementado. 

El conjunto de datos original se almacena en el directorio "Dataset_TFM" y consta de cinco sub-conjuntos de datos:
- PDM_errors.csv
- PDM_failures.csv
- PDM_machines.csv
- PDM_maint.csv
- PDM_telemetry.csv

Estos datos se obtienen originalmente del portal web "Kaggle" [Microsoft Azure Predictive Maintenance](https://www.kaggle.com/datasets/arnabbiswas1/microsoft-azure-predictive-maintenance)

Además, se adjunta el conjunto de datos obtenido tras un proceso de limpieza, combinación y formateo de datos a partir de los anteriores:
- dfp_global.csv

Por otro lado, en el directorio "Notebooks" se pueden consultar los archivos con la programación en Pyhton realizada. Se organiza en cuatro partes, que corresponden cada una a una fase de la metodología CRISP-DM en particular. El propio nombre de cada archivo indica en qué consisten. No obstante, se ordenan del siguiente modo:
1. CRISP-DM - Exploración de los datos. Proceso de exploración de datos mediante técnicas estadísticas y uso de gráficos. 
2. CRISP-DM - Preparación de los datos. Procesos de limpieza, composición de nuevos datos, combinación, adaptación y formateo de los datos.
3. CRISP-DM - Modelado de los datos (CART). Aplicación de la técnica de árboles de decisión CART.
4. CRISP-DM - Modelado de los datos (Random Forest). Aplicación de la técnica de árboles de decisión Random Forest. 





