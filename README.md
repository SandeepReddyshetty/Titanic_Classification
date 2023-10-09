# Titanic_Classification

The sinking of the RMS Titanic in 1912 is a tragic event that has captivated the world's imagination for over a century. This project explores the Titanic dataset and aims to answer a fundamental question: "What sorts of people were more likely to survive?"

## About the Project
This project uses machine learning techniques and data analysis to predict the likelihood of survival for passengers on the Titanic based on various attributes such as name, age, gender, socio-economic class, and more. By examining historical passenger data, we can gain insights into the factors that influenced survival rates during this historic disaster.

## Dataset
The dataset used for this project contains passenger information, including details like name, age, gender, ticket class, and whether or not the passenger survived. This data serves as the foundation for our predictive model.

| Column     | Description                                      | Values/Type                         |
|------------|--------------------------------------------------|------------------------------------|
| Survival   | Survival (0 = No; 1 = Yes)                       | Binary: 0 (No), 1 (Yes)            |
| Class      | Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)     | Categorical: 1, 2, 3               |
| Name       | Name                                             | String (Passenger's Name)          |
| Sex        | Sex                                              | Categorical: 'Male' or 'Female'   |
| Age        | Age                                              | Numeric (e.g., 22.0)               |
| SibSp      | Number of Siblings/Spouses Aboard                | Numeric (e.g., 1, 2)               |
| Parch      | Number of Parents/Children Aboard                | Numeric (e.g., 0, 1, 2)            |
| Ticket     | Ticket Number                                    | String (Ticket Number)             |
| Fare       | Passenger Fare                                   | Numeric (e.g., 7.25, 71.2833)      |
| Cabin      | Cabin                                            | String (Cabin Number)              |
| Embarked   | Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton) | Categorical: 'C', 'Q', 'S'  |


## Goal
Our primary goal is to build a predictive model that can identify patterns and relationships within the dataset to estimate the likelihood of survival for individual passengers. This model can provide valuable insights into the factors that played a role in the Titanic tragedy.

## Acknowledgments
Special thanks to the Kaggle community for providing the Titanic dataset and inspiring this project.
