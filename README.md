# Categorical-Outcome---Heart-Disease
This peoject was done on the dataset obtained from Kaggle
Created a model that predicts whether a person will suffer from heart disease or not based on other health factors provided
## Code and Resources Used
Python Version: 3.7 <br />
Packages: pandas, numpy, sklearn, matplotlib, seaborn, statsmodel
## Project Methodology
- After importing all the relevant libraries, the CSV file was imported to the Jupyter Notebook
- Basic exploration and visualization of the data was done
- Missing values of "cholestrol" were replaced by median values
- Data was mapped by using dummy variables
- The data was split into train and test data with a split ratio of 75/25
- Logistic regression was performed on both test and train data and confusion matrix was generated for both
## Outcome
- The model has an accuracy of 84%
- The misclassification rate is 15%
