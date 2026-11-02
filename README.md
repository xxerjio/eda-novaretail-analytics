# 🛒 EDA NovaRetail+ — Análisis Exploratorio de Datos

## 📌 Descripción del Proyecto
Este proyecto consiste en un **Análisis Exploratorio de Datos (EDA)** completo realizado sobre el dataset ficticio **NovaRetail+**, enfocado en entender el comportamiento de compra de los clientes, las tendencias de ingresos y la eficiencia de la inversión publicitaria en el sector de e-commerce. El objetivo principal es transformar datos transaccionales en hallazgos de negocio accionables.

## 🛠️ Tecnologías y Librerías Utilizadas
El proyecto fue desarrollado en **Python** dentro de un entorno de Jupyter Notebooks, utilizando las siguientes librerías especializadas:
- **Pandas y NumPy:** Manipulación, limpieza y estructuración de datos.
- **Seaborn y Matplotlib:** Visualización de datos (Heatmaps, Scatterplots y matrices de correlación).
- **SciPy (`scipy.stats`):** Cálculo de coeficientes estadísticos avanzados (Pearson, Spearman y `pointbiserialr`).

---

## 📊 Hallazgos Clave del Análisis

1. **Relación entre Ingresos Anuales y Compras Mensuales:**
   - **Evidencia numérica:** Correlación de Pearson $\approx 0.967$.
   - **Implicación de negocio:** Se detectó una fuerte **redundancia informacional (multicolinealidad)**. Ambas variables narran exactamente el mismo comportamiento, por lo que se recomienda prescindir de una de ellas en futuros modelos predictivos para optimizar recursos computacionales.

2. **Visitas Mensuales frente a Gasto Publicitario:**
   - **Evidencia numérica:** Correlación de Spearman $\approx 0.599$.
   - **Implicación de negocio:** Se identificó la presencia de un segmento de clientes con alta frecuencia de visitas que no reciben inversión publicitaria (tráfico orgánico), abriendo la puerta a una optimización y reasignación eficiente del presupuesto de marketing.

---

## ⚠️ Limitaciones del Estudio
- **Asociación vs. Causalidad:** Las correlaciones estadísticas describen tendencias y fuerzas de asociación, pero no confirman relaciones causa-efecto directas de manera aislada.
- **Ventana Estática:** El análisis aborda una perspectiva bivariada global, omitiendo de momento la estacionalidad temporal histórica.

---

## 🚀 Próximos Pasos
- Implementar una segmentación avanzada de usuarios (ej. modelo **RFM**: Recencia, Frecuencia y Monetización).
- Desarrollar un modelo predictivo base (regresión lineal o logística) controlando la multicolinealidad.
- Diseñar pruebas controladas (A/B testing) para validar las hipótesis de conversión en el tráfico orgánico.

---

## 👤 Autor
**Sergio**  
*Analista de Datos / Perfil Técnico enfocado en Negocios*  
[GitHub Profile](https://github.com/xxerjio)
