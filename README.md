
# 📊 Análisis de Salud Mental y Rendimiento Académico en Estudiantes Universitarios

Este proyecto explora la relación entre factores de salud mental (estrés, sueño, ejercicio, búsqueda de ayuda psicológica) y el rendimiento académico (medido como GPA) en estudiantes universitarios. Fue realizado como parte de un programa intensivo de formación en análisis de datos con enfoque práctico.

---

## 📁 Dataset

- Nombre: `mental_health_students.csv`
- Fuente: Simulada con características realistas (valores nulos, outliers, errores comunes)
- Columnas incluyen:
  - `semester_gpa` (GPA del semestre)
  - `hours_of_sleep`, `exercise_freq`, `mental_health_rating`
  - `stress_level`, `seeks_help`, `gender`, `age`, etc.

---

## ⚙️ Herramientas usadas

- **Python** (pandas, seaborn, matplotlib)
- **R Markdown** para documentación original
- **Jupyter Notebook** para ejecución en Kaggle
- Visualización avanzada: `hue`, `subplots`, `heatmaps`
- Técnicas de imputación: media, mediana, moda

---

## 📌 Análisis realizados

- Limpieza de datos y normalización de valores inconsistentes
- Análisis exploratorio (EDA) con histogramas, boxplots y scatterplots
- Agrupaciones por género, estrés y búsqueda de ayuda
- Visualización cruzada con `groupby()` y `pivot_table()`
- Generación de heatmaps para visualizar combinaciones

---

## 🎯 Principales hallazgos

- Los estudiantes con bajo nivel de estrés tienden a tener mejor GPA.
- Aquellos con alto estrés pero sin buscar ayuda muestran GPA altos, lo cual puede estar relacionado con exigencia o falta de tiempo.
- El uso de `hue` y `heatmaps` permitió detectar combinaciones clave entre variables cualitativas y rendimiento académico.
- La mayoría de quienes buscan ayuda no están en el grupo de mayor estrés.

---

## 👨‍💻 Autor

**Miguel C.**  
Aspirante a Data Analyst con enfoque en análisis realista, limpieza avanzada y visualización significativa.  
Este proyecto forma parte de una ruta de especialización técnica orientada a portafolio profesional y aplicación laboral real.

---

## 🔗 Licencia

MIT License. Uso libre con fines educativos, citar autor si se reutiliza.
