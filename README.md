# LBBYs_CH2

Competición de Machine Learning para clasificarnoticias falsas. Análisis de datos, desarrollo de modelo y envíos a Kaggle.

Este repositorio contiene el trabajo realizado por el equipo **G03-LBBYs** 


## Objetivo

Construir un clasificador que, a partir deun statement, determine si se trata de una fake new. La métrica de evaluación es **Macro F1-Score**, lo que obliga a maximizar la precisión y el recall en ambas clases.

---

## Estructura del repositorio

```bash
LBBYs_CH2/
│
├── data/                         # Datos originales y procesados
│   └── processed/                # train_simp.csv, train_simp_preprocess.csv, test_simp.csv, test_simp_preprocess.csv
│
├── notebooks/                    # Notebooks organizados por fases
│   ├── 1_analisis/               # Análisis exploratorio de datos
│   ├── 2_preprocesado/           # Limpieza, encoding, normalización
│   ├── 3_modelado/               # Modelos: tanto de ML(SVC, KNN, Gaussian_NB, ...) como NLP (Bert, Distilbert) Con evalucion incluida
│   └── 4_documentacion/          # Tablas de autoría y valoraciones
│
├── doc/                          # Documentación final del proyecto
│   ├── memoria_equipo.pdf
│   ├── partes_individuales/
│   └── presentacion_equipo.pdf
│
├── README.md                     # Este archivo
└── .gitignore
