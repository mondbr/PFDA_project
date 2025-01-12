<img src="https://beyondthestates.com/wp-content/uploads/2023/09/download.png" width=20% height=20%>

# Programming for Data Analytics - Project

by Monika Dabrowska

This repository is for the the project for the Programming for Data Analytics module in the Higher Diploma in Data Analytics course at [ATU](https://www.atu.ie/) in the winter semester of 2024/25.

It contains a project that demonstrates data analysis of the wind speed in one of the Ireland's regions - Roches Point weather station in County Cork.

## Learning Outcomes of this Project:

In this project, I aim to present my research abilities by identifying and addressing gaps in the dataset, substituting missing data with alternative values using various techniques. I use multiple methods to analyze the available data, ensuring a comprehensive approach.

The goal of the project is to prepare and analyse wind speed data while assessing the wind power potential for possibilities of a wind farm in selected area. This should demonstrate my ability to apply advanced analysis methods that might be helpful in my future work as data analyst.

## Get Started

To begin, you need Python installed on your machine. To do that, you can use the following:

**Anaconda** \

[Download](https://www.anaconda.com/download) \

The easiest way to install Python and the necessary packages for this course.

**Visual Studio Code** \

[Download](https://code.visualstudio.com) \

The editor I will use to create Python scripts.

**Git** \

[Download](https://git-scm.com) \

The software I will use to track my progress.

## Project Overview

My [analysis.ipynb](https://github.com/mondbr/PFDA_project/blob/main/analysis.ipynb) notebook contains detailed analysis of wind speed data from the Roches Point weather station in County Cork, Ireland, using a range of Python libraries:

1. **Project Introduction** : The notebook introduces the project, which involves analyzing 70 years of historical wind speed data from the Roches Point weather station, sourced from Met Éireann. The goal is to assess the wind power potential in the region, which can be helpful with planning wind energy generation.
2. **Data Exploration** :

- **Loading the Dataset** : The dataset is loaded into a Pandas DataFrame, after ignoring metadata rows. The columns are inspected to understand their structure, and data types are checked.
- **Data Cleaning** : I perform cleaning of the data, addressing missing values (including replacing spaces with NaN values), and converting data types to ensure they are appropriate for analysis (such as converting wind speed values to numeric types)

3. **Handling Missing Data** :

- Techniques such as interpolation and imputation (e.g., using Scikit-learn’s SimpleImputer and KNN Imputer) are used to fill in gaps in the data for wind speed.
- The comparison of different data-filling methods is included to assess their impact on the results.

4. **Date-Time Handling** :

* The `date` column is transformed into a datetime object, which enables better manipulation for time-based analysis (e.g., seasonal trends).

5. **Basic Statistical Analysis and Visualization** :

* Basic statistics of the wind speed (`wdsp`) column are computed to understand the tendencies, spread, and distribution.
* Visualizations are created to show trends in wind speed over time, highlighting annual and seasonal variations.

6. **Wind Energy Potential** :

* An exploration of how wind energy potential can be calculated from the historical wind speed data.
* My notebook concludes by considering how these trends can help with decisions about future wind farm installations.

### Insights:

* The dataset shows **no missing values** after cleaning, but a significant number of **zero values** in the wind speed column, that I replaced using varoius techniques.
* The **seasonal variations** in wind speed are analysed, with potential insights into optimal times for wind energy generation.
* **Data imputation methods** are explored, highlighting the importance of accurately filling gaps for robust analysis.

This project demonstrates ability to clean, preprocess, and analyse large datasets, while also addressing real-world issues like missing or incomplete data. Additionally using of Python and various libraries such as Pandas, Matplotlib, and Scikit-learn shows proficiency in data analysis and machine learning.

## Requirements

- Python 3.11.10
- `numpy`
- `matplotlib`
- `pandas`
- `scikit-Learn`
- `seaborn`
- `sklearn.impute`
- `sklearn.experimental`
- `sklearn.linear_model`

## Usage

Clone the repository and open the Jupyter notebooks for each assignment to explore the solutions.

## Technologies

* Visual Studio Code Version: 1.96
