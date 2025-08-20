# ChallengeTelecomX2
# Desafío Telecom X - Parte 2

Este proyecto forma parte del desafío de análisis de datos de Telecom X. El objetivo es **predecir la cancelación (churn) de clientes** utilizando técnicas de estadística, machine learning y análisis exploratorio de datos.

---

## 📂 Contenido del repositorio

- `TelecomX_Data.json` → Dataset tratado y limpio.
- `notebook.ipynb` → Notebook de trabajo con todo el análisis, modelado y conclusiones.
- `README.md` → Este archivo de documentación.

---

## 🛠 Tecnologías y librerías utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib & Seaborn (visualización)
- Scikit-learn (preprocesamiento, modelos y evaluación)
- Jupyter/Google Colab

---

## 🔍 Objetivos del proyecto

1. **Preparación de los datos:** limpieza, estandarización y codificación de variables categóricas.
2. **Exploración de datos:** análisis de correlación, visualización de variables y proporción de churn.
3. **Modelado predictivo:**  
   - Modelos creados: Regresión Logística y Random Forest.  
   - Evaluación con métricas: Accuracy, Precision, Recall, F1-score y matriz de confusión.
4. **Interpretación de resultados:** identificación de variables más relevantes y análisis de factores que afectan la cancelación.
5. **Conclusiones y estrategias de retención:** propuestas basadas en los insights obtenidos de los modelos.

---

## 📈 Resultados principales

- Los modelos identifican que las variables más influyentes en la cancelación son:  
  - `tenure` (tiempo del cliente en la empresa)  
  - `Charges.Total` y `Charges.Monthly` (gasto total y mensual)  
  - Tipo de contrato y servicios contratados (`Contract`, `InternetService`, `OnlineSecurity`)  

- El modelo con mejor desempeño (según F1-score) fue **Random Forest**, mostrando buena capacidad de generalización y predicción del churn.

---

## 💡 Estrategias sugeridas para retención de clientes

1. Incentivos y promociones para clientes nuevos o con poco tiempo de contrato.  
2. Seguimiento y atención personalizada a clientes con gastos elevados.  
3. Optimización y mejora de servicios críticos (Internet, seguridad online).  
4. Implementación de alertas de riesgo de churn usando el modelo predictivo.

---

## 📄 Notas

- Todos los análisis y modelos están documentados en el notebook de Colab.  
- El dataset utilizado se encuentra preprocesado para garantizar consistencia en las variables y calidad de los modelos.

---

## 🔗 Referencias

- [Documentación oficial de Pandas](https://pandas.pydata.org/docs/)
- [Documentación de Scikit-learn](https://scikit-learn.org/stable/documentation.html)
- [Documentación de Matplotlib](https://matplotlib.org/stable/contents.html)
