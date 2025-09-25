# Bioinformática 2025
Repo del curso de Herramientas Bioinformáticas - MSc Bio Mol @ UNMSM

## 🧬 Clase 2 - Bases de datos genómicas
Este repositorio contiene un caso de estudio diseñado para familiarizarse con bases de datos genómicas. Los estudiantes aprenderán a utilizar herramientas y bases de datos bioinformáticas para obtener data libre.

### 📘 Objetivos de la clase 2

#### 🧬 Análisis del gen alpha-amylase (Amy23) de _Solanum tuberosum_ 🥔
Este repositorio contiene un Google Colab notebook para consultar y analizar la secuencia del gen Amy23 desde bases de datos genómicas públicas (NCBI).

#### 📌 Actividades

Obtener la secuencia del gen Amy23 usando Biopython.
Guardar y analizar el archivo FASTA.
Calcular estadísticas básicas: longitud y contenido GC.
Visualizar el contenido GC con matplotlib.

#### 🚀 Cómo usar

Abre el cuaderno en Google Colab.
Ejecuta las celdas paso a paso.
Guarda tus resultados y súbelos a tu repositorio en GitHub.

#### 💻 nota: más funciones de Biopython: https://biopython.org/docs/1.76/api/Bio.Entrez.html


## 🧬 Clase 3 - Bases de datos transcriptómicas y proteómicas

Este notebook forma parte del curso de maestría Herramientas para la Bioinformática y tiene como objetivo introducir a lxs estudiantes en el uso de bases de datos públicas para el análisis de datos transcriptómicos (RNA-seq) y proteómicos (espectrometría de masas).

### 📘 Contenido del análisis
🔍 1. Acceso a datos transcriptómicos desde GEO

Se utiliza la librería GEOparse para descargar un dataset público (ej. GSE124646).
Se exploran los metadatos del estudio y las muestras disponibles.
Se extrae la matriz de expresión para análisis posteriores.

📊 2. Visualización de expresión génica

Se selecciona un gen de interés y se grafica su expresión en distintas condiciones.
Se utiliza seaborn para generar boxplots que comparan grupos experimentales.
Se discute la variabilidad entre muestras y posibles interpretaciones biológicas.

🧪 3. Exploración de datos proteómicos desde PRIDE

Se simula la carga de una tabla de abundancia proteica (por limitaciones de acceso directo).
Se visualiza la abundancia de proteínas clave entre condiciones (control vs tratado).
Se discute la diferencia entre datos transcriptómicos y proteómicos.

📈 4. Análisis comparativo entre condiciones

Se calcula la diferencia de expresión/abundancia entre condiciones para cada proteína.
Se genera una tabla resumen con los cambios observados.
Se fomenta la interpretación de resultados y generación de hipótesis.


### 🛠️ Tecnologías utilizadas

Python
Jupyter Notebook
GEOparse
pandas, matplotlib, seaborn

### 🎓 Objetivos de aprendizaje

Comprender cómo acceder y explorar bases de datos ómicas públicas.
Visualizar y analizar datos de expresión génica y proteica.
Interpretar resultados en el contexto de condiciones experimentales.
