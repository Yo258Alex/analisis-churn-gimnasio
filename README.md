# 🏋️‍♂️ Predicción y Análisis de Abandono de Clientes (Gym Fitness)

## 📌 Descripción del Proyecto
Este proyecto forma parte de mi portafolio como **Analista de Datos Junior**. El objetivo principal fue analizar los patrones de cancelación de socios en la cadena de gimnasios *Model Fitness*, utilizando técnicas de análisis exploratorio de datos (EDA) y modelos de Machine Learning supervisado para predecir qué clientes tienen mayor probabilidad de abandonar el servicio, permitiendo a la empresa enfocar estrategias de retención.

---

## 🛠️ Tecnologías y Librerías Utilizadas
* **Lenguaje:** Python 3.x
* **Manipulación y Limpieza:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn
* **Machine Learning & Estadísticas:** Scikit-Learn (Regresión Logística, Random Forest, K-Means Clustering)
* **Entorno:** Jupyter Notebook, Git / GitHub

---

## 📊 Metodología y Fases del Proyecto

1. **Preprocesamiento y Limpieza de Datos:** 
   * Revisión de valores nulos, duplicados y normalización de tipos de datos de las variables de los socios (edad, distancia al gimnasio, uso de servicios adicionales, tipo de membresía, etc.).
2. **Análisis Exploratorio de Datos (EDA):**
   * Comparación de distribuciones entre los clientes que cancelaron (`churn = 1`) y los que se mantuvieron activos (`churn = 0`).
   * Creación de gráficos de correlación y visualizaciones para identificar variables clave asociadas a la baja (como la duración de la membresía y la frecuencia de asistencia).
3. **Modelado Predictivo y Clasificación:**
   * Entrenamiento de modelos de clasificación (**Regresión Logística** y **Random Forest**) para predecir la probabilidad de abandono individual.
   * Evaluación de métricas de rendimiento (Accuracy, Precision, Recall y ROC-AUC).
4. **Segmentación de Clientes (Clustering):**
   * Estandandarización de características y aplicación de K-Means para agrupar a los usuarios en clústeres e identificar perfiles de riesgo específicos.

---

## 💡 Principales Hallazgos e Impacto en el Negocio

* **Identificación del Segmento Crítico:** Se determinó que el **Clúster 3** concentra el mayor riesgo de abandono (alcanzando una tasa de churn significativamente alta del **31.55%**), caracterizado por una menor frecuencia de visitas y contratos de corta duración.
* **Factores Clave de Retención:** Se comprobó estadísticamente que la cercanía al gimnasio, la contratación de membresías de mayor duración y la asistencia regular a clases grupales reducen drásticamente la probabilidad de cancelación.
* **Propuesta de Valor:** Con estos resultados, la gerencia de marketing y operaciones puede diseñar campañas de retención automatizadas dirigidas exclusivamente a los perfiles de los clústeres de alto riesgo antes de que decidan cancelar su suscripción.

---

📫 Contacto
Autor: Alejandro Cuahutle Saldaña

LinkedIn: [linkedin.com/in/alejandro-cuahutle](https://www.linkedin.com/in/alejandro-cuahutle/)

Correo: ing.meca.acs@gmail.com
