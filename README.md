# 📈 Predicción de Ventas Retail con Prophet y Visualización en Power BI

Este proyecto forma parte de mi portafolio como Analista de Datos. Tiene como objetivo predecir la demanda de productos en tiendas minoristas utilizando modelos de series temporales con Prophet, y presentar los resultados en un dashboard interactivo en Power BI.

---

## 📊 Descripción del Proyecto

**Business Question:**  
¿Cómo podemos anticipar la demanda futura de productos por tienda, utilizando datos históricos de ventas para mejorar la planificación de inventario y estrategias comerciales?

**Metodología:**  
- Transformación y limpieza de datos históricos
- Entrenamiento de modelos de series temporales con Prophet para cada combinación de tienda y producto
- Evaluación del error absoluto y porcentual de las predicciones
- Exportación de resultados a CSV para análisis dinámico en Power BI

**Archivo Principal:**  
El desarrollo completo del modelado se encuentra en el notebook [`store_demand_forecast.ipynb`](store_demand_forecast.ipynb).

**Impacto:**  
Los resultados permiten visualizar la demanda futura estimada por producto y tienda, lo que ayuda a tomar decisiones más informadas sobre abastecimiento y campañas comerciales.

---

## 📌 Problemas que abordé

📌 Predecir la demanda semanal futura por tienda y producto.  
📌 Evaluar el rendimiento del modelo a través de errores absolutos y relativos.  
📌 Visualizar gráficamente las predicciones comparadas con los datos reales.  
📌 Automatizar la generación de predicciones en múltiples niveles (store + item).  
📌 Presentar resultados en Power BI para facilitar la interpretación de patrones.

---

## 🖼️ Visualizaciones del Proyecto

### 🔮 Dashboard en Power BI
¡Este proyecto incluye un dashboard interactivo que permite explorar las predicciones de ventas por tienda y producto!

![Dashboard Forecast](images/retail_forecast_dashboard.png)

---

## 🛠️ Herramientas y Librerías

- Python (pandas, numpy, Prophet)
- Jupyter Notebook
- Power BI
- Git y GitHub

---

## 📁 Estructura del Repositorio

📦 Retail-Sales-Forecasting

├── store_demand_forecast.ipynb        # Notebook con el modelado de series temporales  

├── ventas_predicciones_vs_reales.csv  # Resultados de predicción y errores para Power BI  

├── README.md                          # Documentación del proyecto  

└── Retail Forecast Dashboard.pbix     # Dashboard interactivo en Power BI

---

## 📈 Dashboard Interactivo

Los resultados del modelo se visualizaron con Power BI en un dashboard que permite explorar:

- Tendencias de ventas reales vs. predichas  

🔹 Puedes descargar el archivo aquí:  
[📁 Retail Forecast Dashboard.pbix](./Retail%20Forecast%20Dashboard.pbix)

---

## 📚 Dataset

Fuente: [Kaggle - Store Item Demand Forecasting Challenge](https://www.kaggle.com/competitions/demand-forecasting-kernels-only) 

---

## 📌 Notas Técnicas

- El dataset contiene información semanal de ventas para 10 tiendas y 50 productos.
- Se entrenó un modelo Prophet individual por combinación tienda-producto.
- Se exportaron las predicciones junto con datos reales y errores al archivo `ventas_predicciones_vs_reales.csv`, listo para usarse en Power BI.
- Todo el modelado fue realizado en un entorno local con Jupyter Notebooks.

---

## 📬 Contacto

¿Te interesa colaborar o tienes sugerencias?  
Conecta conmigo en [LinkedIn](https://www.linkedin.com/in/eduardo-alfonso-haro-villanueva-baa50a261/) o visita mi portafolio para más proyectos.

