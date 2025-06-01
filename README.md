### ¿Qué hace exitoso a un videojuego? Un estudio de datos para Ice Store

#### Objetivo del proyecto

Identificar los factores clave que determinan el éxito comercial de un videojuego a partir del análisis de datos históricos (reseñas, géneros, plataformas, ventas, etc.), con el fin de:

- Predecir el potencial de nuevos lanzamientos

- Optimizar decisiones de marketing

- Detectar oportunidades para campañas publicitarias efectivas

#### Lenguaje de programación, librerías y habilidades 
![Python](https://img.shields.io/badge/PYTHON-%232A5D9F.svg?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/PANDAS-%232A5D9F.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NUMPY-%232A5D9F.svg?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SCIPY-%232A5D9F.svg?style=for-the-badge&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/MATPLOTLIB-%232A5D9F.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/SEABORN-%232A5D9F.svg?style=for-the-badge&logo=seaborn&logoColor=white)
![Limpieza de Datos](https://img.shields.io/badge/LIMPIEZA%20DE%20DATOS-%233B7DD8.svg?style=for-the-badge&logoColor=white)
![Análisis de Datos](https://img.shields.io/badge/ANÁLISIS%20DE%20DATOS-%233B7DD8.svg?style=for-the-badge&logoColor=white)
![Análisis Estadístico](https://img.shields.io/badge/ANÁLISIS%20ESTADÍSTICO-%233B7DD8.svg?style=for-the-badge&logoColor=white)

#### Preguntas clave

- Mira cuántos juegos fueron lanzados en diferentes años. ¿Son significativos los datos de cada período?

- ¿Qué plataformas son líderes en ventas? ¿Cuáles crecen y cuáles se reducen? Elige varias plataformas potencialmente rentables.

- Echa un vistazo a la distribución general de los juegos por género. ¿Qué se puede decir de los géneros más rentables? ¿Puedes generalizar acerca de los géneros con ventas altas y bajas?

#### Metodología

- Preprocesamiento de datos: Se limpiaron y ajustaron los datos: se corrigieron tipos, se eliminaron duplicados y se trataron valores faltantes (como los marcados como “TBD”). También se creó una nueva columna que sumaba las ventas totales por juego, unificando todas las regiones.

- Análisis exploratorio de datos (EDA): Se revisó la cantidad de juegos por año, las plataformas con más ventas y cómo cambian con el tiempo. También se analizaron géneros, calificaciones y diferencias regionales. Se usaron visualizaciones y estadísticas básicas para entender los patrones más importantes.

- Análisis estadístico de datos: Se hicieron comparaciones entre plataformas y géneros, usando pruebas de hipótesis. Se midieron relaciones entre calificaciones y ventas para entender si influyen en el éxito. Todo con base en datos reales y evidencia clara.

#### Conclusión general

Este proyecto ha permitido construir una base sólida de análisis a partir de datos bien preparados y explorados, lo que permitió generar un modelo confiable para el año 2017. Gracias a este trabajo, quienes toman decisiones dentro del negocio cuentan con información útil para identificar juegos prometedores, planear campañas más efectivas y maximizar los resultados.

Los hallazgos obtenidos no solo mejoran el rendimiento a corto plazo, sino que también aportan valor estratégico a largo plazo en un sector altamente competitivo y rentable como el de los videojuegos.

#### Diccionario de Datos – Ice Store
- Name - Nombre del videojuego.
- Platform - Plataforma en la que fue lanzado el juego (ej. PS4, Xbox One, PC, etc.).
- Year_of_Release - Año de lanzamiento del videojuego.
- Genre	- Género del videojuego (Acción, Aventura, Deportes, etc.).
- NA_sales -	Ventas en Norteamérica (millones de dólares estadounidenses).
- EU_sales - Ventas en Europa (millones de dólares estadounidenses).
- JP_sales - Ventas en Japón (millones de dólares estadounidenses).
- Other_sales - Ventas en otras regiones fuera de NA, EU y JP (millones de dólares).
- Critic_Score - Calificación promedio de la crítica (escala de 0 a 100).
- User_Score - Calificación promedio de los usuarios (escala de 0 a 10).
- Rating - Clasificación de contenido ESRB (Everyone, Teen, Mature, etc.).

**Nota:** Es posible que los datos de 2016 estén incompletos.
