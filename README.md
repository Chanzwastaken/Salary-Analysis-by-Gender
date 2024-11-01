# Salary Analysis by Gender

## Introduction
The gender pay gap is a significant issue affecting various industries globally. This project uses data analysis and linear regression techniques to explore the disparity in salaries between male and female employees. 

The analysis is performed on a dataset that contains gender, age, years of experience, education level, and salary information.

## Files in the Repository
- **Salary_Data.csv**: The dataset containing information on gender, age, experience, education level, and salary.
- **SalaryAnalysisGender.ipynb**: Jupyter notebook that contains the code to load, clean, visualize, and analyze the dataset.

## Dataset
The dataset used in this project is sourced from Kaggle:  
[Salary Data by Gender](https://www.kaggle.com/datasets/mohithsairamreddy/salary-data/data)

## Project Overview
1. **Data Loading**: Load the dataset using pandas.
2. **Data Cleaning**: Filter and clean the data, focusing on 'Male' and 'Female' genders, and remove missing data.
3. **Exploratory Data Analysis (EDA)**: Use Seaborn and Matplotlib to visualize the salary distribution by gender.
4. **Linear Regression**: Apply a linear regression model to explore the relationship between salary and factors like age, experience, and education level.
5. **Model Evaluation**: Evaluate the regression model using the R-squared value.

## How to Run the Project
1. Clone the repository:
    ```bash
    git clone https://github.com/Chanzwastaken/Salary-Analysis-by-Gender.git
    ```
2. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Open and run the Jupyter notebook:
    ```bash
    jupyter notebook SalaryAnalysisGender.ipynb
    ```

## Results
- The linear regression model provides insights into how factors like age, years of experience, and education level influence salary.
- The R-squared value of the model indicates that approximately 77% of the variance in salary is explained by the model.
![download](https://github.com/user-attachments/assets/7480f858-8332-4db3-aef7-4e34eb70633b)
![download](https://github.com/user-attachments/assets/79bbe609-5117-4763-95a8-3c8df44ec6f3)


## Blog Post
For a detailed explanation and breakdown of the project, check out the blog:  
[Salary Analysis by Gender with Linear Regression](https://medium.com/@chandraabdullah00/salary-analysis-by-gender-with-linear-regression-analysis-0aab0bf912b6)

## License
This project is licensed under the MIT License.
