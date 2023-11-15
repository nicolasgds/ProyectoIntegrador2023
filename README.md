El Proyecto consiste en realizar extracciones diarias de datos bursátiles referentes al mercado nacional de CEDEARS. Con estos datos puede luego analizarse la evolución de cada uno de estos valores a lo largo del tiempo, como así también la pertenencia a cada Empresa asociada.

Las Empresas involucradas y los CEDEAR disponibles no suelen tener grandes variaciones. Por un lado, se guardarán estos datos ‘estáticos’ de Empresas y CEDEAR, y por otro, los detalles de comercialización diario de cada uno de estos instrumentos. De esta forma, la extracción de los registros diarios de operaciones entregarán de forma acumulativa cada vez más datos para analizar.

Preparación del entorno: Se corrobora la funcionalidad y disponibilidad de las herramientas y recursos a utilizar (Jupyter Notebook, librerías Python, MySQL Workbench, SQL Server, página web disponible)

Extracción primaria de datos: Se identifican y enlazan las variables de valor. Se analiza su viabilidad de extracción y la calidad de los datos.

Desarrollo de Funciones Scraper: Una vez se obtiene el acceso a los datos, se formulan los procesos automatizados de extracción y formateo.

Diseño y guardado en BBDD: Se diseña y se crea la BBDD para almacenar los datos extraídos.

Consultas y visualizaciones: Se realizan análisis exploratorios de los datos.

Ejecuciones diarias: Cada día de ejecución incrementará los registros de movimientos pertenecientes a cada CEDEAR y de esta forma, la base de nuestro análisis.