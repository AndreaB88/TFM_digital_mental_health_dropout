# Más Allá de la Predicción: Simulaciones para Entender el Abandono en Salud Mental

**Autor:** Andrea Buenaño  
**Máster en Data Science, Big Data & Business Analytics — Universidad Complutense de Madrid (2025)**

---

## 📄 Descripción
Este Trabajo Fin de Máster analiza el **abandono en programas digitales de salud mental** 
y evalúa **estrategias de retención** mediante análisis de cohortes y simulaciones A/B.  
El objetivo es comprender patrones de deserción más allá de predicciones individuales 
y ofrecer evidencias útiles para el diseño de políticas públicas y estrategias clínicas.

---

## 📂 Contenido del repositorio
- 📑 `Memoria_TFM.pdf` → Documento principal (≤ 20 caras, sin anexos, portada ni índice).  
- 🎥 `Video_TFM.mp4` → Presentación de 5 minutos del proyecto.  
- 📁 `Anexos/` → Material complementario:
  - `Notebooks/` → Notebooks originales en Jupyter (`.ipynb`).  
  - `Notebooks_HTML/` → Notebooks exportados a HTML (EDA, cohortes, regresión logística, simulación A/B).  
  - `Data/` → Incluye:
    - Datos **brutos** descargados de Zenodo.  
    - Datos **procesados** y diccionario de variables para reproducir el análisis.  
  - `fig/` → Figuras y gráficos generados.  
  - `Dashboard/` → Archivos de Tableau, link al dashbord en memoria.  
  - `out/` → Resultados intermedios y tablas auxiliares.  
  - `requirements.txt` → Dependencias mínimas para reproducir.  

---

## ⚙️ Reproducibilidad
- Python 3.11  
- Librerías principales: `pandas`, `numpy`, `scikit-learn`, `seaborn`, `matplotlib`, `statsmodels`  
- Ejecución:
  1. Crear entorno virtual e instalar dependencias:
     ```bash
     pip install -r requirements.txt
     ```
  2. Abrir los notebooks en `Anexos/Notebooks/`.  
  3. Ejecutar en orden del 01 al 05 (EDA → cohortes → logit → simulación A/B → preparación de dashboard).  
- Los notebooks en `Anexos/Notebooks_HTML/` permiten una lectura rápida sin necesidad de ejecutar código.  

---

## 🔗 Datos
El dataset principal procede de **Zenodo** (público y con licencia de uso):  
👉 [https://zenodo.org/records/14838680](https://zenodo.org/records/14838680)  

En este repositorio se incluyen tanto los **datos brutos descargados** de Zenodo como los **datasets procesados** para asegurar la reproducibilidad completa del proyecto.  

