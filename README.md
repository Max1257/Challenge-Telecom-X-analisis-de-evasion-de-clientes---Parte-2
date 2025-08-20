# Challenge-Telecom-X-analisis-de-evasion-de-clientes---Parte-2

# 📌 Predicción de Cancelación de Clientes (Churn)

## 📖 Contexto  
La pérdida de clientes representa uno de los mayores desafíos en el sector de telecomunicaciones. Con el objetivo de anticipar la **cancelación de servicios (Churn)**, se desarrolló un proyecto de análisis y modelado predictivo que permite
identificar los factores más influyentes en la decisión de los usuarios.  

Este trabajo aplica técnicas de **Machine Learning** y análisis exploratorio para generar métricas comparativas y recomendaciones de retención.

---

## 🎯 Objetivo del Proyecto  
- Construir modelos que permitan predecir si un cliente permanecerá o cancelará el servicio.  
- Evaluar el desempeño de distintos algoritmos de clasificación.  
- Determinar qué variables impactan más en la probabilidad de cancelación.  
- Proponer estrategias basadas en los resultados obtenidos.  

---

## ⚙️ Flujo de Trabajo  
1. **Carga y preparación de datos**  
   - Normalización de variables.  
   - Codificación de columnas categóricas.  
   - Definición de variable objetivo: `Churn`.  

2. **División del dataset**  
   - Entrenamiento: 70%  
   - Prueba: 30%    

3. **Modelado**  
   - **Regresión Logística** (con estandarización de variables).  
   - **Random Forest Classifier** (sin normalización).  

4. **Evaluación de desempeño**  
   - Accuracy, Precision, Recall, F1-Score.  
   - Matriz de confusión.  
   - ROC-AUC.  

5. **Importancia de variables**  
   - Se identificaron los factores con mayor peso en la predicción del Churn.  

---

## 📊 Resultados Principales  
- **Ambos modelos** lograron un rendimiento muy alto, clasificando correctamente la mayoría de los casos.  
- **Random Forest** alcanzó métricas perfectas en los datos de prueba, lo que lo convierte en el modelo más robusto.  
- Las variables más influyentes en la predicción incluyen:  
  - **Tenure (tiempo de permanencia del cliente)**.  
  - **MonthlyCharges (cargos mensuales)**.  
  - **TotalCharges (cargos acumulados)**.  
  - **Tipo de contrato** (mensual, anual, etc.).  
  - **Servicios adicionales contratados**.  

---

## 💡 Conclusiones y Recomendaciones  
1. Los clientes con **baja permanencia (tenure bajo)** y **altos cargos mensuales** presentan mayor probabilidad de cancelar.  
2. Contratos de tipo **mensual** están más asociados a la rotación de clientes que los contratos anuales.  
3. El ofrecer **descuentos personalizados**, **programas de lealtad** o **bonificaciones por antigüedad** puede ser clave para reducir la fuga. 

---

## 🛠️ Tecnologías Utilizadas  
- **Python 3**  
- **Pandas, Numpy** (procesamiento de datos)  
- **Scikit-learn** (modelado y métricas)  
- **Matplotlib, Seaborn** (visualización)  

---
