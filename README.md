# Panic Attack Data Analysis

This repository contains a data analysis project focused on understanding the factors and triggers associated with panic attacks. The analysis is performed in a Jupyter Notebook (`data.ipynb`) using Python and popular data science libraries.

## Project Goal

The primary goal of this project is to explore a dataset of individuals, examining the relationships between demographic information (Age, Gender), lifestyle habits (Caffeine Intake, Exercise, Sleep), medical history, and the frequency and severity of panic attacks.

## Dataset

The `panic_attack_dataset.csv` file includes the following key columns:
* **Demographics:** `Age`, `Gender`
* **Panic Attack Details:** `Panic_Attack_Frequency`, `Duration_Minutes`, `Panic_Score`
* **Triggers & History:** `Trigger`, `Chest_Pain`, `Medical_History`
* **Lifestyle Factors:** `Caffeine_Intake`, `Exercise_Frequency`, `Sleep_Hours`, `Alcohol_Consumption`, `Smoking`

## Tools Used

* **Python:** The core language for the analysis.
* **Pandas:** For data loading, cleaning, and manipulation.
* **Matplotlib & Seaborn:** For data visualization to identify trends and correlations.
* **Jupyter Notebook:** For organizing and presenting the analysis.

## Analysis Highlights

This notebook covers:
* **Data Cleaning:** Handling any missing values and ensuring data types are correct.
* **Exploratory Data Analysis (EDA):** Visualizing distributions and relationships.
* **Insight Generation:** Answering questions like:
    * What are the most common triggers?
    * How do lifestyle factors like sleep and caffeine correlate with `Panic_Score`?
    * Are there differences in panic attack frequency across different genders or age groups?
