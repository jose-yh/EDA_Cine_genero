# EDA_Cine_género
 Análisis_del_cine_género_cinematográfico

# 1. INTRODUCCION
El presente proyecto se centra en el análisis del cine de género drama y terror, con un enfoque particular en el cine de terror en lengua española. Surge de la inquietud por comprender las razones detrás de la escasa producción de películas de terror en este idioma. Además, la influencia del idioma en la escritura de guiones podría desempeñar un papel crucial en la forma en que se desarrollan las historias y los personajes. 

# 2. HIPÓTESIS
La hipótesis se puede resumir de la siguiente manera: 
¿La lengua en la que se redacta el guion de una película influye significativamente en su clasificación dentro del género cinematográfico, afectando la percepción y la recepción del género de terror en el cine hispanohablante?
Esta hipótesis se basa en la idea de que factores como la historia de la producción cinematográfica, estereotipos culturales, tabúes, la promoción y el interés del público, así como el impacto del idioma en la narrativa, pueden contribuir a la escasa producción de películas de terror en lengua española.

# 3. HERRAMIENTAS UTILIZADAS Y FUENTE DE DATOS
Para ello, hemos utilizado una muestra de datos obtenida de Kaggle 
https://www.kaggle.com/datasets/akashguna/netflix-prize-shows-information?resource=download

# 4. ESTRUCTURA DE CARPETAS
A continuación se detallan las carpetas:
1. ``src/data``: contiene los archivos de datos utilizados en el analisis. 
2. ``src/notebooks``: contiene los notebooks con los códigos.
3. ``src/Memoria``: contiene un resumen del EDA.
4. ``src/Presentación``: contiene una presentación en PDF del EDA.
5. ``src/Presentación_video``: explicación en video del EDA.
6. ``src/README``: contiene el documento que en este momento estas leyendo.

# 5. DESARROLLO
1.  ¿Qué dificultades podemos encontrar?
- **Calidad y limpieza de datos:** 
El conjunto de datos pueden contener errores y valores faltantes. Se requiere de un análisis exhaustivo y técnicas de limpieza para asegurar la calidad de la información en el análisis. En esta fase, se eliminan caracteres no deseados (str.replace()), se eliminan espacios en blanco (str.strip()), se usan expresiones regulares (implementando regex=True en las operaciones para identificar y eliminar caracteres no deseados de manera más eficiente), filtrados por tipo de película y género, selecciones de columnas a ser trabajadas, análisis de valores nulos, reemplazo de nulos, entre otros.

2. ¿Qué análisis son realizados?
- **Análisis descriptivo de las películas**
 Llevamos a cabo un análisis para comprender la distribución de los idiomas en las películas del género de horror. Nuestro objetivo es identificar las tendencias lingüísticas que prevalecen en este tipo de producciones, así como explorar cómo el idioma puede influir en la narrativa. A través de una recopilación y revisión de datos, examinaremos las características de las películas de horror en diferentes idiomas, lo que nos permitirá obtener una visión más clara del panorama actual de este fascinante género cinematográfico.

- **Visualización de datos para las películas**
Nos enfocamos en la creación de visualizaciones que nos permitan explorar y comprender la relación entre el idioma de las películas y su género correspondiente. Analizaremos cómo estos factores interactúan y qué tendencias emergen de los datos.

3. En una siguiente fase, se centra en realizar un estudio estadístico profundo. Se llevará a cabo un análisis descriptivo detallado y se aplicarán pruebas estadísticas, como la Chi-Cuadrado, para examinar relaciones y patrones en los datos. Este análisis incluirá variables adicionales como idioma, género, país, rating y votos.



