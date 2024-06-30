# ProyectoAnalisisyprocesamiento
Proyecto Final Análisis y procesamiento de datos

Resumen del Código

Carga del Dataset desde Google Drive:
Utilizamos la URL de descarga directa de un archivo CSV alojado en Google Drive para cargar los datos utilizando Pandas.

Preprocesamiento de Datos:
Convertimos la columna 'LeaveOrNot' de valores binarios (0 y 1) a etiquetas categóricas ('Not Leave' y 'Leave') para facilitar su interpretación.
Análisis Exploratorio de Datos (EDA):

Gráfico de Distribución de Sexos: Utilizamos un gráfico de torta para visualizar la distribución de géneros en el dataset.
Gráfico de Niveles de Estudio: Creamos subplots con un histograma y un gráfico de torta para explorar la distribución de los niveles de estudio de los empleados.
Histograma de Edades y Licencias: Utilizamos un histograma para responder si los jóvenes son más propensos a tomar licencias, explorando la distribución de las edades de los empleados que tomaron y no tomaron licencias.
Distribución de Clases 'LeaveOrNot': Graficamos la distribución de clases para verificar si el dataset está balanceado en términos de proporción entre aquellos que toman y no toman licencias.

Gráficos Generados
Gráfico de Distribución de Sexos:
Visualiza la proporción de géneros (masculino y femenino) en forma de gráfico de torta.

Gráfico de Niveles de Estudio:
Muestra un histograma de los niveles de estudio de los empleados.
Acompañado por un gráfico de torta que ilustra la distribución porcentual de los niveles de estudio.

Histograma de Edades y Licencias:
Explora la distribución de edades de los empleados que tomaron y no tomaron licencias mediante un histograma.

Distribución de Clases 'LeaveOrNot':
Representa gráficamente la proporción de clases 'Leave' y 'Not Leave' en el dataset.
