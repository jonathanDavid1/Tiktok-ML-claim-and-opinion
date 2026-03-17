# 🎬 TikTok Claims Classification Model
## Mitigación de Desinformación mediante Machine Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-2C2C2C?style=for-the-badge&logo=xgboost&logoColor=white)
![Random Forest](https://img.shields.io/badge/Random%20Forest-5C5C5C?style=for-the-badge)

### 📌 Descripción del Proyecto
Este proyecto forma parte del **Google Advanced Data Analytics Professional Certificate**. El objetivo principal es construir un modelo de clasificación binaria para determinar si un video de TikTok contiene una **afirmación (claim)** o una **opinión**. 

Esta herramienta permite a la plataforma priorizar los reportes de usuarios y moderar de manera más eficiente el contenido que podría contener desinformación.

### 🎯 Objetivos Técnicos
- **Análisis Predictivo:** Clasificar videos automáticamente para reducir la carga de moderación manual.
- **Comparación de Modelos:** Evaluación de rendimiento entre *Random Forest* y *XGBoost*.
- **Ingeniería de Características:** Extracción de insights basados en el comportamiento de visualización y metadatos del autor.

### 🚀 Metodología PACE
El desarrollo se ejecutó bajo el marco de trabajo **PACE**:

1.  **P (Plan):** Exploración inicial del dataset y definición de la variable objetivo (`claim_status`).
2.  **A (Analyze):** Análisis exploratorio (EDA) y visualización de distribuciones de vistas, compartidos y likes.
3.  **C (Construct):** Codificación de variables categóricas, manejo de desbalanceo de clases y entrenamiento de modelos complejos.
4.  **E (Execute):** Validación mediante matrices de confusión y reporte de métricas (Precision, Recall, F1).

### 🧪 Stack Tecnológico
- **Modelado:** Random Forest, XGBoost, Logistic Regression.
- **Procesamiento:** Pandas, NumPy.
- **Métricas:** Scikit-learn (GridSearchCV, Confusion Matrix).
- **Visualización:** Matplotlib, Seaborn.

### 💡 Resultados Clave
El modelo final (XGBoost/Random Forest) demostró una alta capacidad de generalización, permitiendo identificar contenido sensible con un margen de error mínimo, optimizando así los flujos de trabajo de seguridad de la plataforma.

---
📜 **Certificación:** Google Advanced Data Analytics (Course 6 - Machine Learning).  
💼 **Perfil:** AI Developer & Data Analyst.
