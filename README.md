# 🚕 Predicción de pedidos de taxis en aeropuertos  

## 📝 Descripción del proyecto  
La compañía **Sweet Lift Taxi** ha recopilado datos históricos sobre pedidos de taxis en los aeropuertos.  
Para atraer a más conductores durante las horas pico, es necesario **predecir la cantidad de pedidos de taxis para la próxima hora**.  

Este proyecto tiene como objetivo construir un modelo de **machine learning** que permita anticipar la demanda de taxis y mejorar la asignación de recursos.  

---

## 📊 Problema que resuelve  
Sin un modelo predictivo, resulta difícil gestionar la oferta de taxis frente a la variabilidad de la demanda, especialmente en horarios de alta congestión.  
Con un modelo confiable, la empresa puede:  
- Anticipar la demanda en la próxima hora.  
- Optimizar la disponibilidad de conductores.  
- Mejorar la experiencia del cliente reduciendo tiempos de espera.  

---

## 📏 Métrica del modelo  
El rendimiento de los modelos se evaluó utilizando la métrica **RMSE (Root Mean Squared Error / Error cuadrático medio)**.  
- Esta métrica mide la diferencia entre los valores reales y los valores predichos.  
- Mientras más bajo sea el RMSE, mayor será la calidad de la predicción.  

En este proyecto se obtuvo un **RMSE mínimo de 25.56** utilizando **Regresión Lineal**, muy por debajo del límite establecido de **48**.  

---

## 🛠️ Tecnologías usadas  
- **Python**  
- **Pandas / NumPy** → manipulación y análisis de datos  
- **Matplotlib / Seaborn** → visualización de datos  
- **Scikit-Learn** → entrenamiento, validación y ajuste de modelos de machine learning  

---

## ▶️ Cómo ejecutarlo  
1. Clonar este repositorio:  
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
Instalar las dependencias necesarias:

bash
Copy code
pip install -r requirements.txt
Abrir el proyecto en Jupyter Notebook o un IDE compatible.

Ejecutar los notebooks en este orden:

01_preprocesamiento.ipynb → limpieza y preparación de datos.

02_exploracion_datos.ipynb → análisis visual y estadístico.

03_modelos_prediccion.ipynb → entrenamiento y evaluación de modelos.

📚 Conclusiones generales
La mayoría de los modelos entrenados alcanzaron valores de RMSE menores a 48, cumpliendo con los requisitos del proyecto.

El modelo de Regresión Lineal obtuvo el mejor desempeño (RMSE = 25.56), destacando por su precisión y velocidad de ejecución.

Este modelo constituye una solución óptima para predecir la demanda horaria de taxis, lo que permitirá a la compañía Sweet Lift Taxi optimizar su servicio en aeropuertos y mejorar la satisfacción de sus clientes.
