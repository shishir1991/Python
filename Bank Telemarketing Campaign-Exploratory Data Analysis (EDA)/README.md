#Comprehensive EDA of Bank Telemarketing Campaign Data

## Table of Contents
1. [Overview](#overview)
2. [Files in the Repository](#files-in-the-repository)
3. [Project Objective](#project-objective)
4. [Steps of Analysis](#steps-of-analysis)
   1. [Understanding the Dataset](#understanding-the-dataset)
    2. [Descriptive Statistics](#descriptive-statistics)
    3. [Univariate Analysis](#univariate-analysis)
    4. [Bivariate Analysis](#bivariate-analysis)
    5. [Categorical Variables Analysis](#categorical-variables-analysis)
    6. [Temporal Analysis](#temporal-analysis)
    7. [Feature Engineering](#feature-engineering)
    8. [Correlation Analysis](#correlation-analysis)
    9. [Outlier Detection and Handling](#outlier-detection-and-handling)
5. [Results](#results)
6. [Recommendations](#recommendations)
7. [Usage](#usage)
8. [Contributing](#contributing)
9. [License](#license)
10. [Contact](#contact)

## Overview
This repository contains the project "Bank Telemarketing EDA Insights," which involves conducting an Exploratory Data Analysis (EDA) on a dataset related to a bank's telemarketing campaign for term deposits. The aim is to enhance the bank's revenue by improving the positive response rate to the campaign through detailed data analysis and insights.

## Files in the Repository
- [Problem Statement.pdf](./Problem%20Statement.pdf): Contains the detailed problem statement and project requirements.
- [bank_marketing.csv](./bank_marketing.csv): The dataset used for the EDA, containing various features related to the bank's telemarketing campaign.
- [Attribute details.xlsx](./Attribute%20details.xlsx): Provides detailed descriptions of the attributes (columns) present in the dataset.
- [Exploratory Data Analysis (EDA)-Jupyter File.ipynb](./Exploratory%20Data%20Analysis%20(EDA)-Jupyter%20File.ipynb): The final Jupyter Notebook containing the complete EDA process, visualizations, and insights.

## Project Objective
The primary objective is to perform an end-to-end EDA on the bank's telemarketing campaign dataset to identify patterns and provide actionable insights for improving the campaign's success rate. The analysis includes examining customer demographics, temporal trends, and other influential factors.

## Steps of Analysis
1. **Understanding the Dataset**:
   - Load and scrutinize the dataset to comprehend its structure, including columns and data types.
   - Inspect for missing values, outliers, or data inconsistencies.
  
![image](https://github.com/user-attachments/assets/4f77744a-b02a-4620-ae26-3b6257cf7cbb)
  
2. **Descriptive Statistics**:
   - Derive summary statistics (mean, median, standard deviation) for relevant columns.
   - Examine the distribution of the target variable indicating responses to the term deposit campaign.

![image](https://github.com/user-attachments/assets/5a676956-9366-4148-a724-9e7151613d2e)

3. **Univariate Analysis**:
   - Examine the distribution of individual key features such as age, balance, and call duration.
   - Use visual aids like histograms, box plots, and kernel density plots to discern patterns and outliers.

![image](https://github.com/user-attachments/assets/fd759f90-8d20-4191-8a4d-513479652905)

![image](https://github.com/user-attachments/assets/f01b57e5-2fb6-4611-93c2-af895f9ac850)

4. **Bivariate Analysis**:
   - Evaluate the relationship between independent variables and the target variable.
   - Analyze how features like age, job type, education, and marital status associate with the success of the term deposit campaign using visualizations like bar charts, stacked bar charts, and heatmaps.
  
5. **Categorical Variables Analysis**:
   - Investigate the distribution of categorical variables such as job type, education, and marital status.
   - Assess the impact of these categorical variables on the campaign's success through visualizations like bar charts.
 
![image](https://github.com/user-attachments/assets/026d4462-abcf-4eeb-bc98-c115fd2eaa9c)

6. **Temporal Analysis**:
   - Investigate temporal patterns in the success of the campaign over time.
   - Analyze if specific months or days exhibit superior campaign performance.

![image](https://github.com/user-attachments/assets/b0bbc72b-e26b-4957-bb06-2ffedea08bc3)

7. **Feature Engineering**:
   - Introduce new features that may enhance prediction, such as creating age groups or income categories.
   - Apply encoding techniques to transform categorical variables if necessary.

8. **Correlation Analysis**:
   - Examine correlations between independent variables to identify multicollinearity.
   - Evaluate how correlated features may influence the target variable.
   
![image](https://github.com/user-attachments/assets/16d87113-d9ae-4ee8-b97a-89a528ad6b7e)

9. **Outlier Detection and Handling**:
   - Identify and rectify outliers that could impact the analysis and predictions.

## Results
- **Descriptive Statistics**:
  - The average age of customers is 40 years, with a standard deviation of 10 years.
  - The balance feature shows high variability with several outliers.

- **Univariate Analysis**:
  - The age distribution is right-skewed, with most customers aged between 30 and 50 years.
  - The call duration has a significant impact on the campaign's success.

- **Bivariate Analysis**:
  - Younger customers and those with higher balances are more likely to subscribe to term deposits.
  - Customers with secondary or tertiary education levels show higher subscription rates.

- **Categorical Variables Analysis**:
  - Job type and marital status significantly influence the campaign's success.
  - Married individuals and those in management or technician jobs are more likely to subscribe.

- **Temporal Analysis**:
  - The campaign is more successful in the last quarter of the year.
  - Fridays and Wednesdays show higher subscription rates.

- **Correlation Analysis**:
  - There is a high correlation between age and balance.
  - Call duration has a strong positive correlation with subscription success.

## Recommendations
Based on the analysis, actionable insights are provided to enhance the bank's positive response rate. These recommendations consider factors such as customer demographics, campaign timing, and communication strategies.

## Usage
To view and run the Jupyter Notebook, ensure you have Jupyter Notebook installed along with the necessary Python libraries (e.g., pandas, matplotlib, seaborn). Open the [JUPYTER NOTEBOOK](https://github.com/shishir1991/Python/blob/main/Bank%20Telemarketing%20Campaign-Exploratory%20Data%20Analysis%20(EDA)/Exploratory%20Data%20Analysis%20(EDA)-Jupyter%20File.ipynb) in Jupyter Notebook to explore the complete EDA process and visualizations.

## Contributing
Contributions to this project are welcome. Please fork the repository, make your changes, and submit a pull request for review.

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/shishir1991/Python/blob/main/LICENSE) file for more details.

## Contact
For any questions or inquiries, please contact at [shishirdma@mail.com].


















