<h1>Udacity Data Science Blog Project</h1>

<h2> Table of Contents</h2>

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Data Description](#data-description)
- [Project Structure](#project-structure)
- [Results](#results)
- [Blog Post](#blog-post)
- [License](#license)

## Project Overview

In this project, we will analyze data from the Stack Overflow Survey 2024 and train a model to make predictions.

Da die Umfrage sehr umfangreich ist habe ich mich auf die Analyse der Gehälter konzentriert und möchte herausfinden, welche Faktoren das Gehalt am stärksten beeinflussen.

## Installation

Das Projekt wurde in Jupyter Notebook entwickelt und erfordert die Installation von Python und verschiedenen Bibliotheken. Die erforderlichen Pakete sind in der Datei requirements.txt aufgelistet.

Die Installation der Pakete kann mit dem Befehl `pip install -r requirements.txt` durchgeführt werden.

## Data Description

Die Daten der Umfrage werden aus dem Ordner "data" geladen. 

**Da diese sehr umfangreich sind, müssen die Daten mit folgeden [Link](https://survey.stackoverflow.co/datasets/stack-overflow-developer-survey-2024.zip) von der [Seite](https://survey.stackoverflow.co/) heruntergeladen und im Order "data" gespeichert werden.**

## Project Structure

```
udacity-data-science-blog/
│
├── data/                              # Data directory
│   └── survey_results_public.csv      # Downloaded survey data
│   └── survey_results_schema.csv      # Downloaded schema data
│
├── notebooks/                         # Jupyter notebooks
│   └── data-analysis_2.ipynb          # Salary prediction modeling
│
├── models/                            # Saved models
│   ├── salary_preprocessor.pkl        # Saved data preprocessor
│   └── random_forest_salary_model.pkl # Trained Random Forest model
│
├── requirements.txt                   # Required Python packages
└── README.md                          # Project documentation
```

Make sure to download the Stack Overflow survey data from the link provided in the Data Description section and place it in the data directory.

## Results

The trained model and data preprocessor are saved in the models directory. Some Charts are part of the Jupyter-notebook.

## Blog Post

A blog post explaining the analysis and modeling process will be published on Medium.

## License

This project is licensed under the MIT License.

