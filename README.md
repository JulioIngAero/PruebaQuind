# PruebaQuind

Descripción del Proyecto
Este proyecto tiene como objetivo extraer, transformar y analizar datos de películas, clientes, alquileres y tiendas desde un archivo Excel (Films2(4).xlsx). Utilizamos técnicas de limpieza de datos y procesamiento para asegurar que la información esté en un formato adecuado para su análisis y generación de informes. Además, proporcionamos visualizaciones y análisis exploratorios para responder a preguntas de negocio clave.

Detalle de Implementación: Arquitectura de Datos y Proceso ETL

Extracción:
Herramienta Utilizada: pandas
Descripción: Los datos se cargan desde un archivo Excel con múltiples hojas utilizando la función pd.read_excel().

Transformación:
Herramienta Utilizada: PySpark
Descripción:
Renombramos columnas con espacios en sus nombres.
Limpiamos datos numéricos eliminando caracteres no válidos y convirtiéndolos a su tipo adecuado (int o float).

Carga:
Herramienta Utilizada: pandas, PySpark
Descripción: Los datos transformados se guardan en formato Parquet, un formato columnar eficiente para almacenamiento y procesamiento de datos.

Nota:
Todos los documentos solicitados y necesarios para ejecutar el programa se enecuentran en este repositorio y basta con ejecutar las 3 primeras lineas para enlazarlos con el programa.
