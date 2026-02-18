# 📊 NovaRetail+: Optimización de Estrategia mediante Análisis A/B

[cite_start]Este repositorio contiene el análisis estadístico de un experimento A/B realizado para **NovaRetail+**, con el objetivo de validar cambios en la plataforma que impacten la **tasa de conversión** y el **valor económico (gasto)** por usuario[cite: 1, 4, 9].

## 📝 Descripción del Proyecto
[cite_start]Como analista de datos, el objetivo fue determinar si una nueva versión de la landing page (Versión B) presentaba diferencias significativas frente al control (Versión A)[cite: 3, 4, 30]. [cite_start]El análisis integra la extracción de datos, validación estadística y la generación de insights estratégicos para stakeholders[cite: 5, 22].

## 🛠️ Tecnologías y Herramientas
* **Python**: Análisis de datos y computación estadística.
* **SQL**: Extracción y filtrado de grandes volúmenes de datos.
* **Pandas & NumPy**: Limpieza y manipulación de datasets.
* **SciPy & Statsmodels**: Ejecución de pruebas de hipótesis (t-test, z-test, Chi-cuadrado).
* **Seaborn & Matplotlib**: Visualización de datos de impacto empresarial.

---

## 🚀 Metodología CIPO (Conocer, Identificar, Proponer, Optimizar)
Apliqué mi metodología estratégica para asegurar que el análisis aporte claridad al liderazgo:

### 1. **C - Conocer (Data Discovery & Quality)**
* [cite_start]Validación de la integridad del dataset: 9 columnas incluyendo `user_id`, `landing`, `converted` y `gasto`[cite: 25].
* [cite_start]Limpieza y formateo: Aseguré que la variable `gasto` solo tuviera valores mayores a cero cuando `converted = 1`[cite: 34].

### 2. **I - Identificar (Análisis Estadístico)**
* [cite_start]**Prueba t de Student**: Comparación del gasto promedio por usuario convertido para medir el valor económico[cite: 11, 19].
* [cite_start]**Prueba Z para Proporciones**: Evaluación de la tasa de conversión entre la página A y la página B[cite: 12, 19].
* [cite_start]**Prueba Chi-cuadrado**: Análisis de asociación entre la conversión y variables categóricas como `traffic_source` y `user_type`[cite: 13, 14, 38].

### 3. **P - Proponer (Insights Estratégicos)**
* [cite_start]Identificación de la página ganadora basada en la **significancia estadística (p-value)** y no solo en el promedio visual[cite: 42, 50].
* [cite_start]Traducción de resultados técnicos a recomendaciones de negocio accionables[cite: 58].

### 4. **O - Optimizar (Business Impact)**
* [cite_start]Recomendaciones sobre la segmentación de usuarios (Nuevos vs. Recurrentes)[cite: 14].
* [cite_start]Optimización del presupuesto de marketing basado en los canales de tráfico más efectivos[cite: 13, 45].

---

## 📈 Hallazgos Destacados
* [cite_start]**Calidad del Experimento**: El experimento se validó como balanceado entre las versiones A y B[cite: 39].
* [cite_start]**Conversión vs Gasto**: Se analizaron efectos diferenciales para evitar sesgos al incluir usuarios que no convirtieron[cite: 37].
* [cite_start]**Visualización**: Generación de gráficos de barras apiladas para interpretar la efectividad relativa de cada categoría[cite: 21, 57].



---

## 🤝 Conecta conmigo
Si estás buscando transformar la incertidumbre de tu negocio en decisiones basadas en datos:
* **LinkedIn**: [linkedin.com/in/alejandronieto-cipo-mentor-consultor](https://linkedin.com/in/alejandronieto-cipo-mentor-consultor)
* **Sitio Web**: [alejandronietoalvarez.com](https://alejandronietoalvarez.com)
* **Substack**: [CIPO para líderes](https://alejandronieto.substack.com/)
