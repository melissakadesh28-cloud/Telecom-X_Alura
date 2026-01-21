
# 📊 Telecom-X_Alura

**Análisis de evasión de clientes en telecomunicaciones usando Python, Pandas y visualizaciones con Seaborn.**

---

## 🏅 Insignias
![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-green)
![Estado](https://img.shields.io/badge/Estado-Finalizado-brightgreen)

---

## 📑 Índice
1. [Descripción del Proyecto](#descripción-del-proyecto)  
2. [Notebook Principal](#notebook-principal)  
3. [Demostración de Resultados](#demostración-de-resultados)  
4. [Tecnologías Utilizadas](#tecnologías-utilizadas)  
5. [Acceso al Proyecto](#acceso-al-proyecto)  
6. [Licencia](#licencia)  
7. [Autora](#autora)  

---

## 📖 Descripción del Proyecto
Este proyecto analiza la **evasión de clientes (churn)** en una empresa de telecomunicaciones.  
Se aplican técnicas de limpieza, transformación y visualización de datos para identificar patrones que explican el abandono de clientes.  
El objetivo es generar insights que ayuden a mejorar la retención y tomar decisiones estratégicas basadas en datos.

---

## 📓 Notebook Principal
El archivo [`MR_TELECOMX.ipynb`](MR_TELECOMX.ipynb) contiene:

- Proceso ETL sobre el dataset original  
- Creación de variables derivadas como `services_Count`  
- Matriz de correlación entre variables clave  
- Visualizaciones con Seaborn (scatterplots, boxplots, histogramas)  
- Análisis exploratorio de churn por tipo de cliente y servicios contratados

---

## 🎯 Demostración de Resultados
Ejemplos de visualizaciones generadas:

- 📌 **Matriz de correlación**: muestra relaciones entre cargos mensuales, servicios y churn  
- 📌 **Boxplots**: comparan distribuciones entre clientes que se quedan y los que se van  
- 📌 **Scatterplots**: revelan patrones entre variables numéricas y evasión  

*(Puedes agregar capturas de pantalla aquí si lo deseas)*

---

## 🛠 Tecnologías Utilizadas
- **Lenguaje:** Python 3.10  
- **Librerías:** Pandas, NumPy, Matplotlib, Seaborn  
- **Entorno:** Google Colab / Jupyter Notebook  

---

## 🔑 Acceso al Proyecto
Para ejecutar el proyecto localmente:

```bash
git clone https://github.com/melissakadash28-cloud/Telecom-X_Alura.git
cd Telecom-X_Alura
pip install -r requirements.txt
