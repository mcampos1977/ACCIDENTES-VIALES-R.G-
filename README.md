## Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial.
### Politécnico Malvinas Argentinas.
### Aprendizaje Automático.
### Alumna: Campos, Mara del Carmen.
1
## Título del Proyecto: Accidentología vial y Consumo de alcohol en la Conducción.-

### Descripción General del Proyecto y objetivo:

Este proyecto tiene como objetivo, abordar una problemática preocupante en nuestra ciudad, como es la accidentología vial y consumo de alcohol en la conducción,esto lleva a que casi a diario se produzcan accidentes de tránsito causados por conductas imprudentes de  los conductores al  subirse a su   vehículo y los cuales  se incrementa los fines de semana. A través de Técnicas de Aprendizaje Automático, se lograría ayudar al Municipio a implementar medidas preventivas más efectivas para reducir la tasa de accidentes viales en Río Grande el objetivo es aplicar Técnicas de Aprendizaje Automático para predecir accidentes de tránsito en Río Grande, identificar los riesgos por el consumo de alcohol y desarrollar un modelo Predictivo que permita reducir significativamente  la tasa de siniestros viales en nuestra ciudad;para esto se podría aplicar técnicas de clasificación , ya que el objetivo principal es predecir si ocurrirá un accidente  o si está relacionado con el consumo de alcohol 
       
## Contexto del problema y relevancia: 

Nuestra ciudad no está exenta de esta problemática, los accidentes diarios que vive Río Grande es significativo, los cuales son ocasionados por los tres factores comunes que se presentan a la hora de trasladarse en los vehículos, como factor humano, factor ambiental y factor vehículo. Estos accidentes no solo deja daños materiales, sino que ponen en riesgo la vida de los ocupantes de los vehículos y de terceros.
Por lo antes expuesto es de mucha importancia utilizar buenas técnicas de    Aprendizaje Automático para obtener una comprensión más profunda de los factores de riesgo y desarrollar soluciones que ayuden a nuestra comunidad  a disminuir este tipo de accidentes y los mismos puedan ser utilizados por la autoridades de nuestra ciudad. 

## Preguntas de investigación:

#¿Cuáles son los factores de riesgo más importantes que causan este  tipo  de accidentes en Río Grande?

#¿Es posible predecir accidentes de tránsito utilizando técnicas de Aprendizaje Automático?

#¿Qué decisiones son las más acertadas para contrarrestar esta problemática? 
       
## Herramientas utilizadas

*Librerías pandas, numpy, matplotlib, Scikit-learn

*Repositorio github, git

*Lenguaje python

*excel para ETL

*Estructura cookiecutter

*Enlace video_



## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for {{ cookiecutter.module_name }}
│                         and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── {{ cookiecutter.module_name }}                <- Source code for use in this project.
    │
    ├── __init__.py    <- Makes {{ cookiecutter.module_name }} a Python module
    │
    ├── data           <- Scripts to download or generate data
    │   └── make_dataset.py
    │
    ├── features       <- Scripts to turn raw data into features for modeling
    │   └── build_features.py
    │
    ├── models         <- Scripts to train models and then use trained models to make
    │   │                 predictions
    │   ├── predict_model.py
    │   └── train_model.py
    │
    └── visualization  <- Scripts to create exploratory and results oriented visualizations
        └── visualize.py
```

--------

