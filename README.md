# Insurance_Cost_Prediction_System

# Insurance Cost Prediction Using Machine Learning

**Predicting individual insurance charges using demographic and health-related features with a complete machine learning workflow, including data exploration, visualization, model training, evaluation, and interactive prediction.**

---

## Project Overview

Insurance charges depend on multiple factors such as age, BMI, number of children, sex, smoking status, and region.  
This project demonstrates a **full machine learning pipeline** with a focus on **data-driven insights, model evaluation, and interpretability**.  

The project is modular, research-oriented, and suitable for undergraduate internship portfolios like **MBZUAI UGRIP**.

---

## Objectives

- Explore relationships between features and insurance costs  
- Apply Linear Regression to predict insurance charges  
- Evaluate model performance with multiple metrics  
- Analyze prediction errors and residuals  
- Implement an interactive console-based prediction module for custom inputs  
- Demonstrate clean, modular, and reusable code design  

---

## Technologies & Tools

- **Python** – Core programming  
- **NumPy & Pandas** – Data manipulation and numerical computing  
- **Matplotlib & Seaborn** – Data visualization and exploration  
- **Scikit-learn** – Machine learning models, preprocessing, pipelines  
- **Google Colab / Jupyter Notebook** – Interactive experimentation  
- **Object-Oriented Programming** – Modular, maintainable code  

---

## Data & Features

**Dataset:** Insurance dataset (CSV or Seaborn fallback)  
**Key Features:**

| Feature     | Description                          |
|------------|--------------------------------------|
| age        | Age of the individual                |
| bmi        | Body Mass Index                       |
| children   | Number of children                    |
| sex        | Male or Female                        |
| smoker     | Yes or No                             |
| region     | Geographical region                   |
| charges    | Insurance cost (target variable)      |

---

## Methodology

### 1. Data Loading & Preprocessing
- Load dataset and inspect for missing values  
- Handle categorical variables using **OneHotEncoder**  
- Scale numerical variables using **StandardScaler**  
- Modular preprocessing pipeline for reproducibility  

### 2. Exploratory Data Analysis (EDA)
- Scatter plots: Age vs Charges, BMI vs Charges  
- Boxplots: Impact of Smoking, Number of Children  
- Correlation heatmap for feature relationships  

### 3. Model Training
- **Linear Regression** using a pipeline combining preprocessing and regression  
- Train-test split (80/20)  
- Extract feature names for interpretability  

### 4. Model Evaluation
- Metrics:
  - **Mean Absolute Error (MAE)**  
  - **Root Mean Squared Error (RMSE)**  
  - **R² Score**  
- Plots:
  - Actual vs Predicted  
  - Residual analysis  
  - Prediction error histogram  

### 5. Interactive Prediction Module
- Accepts user inputs for age, BMI, children, sex, smoker, and region  
- Outputs predicted insurance charges  
- Repeatable prediction loop with error handling  

---

## Results & Insights

- **Smoking status** is the strongest predictor of insurance charges  
- **Age and BMI** also show significant correlation with costs  
- Linear Regression provides interpretable coefficients for understanding feature impact  
- Residual analysis shows model performance across ranges of predicted values  

---

## Learning Outcomes

- Gained hands-on experience with **data preprocessing** and **feature engineering**
- Built and evaluated **predictive machine learning models**
- Conducted **exploratory data analysis (EDA) and visualization**
- Understood **model errors, residuals, and limitations**
- Developed **interactive, user-friendly Python programs** for real-time predictions

---

##  Limitations

- Dataset is relatively **small** and may not generalize across all populations
- Only **Linear Regression** was implemented; other models may improve performance
- Some important **behavioral or socioeconomic factors** are not included
- Predictions are **estimates** and should not be used as medical or financial advice

---

## Future Enhancements

- Implement additional models: **Decision Trees, Random Forests, Gradient Boosting**
- Add **cross-validation** and **hyperparameter tuning** for more robust performance
- Deploy the project as a **web application** using **Streamlit** or **Flask**
- Use **SHAP values** or other interpretability methods to analyze feature impact
- Expand the **dataset** to improve model generalization and prediction accuracy

---
## Conclusion

This project demonstrates a **complete machine learning workflow** for predicting individual insurance charges based on demographic and health-related features. Through **data exploration, visualization, and model evaluation**, key factors such as **smoking status, age, and BMI** were identified as the most influential in determining insurance costs.

The project also highlights the importance of **preprocessing, feature encoding, and pipeline implementation** for robust predictive modeling. The interactive prediction module provides a **user-friendly way to obtain real-time estimates**, reinforcing practical application skills.

**Key Takeaways:**
- Developed proficiency in **Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn**
- Gained hands-on experience in **data preprocessing, feature engineering, and model evaluation**
- Practiced **error analysis and interpretation of predictive models**
- Built **modular and scalable code**, laying the foundation for more advanced machine learning projects

This project serves as a strong demonstration of **analytical thinking, problem-solving, and applied AI skills**, making it highly relevant for research-oriented internships such as **MBZUAI UGRIP**.


