# Modelo Predictivo de Churn - Telecom X

## 📝 Descripción del Proyecto
Este proyecto es el cierre de mi especialización y se enfoca en el uso de **Inteligencia Artificial** para predecir qué clientes tienen mayor probabilidad de cancelar sus servicios. Pasamos de un análisis descriptivo a un modelo capaz de anticipar el abandono con alta precisión.

## 🤖 Modelos de Machine Learning
Para este desafío, entrenamos y comparamos dos algoritmos potentes:
1. **Regresión Logística:** Utilizada para entender la influencia directa de variables como el costo mensual y el tipo de contrato.
2. **Random Forest (Modelo Ganador):** Elegido por su capacidad de manejar relaciones complejas entre datos, logrando una **Exactitud del 85%** y un **Recall del 86%**.



## 🛠️ Tecnologías y Técnicas
* **Python & Pandas:** Limpieza y transformación de datos.
* **Scikit-Learn:** División de datos (Train/Test Split), escalado de variables y entrenamiento de modelos.
* **Imbalanced-Learn:** Balanceo de clases para evitar sesgos en la predicción.
* **Matplotlib & Seaborn:** Visualización de matrices de correlación y de confusión.

## 🎯 Hallazgos y Estrategia de Negocio
* **Factor Crítico:** Los clientes con contratos **mes a mes** y servicios de **Fibra Óptica** presentan el mayor riesgo de fuga.
* **Lealtad:** La probabilidad de abandono cae drásticamente después de los primeros **20 meses** de antigüedad.
* **Propuesta:** Implementar un plan de migración de contratos mensuales a anuales y reforzar el soporte técnico en los primeros 6 meses de vida del cliente.
