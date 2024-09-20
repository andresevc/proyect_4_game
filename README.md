Descripción del Proyecto: Análisis de Datos de Videojuegos para Ice
Objetivo del Proyecto

El objetivo de este proyecto es analizar los datos históricos de ventas de videojuegos de la tienda online Ice para identificar patrones que determinen el éxito de un videojuego. A través del análisis de datos, se busca detectar proyectos prometedores y planificar campañas publicitarias efectivas para maximizar las ventas en el año 2017. El análisis también tiene como objetivo proporcionar experiencia trabajando con datos y pronosticar ventas futuras.
Datasets Utilizados

El proyecto utilizará los siguientes conjuntos de datos:

    games.csv: Incluye información sobre videojuegos, como el nombre, plataforma, género, año de lanzamiento, ventas por región, puntuaciones de usuarios y críticos, y clasificación ESRB.

    Las columnas clave son:
        name: Nombre del videojuego.
        platform: Plataforma en la que está disponible el juego.
        year_of_release: Año de lanzamiento.
        genre: Género del videojuego.
        na_sales, eu_sales, jp_sales, other_sales: Ventas en Norteamérica, Europa, Japón y otras regiones (en millones de dólares).
        critic_score: Puntuación de los críticos (máximo de 100).
        user_score: Puntuación de los usuarios (máximo de 10).
        rating: Clasificación ESRB (como Adolescente, Adulto, etc.).

Metodología

El análisis se llevará a cabo en varias etapas:

    Descripción de los Datos: Exploración inicial del dataset para entender la estructura y calidad de los datos. Se identificarán valores ausentes y duplicados, y se revisarán las características generales de las variables.

    Preprocesamiento de los Datos:
        Conversión de nombres de columnas a minúsculas.
        Conversión de datos a los tipos adecuados.
        Tratamiento de valores ausentes, especialmente en puntuaciones y años de lanzamiento. También se decidirá cómo manejar los valores "TBD" (a determinar).
        Cálculo de las ventas totales para cada juego sumando las ventas en todas las regiones.

    Análisis Exploratorio de Datos (AED):
        Distribución de lanzamientos por año: ¿Cuántos juegos se lanzaron en cada año y si los datos son representativos?
        Ventas por plataforma: Análisis de las plataformas con mayores ventas totales, identificando las más rentables y aquellas que han perdido popularidad con el tiempo.
        Plataformas líderes: Determinación de las plataformas más prometedoras para 2017 y análisis de la tendencia de ventas en plataformas nuevas y antiguas.
        Análisis de reseñas: Exploración del impacto de las reseñas de usuarios y críticos en las ventas de un juego en plataformas populares.
        Géneros más populares: Análisis de la distribución de juegos por género y evaluación de los géneros más rentables.

    Creación de un perfil de usuario por región:
        Identificación de las cinco plataformas y géneros más populares en Norteamérica, Europa y Japón.
        Análisis de cómo la clasificación ESRB afecta a las ventas en cada región.

    Prueba de Hipótesis:
        Hipótesis 1: Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son las mismas.
        Hipótesis 2: Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.

    Se formularán las hipótesis nulas y alternativas, y se utilizará un criterio estadístico adecuado para probar las hipótesis (como la prueba t). El umbral alfa se definirá para establecer la significancia.

Tecnologías Utilizadas

    Python: Lenguaje principal para manipulación y análisis de datos.
    Pandas: Para la limpieza, transformación y agregación de datos.
    NumPy: Para cálculos numéricos eficientes.
    Matplotlib y Seaborn: Bibliotecas de visualización de datos para crear gráficos de distribución y diagramas de caja.
    Jupyter Notebooks: Entorno interactivo que permite la creación de análisis documentados.

Resultados Esperados

    Visualizaciones que muestren claramente las tendencias de ventas de videojuegos por plataforma, género y región.
    Identificación de plataformas y géneros con mayor potencial de ventas.
    Un análisis detallado del impacto de las reseñas de usuarios y críticos en las ventas.
    Recomendaciones para futuras campañas publicitarias y lanzamiento de videojuegos en 2017 basadas en los hallazgos del análisis.

Conclusiones

Este proyecto proporcionará insights clave sobre los patrones de éxito en la venta de videojuegos, ayudando a la tienda Ice a planificar campañas de marketing más efectivas y mejorar la toma de decisiones estratégicas. Además, se obtendrá experiencia práctica en el análisis de datos, visualización y pruebas de hipótesis aplicadas a la industria de los videojuegos.
