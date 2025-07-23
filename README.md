# ML_pipeline
```text
project_root/
├── ml_pipeline/                            # Główna logika ML podzielona na etapy
│   ├── 01_data_collection/                 # Pozyskiwanie danych (API, scraping, pliki)
│   │   └── collect_from_api.py
│   │
│   ├── 02_data_exploration/               # Eksploracyjna analiza danych (EDA)
│   │   ├── eda_visualizations.ipynb
│   │   └── summary_statistics.py
│   │
│   ├── 03_data_cleaning_preprocessing/    # Czyszczenie i przygotowanie danych
│   │   ├── missing_values.py
│   │   ├── feature_encoding.py
│   │   └── scaling_transformation.py
│   │
│   ├── 04_feature_engineering/            # Tworzenie i wybór cech
│   │   ├── feature_selection.py
│   │   ├── dimensionality_reduction.py
│   │   └── domain_features.py
│   │
│   ├── 05_modeling/                       # Trening modeli ML
│   │   ├── train_baseline_models.py
│   │   ├── train_advanced_models.py
│   │   └── model_utils.py
│   │
│   ├── 06_model_evaluation/               # Ewaluacja modeli
│   │   ├── metrics_classification.py
│   │   ├── metrics_regression.py
│   │   └── plots_confusion_auc.py
│   │
│   ├── 07_model_tuning/                   # Ulepszanie modeli (GridSearch, Optuna, itp.)
│   │   ├── grid_search.py
│   │   ├── random_search.py
│   │   ├── bayesian_optimization.py
│   │   └── learning_curves.py
│   │
│   ├── 08_model_validation/               # Walidacja, overfitting, cross-validation
│   │   ├── cross_validation.py
│   │   └── validation_curves.py
│   │
│   ├── 09_model_interpretability/         # Interpretowalność modelu (SHAP, LIME)
│   │   ├── shap_analysis.py
│   │   ├── lime_explanations.py
│   │   └── feature_importance.py
│   │
│   ├── 10_model_deployment/              # Wdrożenie (API, eksport modelu, Docker)
│   │   ├── save_model.py
│   │   ├── load_model.py
│   │   ├── flask_api.py
│   │   └── docker/
│   │       └── Dockerfile
│   │
│   └── 11_monitoring_and_maintenance/    # Monitorowanie, retraining, drift detection
│       ├── data_drift.py
│       ├── model_monitoring.py
│       └── retraining_pipeline.py
│
├── notebooks/                             # Notebooki z analizami i testami
│   └── eda.ipynb
│
├── utils/                                 # Funkcje pomocnicze i wspólne narzędzia
│   └── logger.py
│
├── config/                                # Pliki konfiguracyjne (np. YAML)
│   └── params.yaml
│
├── requirements.txt                       # Lista zależności projektu
└── README.md                              # Dokumentacja projektu
```
