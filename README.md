# ClassicML

`ClassicML` - это исследовательский проект по классическому машинному обучению. Репозиторий собран как набор Jupyter-ноутбуков, где каждая папка посвящена отдельному направлению, а каждый ноутбук - конкретному алгоритму или методу. Проект подходит для изучения теории, практических экспериментов и сравнения разных подходов между собой.

## О проекте

Внутри репозитория собраны ноутбуки по основным темам Classic Machine Learning:

- `Classification/` - методы классификации.
- `Regression/` - алгоритмы регрессии.
- `Clasterization/` - методы кластеризации.
- `DimensionalityReduction/` - методы снижения размерности и визуализации данных.
- `Ansamble/` - ансамблевые методы.

Названия папок сохранены в том виде, в котором они используются в проекте.

## Структура проекта

```text
ClassicML/
|-- README.md
|-- Ansamble/
|   |-- adaboost.ipynb
|   |-- gradient_boosting_ensemble.ipynb
|   `-- random_forest.ipynb
|-- Classification/
|   |-- decision_tree_classification.ipynb
|   |-- gradient_boosting_classification.ipynb
|   |-- knn_classification.ipynb
|   |-- logistic_regression.ipynb
|   |-- naive_bayes.ipynb
|   `-- svm_classification.ipynb
|-- Clasterization/
|   |-- dbscan.ipynb
|   |-- gmm_clustering.ipynb
|   |-- hdbscan.ipynb
|   `-- kmeans.ipynb
|-- DimensionalityReduction/
|   |-- LDA.ipynb
|   |-- PCA.ipynb
|   |-- TSNE.ipynb
|   `-- UMAP.ipynb
`-- Regression/
    |-- decision_tree_regression.ipynb
    |-- gradient_boosting_regression.ipynb
    |-- knn_regression.ipynb
    `-- lin_pol_regression.ipynb
```

## Кратко по разделам

- `Ansamble/` - ноутбуки по ансамблевым моделям: `AdaBoost`, `Random Forest`, `Gradient Boosting`.
- `Classification/` - задачи предсказания классов: логистическая регрессия, `KNN`, `SVM`, наивный Байес, деревья решений и градиентный бустинг.
- `Clasterization/` - методы поиска групп в данных без разметки: `KMeans`, `DBSCAN`, `HDBSCAN`, `GMM`.
- `DimensionalityReduction/` - методы уменьшения числа признаков и визуализации многомерных данных: `PCA`, `LDA`, `t-SNE`, `UMAP`.
- `Regression/` - алгоритмы для предсказания непрерывных значений: линейная и полиномиальная регрессия, `KNN`, деревья решений и градиентный бустинг.

## Назначение проекта

Этот репозиторий можно использовать как:

- исследовательскую базу для экспериментов с алгоритмами;
- учебный набор ноутбуков по разным темам классического ML;
- удобную точку входа для сравнения методов на практике.