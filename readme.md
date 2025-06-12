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

```bash
.
├── data
│   ├── Load Data_see readme 
│   ├── survey_results_public.csv    # needs to be downloaded
│   └── survey_results_schema.csv    # needs to be downloaded
├── models
│   ├── random_forest_salary_model.pkl
│   └── salary_pipeline.pkl
├── notebooks
│   └── data-analysys_2.ipynb        # Jupyter Notebook
├── plots
│   ├── 2.1_distribution_of_annual_compensation.png
│   ├── 2.2_distribution_of_annual_compensation_without_outliers.png
│   ├── 2.3_log_distribution_of_annual_compensation_with_salary_references.png
│   ├── 3.1_salary_by_years_of_professional_coding_experience.png
│   ├── 3.2_salary_by_education_level.png
│   ├── 3.3_salary_by_country_top_15_countries.png
│   ├── 4.1_salary_distributions_before_and_after_cleaning.png
│   ├── 5.1_random_forest_predicted_vs_actual_salary.png
│   ├── 5.2_tuned_random_forest_actual_vs_predicted_salary.png
│   ├── 5.3_top_20_feature_importances_random_forest.png
│   ├── 5.4_feature_importance_by_category.png
│   └── boxplot_anatomy.png
├── readme.md                       # this file
└── requirements.txt                       
```

Make sure to download the Stack Overflow survey data from the link provided in the Data Description section and place it in the data directory.
## Results

The trained model and data preprocessor are saved in the models directory. Some Charts are part of the Jupyter-notebook.

## Blog Post

A blog post explaining the analysis and modeling process is published on [Medium](https://medium.com/@t.lucas_2982/salaries-in-the-tech-industry-what-influences-your-income-4209ba01739c).
## License

This project is licensed under the MIT License.
