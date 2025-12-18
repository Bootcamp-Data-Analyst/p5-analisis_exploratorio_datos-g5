# 🐾 Veterinary Clinical Dataset — Exploratory Data Analysis (EDA)

![Logo de Mariana Rocío L. Analytics](logo.webp)


![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-1.6.2-blue?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-1.26.0-blue?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.8.0-orange?logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12.2-blue?logo=seaborn&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-Open_in_Colab-orange?logo=googlecolab&logoColor=white)

---

## 📌 Descripción del proyecto
Este proyecto consiste en un **análisis exploratorio de datos (EDA)** aplicado a un dataset clínico veterinario, con el objetivo de comprender las características demográficas y clínicas de **perros y gatos** atendidos en un contexto veterinario.

El análisis se centra en variables como **especie, edad, peso, raza, síntomas, historial médico y diagnósticos**, utilizando técnicas estadísticas descriptivas y visualizaciones para identificar patrones y relaciones relevantes.

---

## 👥 Contribuyentes y roles

| Nombre              | Rol                                                         |
|---------------------|-------------------------------------------------------------|
| Rocio Lopez Caro    | Análisis exploratorio de datos, visualización, limpieza de datos |
| Mariana Moreno Henao| Apoyo en análisis, revisión de resultados y documentación |

---

## 🎯 Objetivos del proyecto
- Comprender la distribución de **edad y peso** en perros y gatos.  
- Analizar diferencias entre **especies y razas**.  
- Explorar la relación entre **edad, peso y variables clínicas** (síntomas, historial médico y diagnósticos).  
- Identificar patrones descriptivos relevantes en un contexto veterinario.  
- Documentar un **flujo de análisis reproducible** en Python.  

---

## 🏗️ Arquitectura del pipeline
1. **Carga del dataset**  
2. **Exploración inicial**  
   - Revisión de estructura  
   - Tipos de variables  
   - Primeros registros  
3. **Limpieza de datos**  
   - Manejo de valores faltantes  
   - Corrección de inconsistencias  
4. **Análisis exploratorio**  
   - Estadísticos descriptivos  
   - Visualizaciones por especie, raza y variables clínicas  
5. **Conclusiones basadas en datos**

---

## 📁 Estructura del repositorio

├── EDA_Veterinary_Clinical_Dataset.ipynb
├── README.md


---

## 🛠️ Tecnologías y librerías usadas
- Python 3  
- pandas  
- numpy  
- matplotlib  
- seaborn  

*(Las versiones exactas pueden consultarse en el entorno de ejecución del notebook)*

---

## 🧹 Proceso de limpieza y normalización de datos
- Se revisaron valores faltantes en columnas numéricas y categóricas.  
- Se eliminaron o filtraron registros con información incompleta cuando no era posible una imputación coherente.  
- Se aseguraron tipos de datos correctos para **edad y peso**.  
- Se estandarizaron categorías textuales (**especie, raza, historial médico y síntomas**) para evitar duplicados semánticos.  

---

## 📊 Dataset final
El análisis se realizó sobre el dataset original, sin generar un archivo final separado.  
Las transformaciones y filtrados se aplican directamente en el notebook para garantizar **trazabilidad y reproducibilidad**.

**Principales columnas utilizadas:**
- `AnimalName` (especie)  
- `Breed`  
- `Age`  
- `Weight_kg`  
- `Symptoms`  
- `MedicalHistory`  
- `Diagnosis`  

---

## 📐 Nota metodológica y enfoque estadístico
El proyecto utiliza un enfoque **descriptivo y exploratorio**, basado en:  
- Estadísticos descriptivos (media, mediana, desviación estándar).  
- Comparaciones entre grupos categóricos.  
- Visualización de distribuciones y relaciones entre variables.  

> No se aplicaron modelos predictivos ni inferenciales.

---

## ▶️ Cómo ejecutar el proyecto
1. Clonar el repositorio.  
2. Abrir el archivo `EDA_Veterinary_Clinical_Dataset.ipynb` en **Jupyter Notebook** o **Google Colab**.  
3. Instalar las dependencias necesarias:
```bash
pip install pandas numpy matplotlib seaborn

Ejecutar las celdas en orden para reproducir el análisis completo.

---

## 📚 Referencias
- Dataset: **Veterinary Clinical Dataset** (Kaggle)  
- Documentación oficial de **pandas**, **seaborn** y **matplotlib**  

---

## 🔍 Conclusiones basadas en los datos
- Existen diferencias claras de **peso y edad** entre perros y gatos, visibles en las distribuciones.  
- El peso promedio varía significativamente entre razas, especialmente en perros.  
- Algunos síntomas e historiales médicos se concentran en rangos específicos de edad.  
- Los **boxplots** permiten identificar variabilidad y valores atípicos relevantes en edad y peso según condiciones clínicas.  
- Las visualizaciones facilitan la comparación entre especies y categorías médicas sin necesidad de modelos complejos.
