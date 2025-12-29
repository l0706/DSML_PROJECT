# 📊 Intro to DS & ML Team Assignment — Predicting Ride-Hailing Trip Times in Chicago

### 🧠 An Analysis for *Introduction to Data Science and Machine Learning* (Summer Semester 2025)

This project, was developed as part of this this course, focusing on building and evaluating predictive models for ride-hailing trip durations in Chicago.
Using real-world mobility data, our team explored the factors influencing trip time and demonstrated a complete data science workflow — from data understanding and preparation to modeling and evaluation.

---

### 📝 Project Overview

The primary objective of this assignment was to **build and compare two predictive models** to forecast trip duration (in seconds) for ride-hailing services.
Our approach followed the **CRISP-DM** methodology, ensuring a structured, reproducible, and industry-standard process.

Key tasks included:

* **Data Cleaning & Exploration:** Handling missing values, correcting data types, and conducting descriptive analysis to understand the dataset’s structure and distribution.
* **Feature Engineering:** Creating additional features such as trip distance, pickup time categories, and duration-derived variables.
* **Modeling:** Building and training two distinct predictive models.
* **Evaluation:** Comparing the models’ performance using appropriate regression metrics to identify the most effective approach.

---

### 📅 Milestones & Task Tracking

This section reflects our original project timeline and task progression.

* **Milestone 1** *(25 May 2025)* — Data loading, cleaning, and initial exploration
* **Milestone 2** *(22 June 2025)* — Modeling and preliminary evaluation
* **Final Submission** *(15 July 2025)* — Final notebook, presentation slides, and reflection document

#### ✅ To-Do List Progress

* [x] Finish exploration
* [x] Finalize descriptive analysis
* [x] Build the 2nd model
* [ ] Add socio-economic features *(Initially planned but not pursued due to time constraints)*

---

### 📦 Repository Structure

This repository contains, mostly for our own comfort, all essential files required to understand, reproduce, and evaluate our work:

* **`Final_Submission_Notebook.ipynb`** — The main Jupyter notebook documenting every step of the **CRISP-DM** process, from data loading to model evaluation.
  *(Includes earlier milestone submission notebooks for reference.)*

* **`Final_Presentation_Slides.pdf`** — A concise slide deck summarizing our methodology, findings, and results.
  *(Located in the `PPT/` directory.)*

* **`project_reflection.pdf`** — A short reflective document outlining the team’s process, challenges, and key learnings.

* **Additional files:**

  * The source `.csv` dataset used for model training and evaluation
  * The official team assignment sheet
  * A 3D plot and the corresponding Python script that generated it

> All files and results are organized to ensure full reproducibility and transparency of our analytical workflow.

---

### ⚙️ Methodology & Models

Our analysis followed the **CRISP-DM** framework, as required, focusing on the stages of **Business Understanding**, **Data Understanding**, **Data Preparation**, **Modeling**, and **Evaluation**.

#### 🧩 Data Understanding & Preparation

We began with a raw dataset of ride-hailing trips in Chicago.
Key steps in this phase included:

* Performing descriptive statistics and visual analysis to identify patterns, trends, and outliers.
* Conducting geospatial analysis with `geopandas` and `contextily` to visualize pickup hotspots across the city.
* Handling missing data, removing implausible trip durations, and standardizing numerical and categorical variables for modeling.

#### 🤖 Modeling & Evaluation

We implemented and compared two predictive models to estimate **trip duration**:

1. **Model 1:** *Multiple Polynomial Linear Regression* — chosen for its interpretability and ability to capture non-linear relationships through polynomial terms.
2. **Model 2:** *Random Forest Regressor* — selected to explore a more complex, ensemble-based, and non-linear approach with the potential for higher predictive accuracy.

Both models were evaluated using standard regression metrics:
**Mean Absolute Error (MAE)**, **Root Mean Squared Error (RMSE)**, and **R² (Coefficient of Determination)**.

---

### 📋 Prerequisites

This project was developed within a **virtual environment provided by the course instructors**.
If you wish to reproduce the analysis independently, ensure that you have **Python 3.9+** installed along with the following libraries:

```bash
# Install required packages
pip install pandas scikit-learn numpy matplotlib seaborn geopandas contextily jupyter
```

Alternatively, you can create your own virtual environment (e.g., using **Anaconda**) and install the dependencies there:

```bash
conda create -n DSML_env python=3.10
conda activate DSML_env
pip install pandas scikit-learn numpy matplotlib seaborn geopandas contextily jupyter
```

> 💡 *Note:* Depending on your operating system, you may need to install additional dependencies for `geopandas` (e.g., `fiona`, `gdal`, or `shapely`).

---

### 👥 Team Members

* **Louis**
* **Malak**
* **Eero**
* **Lena**
