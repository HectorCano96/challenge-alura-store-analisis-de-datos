# 🛍️ Análisis de Rendimiento por Tienda – Alura Store

Este proyecto consiste en un análisis exploratorio y comparativo del rendimiento de cuatro tiendas ficticias de **Alura Store**, utilizando herramientas de análisis de datos en **Python**. El objetivo es identificar cuál tienda presenta el mejor desempeño en términos de ingresos, volumen de ventas, satisfacción del cliente y costos de envío, para así ofrecer una recomendación fundamentada sobre cuál tienda concentrar las ventas.

## 📊 Objetivos del proyecto

- Clasificar e integrar la información clave de las tiendas.
- Analizar métricas como ingresos, ventas, calificaciones y costos.
- Visualizar comparativamente los indicadores más relevantes.
- Realizar una recomendación estratégica de negocio.

## ⚙️ Enfoque y estructura del análisis

Para efectos de este ejercicio, propuse trabajar con **diccionarios** como estructura principal de datos, con el fin de facilitar la lectura, el procesamiento y la búsqueda de información mediante claves. Esta decisión tuvo como objetivo mejorar la eficiencia del código, sobre todo al escalar el análisis o agregar nuevas variables.

Aunque el uso de bloques de código reutilizables puede dificultar la apreciación inmediata de esta eficiencia, el uso de diccionarios permite integrar fácilmente:

- Más tiendas.
- Nuevas métricas o indicadores.
- Tipos de análisis distintos (por ejemplo, series temporales o análisis de categorías).

Si bien se utilizaron **listas** y **tuplas** en algunos momentos, su papel fue secundario frente a la estructura jerárquica de los diccionarios, que facilitaron el acceso rápido a los datos, favoreciendo la claridad y extensibilidad del código.

La estructura del análisis se divide en:

- **Integración de datos** mediante un diccionario principal (`info_por_tienda`) con claves por tienda.
- **Cálculo de métricas** individuales y totales (ingresos, conteo, calificaciones, costos de envío, etc.).
- **Visualización** de los datos más relevantes mediante `matplotlib`.
- **Recomendación final**, basada en una combinación de métricas de rendimiento.

## 📈 Resultados generales

Se identificaron diferencias claras entre las tiendas, destacando una de ellas (Tienda 4) por su balance entre ingresos altos y satisfacción del cliente. La recomendación se fundamentó en una evaluación integral, ponderando calidad, volumen de ventas, calificación promedio y eficiencia logística.

## 🧠 Aprendizajes clave

Este proyecto fue una oportunidad para aplicar de forma práctica conocimientos de:

- Análisis de datos con Python (diccionarios, listas, comprensión de listas, etc.)
- Visualización con `matplotlib`
- Buenas prácticas en la organización del código y comentarios
- Lógica para tomar decisiones basadas en datos

Además, desarrollé habilidades de interpretación crítica de resultados y redacción de análisis técnico con un enfoque profesional.

## 📂 Estructura del repositorio

```text
📁 alura-store-analisis/
├── alura_store.ipynb        # Análisis en Jupyter Notebook
└── README.md                # Este archivo

## 🧑‍💻 Autor

Héctor Gabriel Cano Bello
Economista | Analista de Datos | Estudiante de Ciencia de datos


## 📌 Notas finales

Este análisis está diseñado como un ejercicio formativo. Los datos son ficticios, pero el enfoque y la metodología aplican a escenarios reales de análisis de datos. Si deseas reutilizar el código o adaptarlo a tus propios datos, siéntete libre de hacerlo, dando crédito correspondiente.

Proyecto desarrollado como parte de los cursos de formación de Alura Latam y como práctica independiente de análisis de datos.
