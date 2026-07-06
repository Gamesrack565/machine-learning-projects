# 🧠 Proyectos de Machine Learning: Enfoques Supervisado y No Supervisado

Este repositorio contiene implementaciones prácticas de algoritmos de Machine Learning, desarrolladas como parte de mi formación en Ingeniería en Inteligencia Artificial. El proyecto está dividido en dos ramas principales de aprendizaje automático, utilizando Python y Jupyter Notebooks para el análisis y modelado de datos.

---

## 📂 Estructura del Repositorio

```text
├── aprendizaje-supervisado/
│   ├── Proyecto_supervizado.ipynb              # Notebook con el análisis y modelo
│   └── diabetes_procesado.xml                  # Dataset tabular en formato XML
├── no-supervisado/
│   └── Proyecto_no_supervizado.ipynb           # Notebook con el modelo no supervisado
|
├── tareas/
|   ├── instrucciones_tareas
|   ├── tarea1.pdf
|   └── tarea2.ipynb
├── .gitignore
├── requeriments.txt
└── README.md
```

## 📊 1. Aprendizaje Supervisado: Análisis de Diabetes
Este proyecto utiliza un enfoque de aprendizaje supervisado con datos tabulares.

**Objetivo:** Practicar la implementación y evaluación de modelos predictivos. La meta central es alcanzar buenas métricas de desempeño mediante técnicas de limpieza y preparación de datos, aunque el procesamiento actual de este dataset específico aún se encuentra en fase de mejora para optimizar los resultados.

**Dataset:** Se incluye en el repositorio el archivo `diabetes_procesado.xml`.

**Uso:** El notebook principal procesa directamente el archivo XML local (puedes utilizar `pandas.read_xml()` para su extracción y limpieza).

---

## 🔍 2. Aprendizaje No Supervisado: IMDB Movie Reviews
Este proyecto se enfoca en el procesamiento de lenguaje natural (NLP) y técnicas de aprendizaje no supervisado aplicadas a reseñas de películas.

**Objetivo:** Practicar la construcción de modelos no supervisados. El reto principal radica en ejecutar un buen procesamiento de los datos de texto para lograr una alta separabilidad de los clústeres (agrupaciones) y, en última instancia, obtener métricas sólidas que validen el modelo.

## 🛠️ Tecnologías y Librerías Principales
* **Manipulación y Procesamiento:** Pandas, NumPy, lxml
* **Machine Learning (Scikit-Learn & Extras):** Random Forest, Regresión Logística, SVM, K-Means, DBSCAN, K-Medoids, Spectral Clustering
* **Procesamiento de Lenguaje Natural (NLP):** SpaCy, Sentence Transformers, TfidfVectorizer
* **Reducción de Dimensionalidad:** UMAP, t-SNE, PCA/SVD, NMF
* **Visualización:** Matplotlib, Seaborn

---

## 🚀 Pre-requisitos e Instalación

Para ejecutar estos notebooks en tu entorno local, asegúrate de tener instalado Python 3.12. Todas las dependencias necesarias (incluyendo modelos de NLP y algoritmos de clustering) están documentadas en el archivo `requirements.txt`.

Sigue estos pasos en tu terminal:

```bash
# 1. Clonar el repositorio
git clone [https://github.com/Gamesrack565/machine-learning-projects.git](https://github.com/Gamesrack565/machine-learning-projects.git)
cd machine-learning-projects

# 2. Crear y activar un entorno virtual (Recomendado)
python3 -m venv .venv
source .venv/bin/activate

# 3. Instalar todas las dependencias del proyecto
pip install -r requirements.txt
