# ML & DL — Repositorio de cursos

Repositorio global que reúne distintos cursos de **Machine Learning**, **Data Science** y **Deep Learning**. Cada curso vive en su propia carpeta y conserva su material, notebooks y datasets de forma independiente.

## Cursos

| Curso | Estado | Enfoque |
| --- | --- | --- |
| [`python-ds-18-dias`](./python-ds-18-dias) | Terminado | Python para Data Science: fundamentos, Pandas, NumPy, visualización, ML, Plotly y APIs. |
| [`machine-learning-y-data-science`](./machine-learning-y-data-science) | En progreso | Machine Learning aplicado a ciberseguridad (spam, malware, fraudes, URLs maliciosas). |

---

## `python-ds-18-dias` — Terminado

Curso de Udemy de 18 días, desde los fundamentos del lenguaje hasta Machine Learning y visualización avanzada. Incluye notebooks por día, proyectos prácticos y certificado.

- Temario completo y estructura: ver [`python-ds-18-dias/README.md`](./python-ds-18-dias/README.md).
- Librerías: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `plotly`, `dash`, `keras`/`tensorflow`, `requests`.
- Certificado en `python-ds-18-dias/certificado/`.

## `machine-learning-y-data-science` — En progreso

Curso de Machine Learning con enfoque en **ciberseguridad**. Actualmente cubre los módulos de introducción, librerías de DS/ML, conceptos de ML, regresión lineal y logística, consideraciones de proyectos, y una colección de casos prácticos.

- Módulos presentes: `01_introduccion`, `02_librerias_python_ds_ml`, `03_que_es_ML`, `04_regresion_lineal`, `05_regresion_logistica`, `07_creacion_proyecto_ML`.
- Casos prácticos: evaluación de resultados, SVM, árboles de decisión, Random Forests, selección de características, PCA, K-Means, DBSCAN, Naive Bayes, Isolation Forest y redes neuronales.
- Datasets asociados (NSL-KDD, TREC 2007, credit card, malware/phishing, etc.) en `machine-learning-y-data-science/datasets/`.

> Este curso aún está en desarrollo y **no debe modificarse** hasta finalizarlo.

---

## Estructura del repositorio

```
ml-dl/
├── .gitignore
├── README.md
├── python-ds-18-dias/                 # Curso terminado
│   ├── README.md
│   ├── dia02 … dia18/
│   └── certificado/
└── machine-learning-y-data-science/   # Curso en progreso
    ├── 01_introduccion … 07_creacion_proyecto_ML/
    ├── casos_practicos_machine_learning/
    └── datasets/
```

## Datasets y entornos

- **Datasets:** los datasets pesados (p. ej. `datasets/`) **no se versionan**; se excluyen vía `.gitignore` y se mantienen solo en local. Los CSV pequeños propios de los ejercicios sí se versionan.
- **Entornos virtuales:** este repositorio no incluye entornos virtuales. Si en el futuro se añade uno, `.gitignore` ya los excluye (`venv/`, `.venv/`, `env/`, etc.).
