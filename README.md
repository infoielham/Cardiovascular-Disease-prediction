
#  Cardiovascular Disease dataset Proposal
<hr>

## Introduction: 
This study aims to create a model that uses limited patient information to extract the relationship between cardiovascular disease with other vital signe features.
## Case Problem:
Find best prediction model if the individual more likely having a cardiovascular disease or not to help accelerating the process of medication to get recovery and awareness

----

 
## Data Features & description:
- **Age**:   Objective Feature | age | int (days)
- **Height:**  Objective Feature | height | int (cm) 
- **Weight:** Objective Feature | weight | float (kg)
- **Gender:** Objective Feature | gender | categorical code
- **Systolic blood pressure:**  Examination Feature | ap_hi | int 
- **Diastolic blood pressure:** Examination Feature | ap_lo | int
- **Cholesterol:** Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal
- **Glucose:** Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal
- **Smoking:** Subjective Feature | smoke | binary 
- **Alcohol intake:** Subjective Feature | alco | binary
- **Physical activity:** Subjective Feature | active | binary 
- **Presence or absence of cardiovascular disease:** Target Variable | cardio | binary

## Size of Data:
  - Number of rows: 70000
  - Number of columns: 13
## Dataset sourec:
from Kaggle website [[Kaggle]] https://www.kaggle.com/sulianova/cardiovascular-disease-dataset

## Questions:
1. what is the percentage of cardiovascular disease per gender?
2. what is the average of having cardiovascular disease along with three kinds of cholesterol?
3. what is the relationship between glucose and cardiovascular disease?
4. what are the most generations ages along with cardiovascular disease?
5. what is the relationship between the alcoholic and smoker people along with cholesterol?


## Algorithms:
- Logistic Regression.
- XGBoost.
- Support Vector Machine.
- Random Forest.
- K-Nearest Neighbors.
- Decision Tree.
- Staking.

## Tools:
- Libraries: pandas, numpy, matplotlib, seaborn, MLextend, sklearn,XGBoost,Statsmodels.

- Softwares: Trello, GitHub, Jupyter, prize, Zoom.
<hr>


## Team Members
 - Elham Alzahrani (Leader)
 - Nouf Alkhaldi
 - Abdulrahim Alshehri
 

