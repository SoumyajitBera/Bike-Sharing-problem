# **Bike Sharing Demand Forecasting using Linear Regression**

This repository focuses on predicting bike rental demand for Washington, D.C.’s Capital Bikeshare program. By analyzing historical bike sharing data and weather conditions, we build a linear regression model that forecasts daily bike rentals.

---

## **Project Overview**
- Bike sharing systems record trip durations, start/end locations, and times.
- This data, combined with weather information, helps in studying urban mobility patterns.
- Our goal is to forecast bike rental demand by applying linear regression techniques and validating model assumptions.

---

## **Repository Contents**
- **Data/**  
  Directory containing the dataset(s) used for this project.
- **Bike_sharing.ipynb**  
  Jupyter Notebook with the complete analysis, including:
  - Data preprocessing  
  - Exploratory data analysis  
  - Linear regression model building  
  - Model evaluation and interpretation
- **README.md**  
  This file, providing an overview of the project and setup instructions.
- **requirements.txt**  
  List of Python packages required to run the project.

---

## **Key Features**
- **Data Exploration & Visualization**  
  Gain insights into relationships between features (e.g., temperature, season, holidays) and bike rentals.
- **Linear Regression Modeling**  
  Build and interpret a regression model to predict bike demand.
- **Model Diagnostics**  
  Validate assumptions using residual plots, Q-Q plots, and VIF for multicollinearity checks.
- **Statistical Insights**  
  Understand the role of scaling, correlation (Pearson’s R), and categorical variables in the modeling process.

---

## **How to Run the Project**

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/SoumyajitBera/Bike-Sharing-problem.git
   cd Bike-Sharing-Problem



2. **Set Up a Virtual Environment**

* Windows <br>
    ```bash
    python -m venv .venv <br>
   .\.venv\Scripts\activate


* MAC/LINUX<br>
    ```bash
   python3 -m venv .venv <br>
   source .venv/bin/activate 

3. **Install Dependencies**
    ```bash
   pip install -r requirements.txt 

4. **Project Structure**


Bike-Sharing-Problem/
├── .venv/                   # Virtual environment folder
├── Data/                    # Dataset(s)
├── Bike_sharing.ipynb       # Jupyter Notebook with analysis
├── README.md                # This documentation
└── requirements.txt         # Python dependencies



    
