# Seguimiento de vuelos y pasajeros

## Información General
- **Fecha de los datos:** 01/01/2020 - 31/12/2020 y 01/01/2022 - 31/12/2022
- **Fecha de actualización de los datos:** 09/2023
- **Fecha de entrega:** 09/2023
- **Autora:** Bezmalinovich, Florencia

¡Sumérgete en los patrones y fluctuaciones de vuelos mientras desvelamos el ritmo de los cielos! 🌌🛫🛬.

## Título: Análisis de Patrones de Vuelo en Argentina: Perspectivas Data-Driven

### Introducción:

Bienvenidos al análisis de datos sobre patrones de vuelo en Argentina. Esta presentación ofrece un enfoque data-driven para entender la dinámica de la aviación en el país y cómo ha sido afectada por eventos clave, incluida la pandemia. Dirigida a expertos en ciencia de datos del equipo estatal, esta exposición proporcionará ideas valiosas para la toma de decisiones informadas.

### Contexto:

La industria de la aviación es crucial para la conectividad global y el desarrollo económico. Este análisis se centra en datos que abarcan aspectos como horarios de vuelo, aerolíneas y movimientos, revelando patrones que iluminan la situación pre-pandémica y post-pandémica en Argentina.

### Análisis de Datos:

1. **Hora Pico de Vuelos:**  
   Nuestra exploración inicial revela que las 16 horas marcan la hora pico de vuelos en el territorio argentino. Este dato tiene implicaciones significativas para la planificación de recursos y la gestión del tráfico aéreo.

2. **Día con Mayor Tráfico Aéreo:**  
   Los datos demuestran que los sábados experimentan el tráfico aéreo más intenso en Argentina. Esta tendencia puede influir en la programación de vuelos y la optimización de recursos.

3. **Aerolíneas Líderes:**  
   Al analizar vuelos domésticos e internacionales, las aerolíneas más prominentes incluyen Aerolíneas Argentinas SA, Jetsmart Airlines SA, FlyBondi Líneas Aéreas, American Yet SA y Baires Fly SA. Estos resultados brindan ideas sobre las preferencias de los viajeros y las oportunidades de colaboración.

4. **Impacto de la Pandemia:**  
   Nuestro análisis corrobora la hipótesis de una disminución significativa de vuelos durante la pandemia, superando incluso las expectativas. Esto subraya el desafío que enfrentó la industria y su capacidad para recuperarse.

5. **Análisis de Pasajeros:**  
   Investigamos la relación entre pasajeros en despegues y arribos internacionales, concluyendo que hubo más pasajeros en despegues en ambos años. Este análisis proporciona una comprensión clara de los flujos de pasajeros y su impacto en la industria.

### Conclusión:

En resumen, este análisis data-driven destaca los patrones de vuelo en Argentina y su evolución durante eventos cruciales. Los insights obtenidos pueden guiar estrategias de gestión del tráfico aéreo, decisiones de inversión y colaboraciones entre aerolíneas.

## Acerca del dataset

El dataset es una colección de información detallada sobre los vuelos que se realizaron en el territorio aéreo argentino durante todo el año 2020 y el año 2022 y fueron procesados por la Administración Nacional de Aviación Civil (ANAC). El conjunto de datos contiene desde vuelos nacionales hasta vuelos internacionales. Se registran tanto los vuelos comerciales como los vuelos privados, y se incluyen datos sobre las aerolíneas, los aeropuertos de origen y destino, las fechas y horarios de salida y llegada, la cantidad de pasajeros de cada vuelo. El conjunto de datos NO se actualiza en tiempo real.

## Objetivo, contexto y problema comercial
- Evaluar el impacto de la pandemia en la industria.
- ¿Cuál es la hora pico de vuelos en el territorio argentino?
- ¿Cuál es el día de la semana donde hay más aeronaves sobrevolando el territorio nacional?
- ¿Cuáles son las 5 aerolíneas con más vuelos domésticos en el país? ¿Y cuáles son las 5 aerolíneas con más vuelos internacionales?
- Actualmente, se desconoce el funcionamiento de los aeropuertos.
- Actualmente, es cuestión de estado conocer cuántas personas salen del país por medios aéreos y no regresan en el mismo año.
- Proporcionar información para políticas públicas.

## Contexto
Problemas e hipótesis

## Contexto
Objetivo

## Contexto
Contexto

## ¿Fue mayor la cantidad de personas que salieron del país o las que ingresaron al país?
## ¿Cuánto variaron los vuelos argentinos durante el año de pandemia vs. el año sin pandemia?
## ¿Se podría predecir cuántos pasajeros se subirán a un avión con una precisión de 1 persona o menos?

## Con Matplotlib, grafiqué datos en función de las horas revelando que el apogeo de actividad es a las 15:00 hs. Usamos un eje de tiempo para representar el flujo a lo largo del día 🕒. Cada punto en el gráfico cuenta una historia de actividad aérea. Los intervalos de una hora en el eje x permiten un análisis detallado. 
Explorando la dinámica temporal de los vuelos✈️📊

## Utilizando Python y Matplotlib, encontramos que el día jueves es el día de mayor actividad aérea y lo resaltamos con color celeste, con tan solo 526 vuelos de diferencia el día viernes quedó en segundo lugar.
Observar cómo los días de la semana se despliegan en el eje x, mientras que la cantidad de vuelos se eleva en el eje y. Este análisis visual revela patrones ocultos y abre ventanas hacia una comprensión más profunda de la dinámica de los vuelos.
Explorando el flujo aéreo semanal ✈️📊

## Utilizando NumPy y Matplotlib, identificamos la aerolínea líder en vuelos domésticos es Aerolíneas Argentinas S.A. Relevé el rendimiento de cada aerolínea en el escenario doméstico. Observa cómo el eje y muestra las aerolíneas y el eje x muestra la cantidad de vuelos. Este análisis visualiza el dominio de las aerolíneas en los vuelos internos. 
Explorando los líderes en el mercado✈️📊

## Empleando Seaborn detecté que Aerolíneas Argentinas S.A. también es la aerolínea líder de vuelos internacionales. En este caso cambian las aerolíneas que la siguen en jerarquía. El eje y enumera las aerolíneas, mientras que el eje x cuantifica sus vuelos.

## Análisis de la variación de vuelos argentinos: año pandémico vs. año sin pandemia y mayor inmunización✈️📊
Mediante análisis y visualización de datos, evaluamos la hipótesis clave: ¿La variación de vuelos argentinos durante la pandemia y el período posterior a la inmunización aumentó un 100%? Siendo la respuesta si, aumento un 124,66%. El cálculo de la variación porcentual reveló el impacto. Plasmado en un gráfico de líneas, se destacan los vuelos promedio por mes en 2020 y 2022. Observamos las fluctuaciones y las diferencias, permitiéndonos comprender cómo las condiciones cambiantes influenciaron los viajes aéreos. Un análisis técnico que ilumina las tendencias de la aviación durante dos años cruciales.

## Además, analizando las distribuciones de pasajeros en despegues y aterrizajes observé el comportamiento de los pasajeros durantes ambos años, descubrí  que en el año 2022, 199.085 personas no regresaron, representando el 4,74% del total de despegues. Mientras que en el año 2020, 33.826 personas no regresaron, conformando el 1,97% de los despegues. Este contraste sugiere una mayor retención de pasajeros en 2022, datos que son valiosos para comprender la movilidad y las tendencias en Argentina.

## Machine Learning: Predicción de cantidad de pasajeros en cada vuelo✈️📊
Luego de aplicar encoding, freature selection, freature engineer entrené 3 modelos sobre un mismo dataset para encontrar cual es el que mejor predice la cantidad de pasajeros que tendrá un vuelo, finalmente seleccioné el modelo Random Forest. Las métricas comparadas son las siguientes:
Evalúe el modelo seleccionado y ajusté sus hiper parámetros.
A continuación validé mi modelo el cual terminó prediciendo la cantidad de pasajeros en un vuelos como lo vemos en la imagen de arriba con un RMSE promedio de 1.13, es decir, que no se puede predecir con una precisión de menos de una personas, además necesitamos muchas variables para poder realizar esta predicción.

## INSIGHTS & RECOMENDA- CIONES
### Insights vuelos
- Los vuelos con horario de aterrizaje o despegue por la tarde se imponen sobre los vuelos con horario a la madrugada o mañana.
- Si bien la moda de vuelos es el día jueves, los vuelos se reparten de manera relativamente uniforme entre todos los días.
- Para todos los vuelos la compañía con más vuelos es Aerolíneas Argentinas SA.

### Insights pasajeros
- Al parecer hay un aumento en la cantidad de personas que salieron del país y no regresaron.
- Se puede predecir un aproximado de cuántos pasajeros pueden subirse a un avión.

## Recomendaciones y futuras líneas
- Si estás con dudas sobre con qué aerolínea viajar, Aerolíneas Argentinas es la opción recomendable ya que posee la


