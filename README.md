# 🛍️ NovaRetail+: Optimización de Conversión mediante Análisis A/B

![NovaRetail Logo](https://img.shields.io/badge/Business-Analysis-blue) ![Python](https://img.shields.io/badge/Python-3.9+-green) ![SQL](https://img.shields.io/badge/SQL-Data_Extraction-blue) ![Statistics](https://img.shields.io/badge/Statistics-Hypothesis_Testing-orange)

## 🎯 Objetivo del Proyecto
El objetivo principal de este proyecto es validar el impacto de cambios estratégicos en la plataforma de **NovaRetail+**. Mediante el uso de analítica avanzada y pruebas de hipótesis, buscamos determinar si las modificaciones en el diseño o flujo de usuario generan un incremento real en la tasa de conversión y en el valor económico por cliente, eliminando la incertidumbre en la toma de decisiones.

## 📊 Datasets Utilizados
Para este análisis se integraron fuentes de datos transaccionales y de comportamiento:
* **`retail_events.csv`**: Registro detallado de interacciones de usuarios y rutas de navegación.
* **`orders_retail.csv`**: Historial de compras, montos invertidos y fechas de transacción.
* **`user_segments.csv`**: Información demográfica y clasificación de lealtad de los clientes.

## 🛠️ Metodología de Análisis (CIPO)
El proyecto se ejecutó siguiendo mi metodología de consultoría estratégica:

1.  **Conocer:** Exploración profunda de los datos (EDA) para asegurar la integridad de la información y validar que los grupos del experimento estén balanceados.
2.  **Identificar:** Aplicación de pruebas de hipótesis (t-test para gasto y z-test para conversión) para detectar diferencias significativas que no sean producto del azar.
3.  **Proponer:** Traducción de hallazgos estadísticos en recomendaciones ejecutivas orientadas a mejorar la rentabilidad.
4.  **Optimizar:** Rediseño de la inversión en canales de tráfico basándose en su eficiencia relativa detectada mediante pruebas de Chi-cuadrado.

## 📈 Hallazgos Clave
* **Impacto en Gasto:** Identificación de si el ticket promedio aumentó significativamente tras las modificaciones.
* **Canales de Alta Eficiencia:** Detección de fuentes de tráfico con tasas de conversión superiores que ameritan mayor inversión.
* **Segmentación:** Descubrimiento de comportamientos diferenciados entre usuarios nuevos y recurrentes para personalizar la oferta.



## 🚀 Cómo Ejecutar el Proyecto
Para reproducir este análisis:
1. Clona el repositorio: `git clone https://github.com/tu-usuario/novaretail-ab-testing.git`
2. Asegúrate de tener instaladas las librerías: `pandas`, `scipy`, `statsmodels`, `seaborn`.
3. Ejecuta el notebook `NovaRetail_Analysis.ipynb` de forma secuencial.

---

## 🤝 Conecta conmigo
Si buscas transformar datos en decisiones estratégicas bajo el método CIPO:
* **LinkedIn**: [linkedin.com/in/alejandronieto-cipo-mentor-consultor](https://linkedin.com/in/alejandronieto-cipo-mentor-consultor)
* **Sitio Web**: [alejandronietoalvarez.com](https://alejandronietoalvarez.com)
* **Substack**: [CI PO demos avanzar](https://alejandronieto.substack.com/)
