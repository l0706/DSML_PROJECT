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
Perfect — here’s the improved and polished version of the **Prerequisites** section (and I’ve included the extra line under “Repository Structure” too).
This version sounds more natural and professional for an academic or portfolio README, clearly indicating that the environment was provided by the course instructors but still listing what’s needed for anyone reproducing the project.

### 📦 Repository Structure

This repository contains all essential files required to understand, reproduce, and evaluate our work:

* **`Final_Submission_Notebook.ipynb`** — The main Jupyter notebook documenting every step of the **CRISP-DM** process, from data loading to model evaluation.
  *(Includes earlier Milestone Submission Notebooks for reference.)*

* **`Final_Presentation_Slides.pdf`** — A concise slide deck summarizing our methodology, findings, and results.
  *(Located in the `PPT/` directory.)*

* **`project_reflection.pdf`** — A short reflective document outlining the team’s process, challenges, and key learnings.

* **Additional files:**

  * The source `.csv` dataset used for model training and evaluation
  * The course’s team assignment sheet
  * An additional 3D plot and the corresponding Python script that generated it

> All files and results are organized to ensure full reproducibility and transparency of our analytical workflow.

### ⚙️ Methodology & Models

Our analysis followed the **CRISP-DM** framework, focusing on **Business Understanding**, **Data Understanding**, **Data Preparation**, **Modeling**, and **Evaluation**.

#### **Data Understanding & Preparation**

We began with a raw dataset of ride-hailing trips in Chicago.
Key steps in this phase included:

* Performing descriptive statistics and exploratory data visualizations to identify patterns, trends, and outliers.
* Conducting geospatial analysis with `geopandas` and `contextily` to visualize pickup hotspots across Chicago.
* Handling missing values, filtering out implausible trip durations, and standardizing relevant features for modeling.

#### **Modeling & Evaluation**

We implemented and compared two predictive models to estimate **trip duration**:

1. **Model 1:** *Multiple Polynomial Linear Regression* — chosen for its interpretability and ability to capture non-linear relationships through polynomial features.
2. **Model 2:** *Random Forest Regressor* — selected to explore a more complex, ensemble-based, and non-linear approach for potentially higher predictive performance.

We evaluated both models using common regression metrics:
**Mean Absolute Error (MAE)**, **Root Mean Squared Error (RMSE)**, and **R² (Coefficient of Determination)**.

### 📋 Prerequisites

This project was developed in a **virtual environment provided by the course instructors**.
If you wish to reproduce the analysis independently, ensure that you have **Python 3.9+** and the following libraries installed.

You can install all required packages using `pip`:

```bash
# Install required packages
pip install pandas scikit-learn numpy matplotlib seaborn geopandas contextily jupyter
```

Alternatively, you may create your own virtual environment (e.g., with **Anaconda**) and install the packages there:

```bash
conda create -n DSML_env python=3.10
conda activate DSML_env
pip install pandas scikit-learn numpy matplotlib seaborn geopandas contextily jupyter
```

> Note: Depending on your system setup, you may need to install additional dependencies for `geopandas` (e.g., `fiona`, `gdal`, or `shapely`).

### 👥 Team Members

* **Louis**

* **Malak**

* **Eero**

* **Lena**