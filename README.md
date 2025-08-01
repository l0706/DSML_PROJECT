# 📊 Intro to DS & ML Team Assignment - Predicting Ride-Hailing Trip Times in Chicago

### An Analysis for Introduction to Data Science and Machine Learning (Summer Semester 2025)

This project, developed for a university course on data science and machine learning, focuses on building and evaluating predictive models for ride-hailing trip durations in Chicago. Our team used real-world mobility data to explore the factors influencing trip time and to demonstrate a complete data science workflow, from data understanding to model evaluation.

### 📝 Project Overview

The primary objective of this assignment was to build and compare two predictive models to forecast trip time (in seconds) for ride-hailing services. The analysis follows the **CRISP-DM** methodology, ensuring a structured and reproducible approach to solving the problem. Key tasks included:

* **Data Cleaning and Exploration:** Handling missing values, addressing data types, and performing descriptive analysis to understand the dataset's characteristics.

* **Feature Engineering:** Creating new features from existing data, such as trip distance and time-based variables.

* **Modeling:** Building and training two distinct predictive models.

* **Evaluation:** Comparing the models' performance using appropriate metrics to determine the most effective approach.

### 📅 Milestones & To-Do List

This section reflects the original project plan and tasks.

* **Milestone 1** (25 May 2025): Data loading, cleaning, and early exploration

* **Milestone 2** (22 June 2025): Modeling and initial evaluation

* **Final Submission** (15 July 2025): Final notebook, slide deck, and reflection

#### To-Dos

* \[X] Finish exploration

* \[X] Finalize descriptive analysis

* \[X] Build the 2nd model

* \[ \] Add socio-economical features (This was an ambitious goal that we ultimately did not pursue due to time constraints)

* \[ \] Clean that (Same as above)

### 📦 Repository Structure

This repository contains all the necessary files to understand and reproduce our work:

* `Final_Submission_Notebook.ipynb`: The primary Jupyter notebook detailing every step of the CRISP-DM process, from data loading to model evaluation.

* `Final_Presentation_Slides.pdf`: A slide deck summarizing our methodology, findings, and results.

* `project_reflection.pdf`: A brief document reflecting on the team's process and key learnings.

### ⚙️ Methodology & Models

Our analysis followed the CRISP-DM framework, with a specific focus on:

#### **Data Understanding and Preparation**

We began with a raw dataset of ride-hailing trips. Key steps in this phase included:

* Descriptive statistics and data visualization to identify trends and outliers.

* Geospatial analysis using `geopandas` to visualize pickup hotspots in Chicago.

* Handling missing data and removing trips with implausible values.

#### **Modeling and Evaluation**

We developed and evaluated two predictive models to forecast trip duration:

1.  **Model 1:** A `[Linear Regression, Random Forest, etc.]` model, chosen for its `[simplicity, interpretability, etc.]`.

2.  **Model 2:** A `[Gradient Boosting, etc.]` model, selected to explore a more complex, non-linear approach.

We evaluated these models using metrics such as `[Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), R-squared]`.

### 📋 Prerequisites

To run the notebook and reproduce the analysis, you will need the following Python libraries. We worked within an Anaconda environment named `DSML_env` which you can create and activate. You can install the necessary packages using `pip` (… actually, idk):

```

pip install pandas scikit-learn numpy matplotlib seaborn geopandas contextily jupyter

```

### 👥 Team Members

* **Louis**

* **Malak**

* **Eero**

* **Lena**