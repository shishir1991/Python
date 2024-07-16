# Descriptive Statistics & Bank Personal Loan Modelling dataset Analysis

## Table of Contents
1. [Section 1: Theoretical Questions](#section-1-theoretical-questions)
   - [Question 1](#question-1)
   - [Question 2](#question-2)
   - [Question 3](#question-3)
   - [Question 4](#question-4)
   - [Question 5](#question-5)
   - [Question 6](#question-6)
   - [Question 7](#question-7)
2. [Section 2: Practical Questions with Dataset](#section-2-practical-questions-with-dataset)
   - [Question 8 to 20] [JUPYTER NOTEBOOK](https://github.com/shishir1991/Descriptive-Statistics-PythonPackage/blob/main/Descriptive%20Statistics-Jupyter%20Notebook.ipynb)
3. [Deliverables for Solution](#deliverables-for-solution)
4. [License](#license)
5. [Contact](#contact)

## Section 1: Theoretical Questions
### Question 1
A statistics test was conducted for 10 learners in a class. The mean of their score is 85 and the variance of the score is zero. What can you interpret about the score obtained by all learners?

- If the variance of the scores is zero, it implies that there is no variability in the scores. In other words, all scores are identical. Since the mean score is 85, it means that all 10 learners scored exactly 85 on the test.

### Question 2
In a residential locality, the mean size of the house is 2224 square feet and the median value of the house is 1500 square feet. What can you interpret about the skewness in the distribution of house size? Are there more bigger or smaller houses in the residential locality?

- The mean (2224 square feet) is greater than the median (1500 square feet), indicating that the distribution of house sizes is positively skewed, with a tail extending towards larger house sizes. Therefore, there are more smaller houses in the residential locality as indicated by the median value being less than the mean.

### Question 3
The following table shows the mean and variance of the expenditure for two groups of people. You want to compare the variability in expenditure for both groups with respect to their mean. Which statistical measure would you use to evaluate the variability in expenditure? Please provide an explanation for your answer.

| Expenditure | Group I | Group II |
|-------------|---------|----------|
| Mean        | $500,000| $40,000  |
| Std. Dev.   | $125,000| $10,000  |

- To compare the variability in expenditure for both groups with respect to their mean, you would use the coeff. of variation (CV).
Coefficient of variance (CV) = (Standard dev. / Mean)  * 100%
For
Group 1: CV = (125,000 / 500,000) * 100% = 25%
Group 2: CV = (10,000 / 40,000) * 100% = 25%
Both groups have the same coefficient of variation (25%), indicating that the variability in expenditure relative to the mean is consistent across both groups.

### Question 4
During the survey, the ages of 80 patients infected by COVID and admitted to one of the city hospitals were recorded and the collected data is represented in the less than cumulative frequency distribution table.

| Age (in yrs.) | No. of Patients |
|---------------|-----------------|
| 5 - 15        | 6               |
| 15 - 25       | 11              |
| 25 - 35       | 21              |
| 35 - 45       | 23              |
| 45 - 55       | 14              |
| 55 - 65       | 5               |

#### a. Which class interval has the highest frequency?  
The class interval with the highest frequency is "35-45 years," with 23 patients.

#### b. Which age was affected the least?  
As the age group “55-65 years” have only 5 patients. Therefore, this age range was affected the least among the patients admitted to the hospital.

#### c. How many patients of age 45 years and above were admitted?  
Since the interval spans 10 years (from 35 to 45), and assuming a uniform distribution, we can estimate that approximately 1/10th of the patients in this interval are exactly 45 years old.
So, for the "35 to 45 years" interval: Number of patients aged 45 = (1/10) * 23 = 2.3, rounding off 2
Total patients of age 45 years and above 14 (from "45 to 55 years") + 2 (estimated from "35 to 45 years") + 5 (from "55 to 65 years") = 21
So, there were approximately 21 patients of age 45 years and above admitted to the hospital.

#### d. Which is the modal class interval in the above dataset?
The modal class interval is the interval "35 to 45 years" because it has the highest frequency of 23 patients.

#### e. What is the median class interval of age?
To find the median class interval, we locate the class interval containing the median age, which is the interval where the cumulative frequency first exceeds (or equals) half of the total frequency.

Cumulative Frequency:
- 5 to 15 years: 6
- 15 to 25 years: 6 + 11 = 17
- 25 to 35 years: 17 + 21 = 38
- 35 to 45 years: 38 + 23 = 61
- 45 to 55 years: 61 + 14 = 75
- 55 to 65 years: 75 + 5 = 80

Since the total frequency is 80, the median would be the 40th value. Looking at the cumulative frequencies, the interval "35 to 45 years" (from 38 to 61) contains the 40th value.
So, the median class interval of age is "35 to 45 years."

### Question 5
Assume you are the trader and you have invested over the years, and you are worried about the average return on investment. What average method would you use to compute the average return for the data given below?

| Year | Return | Asset Price |
|------|--------|-------------|
| 2015 | 36%    | 5000        |
| 2016 | 23%    | 6400        |
| 2017 | -48%   | 7890        |
| 2018 | -30%   | 9023        |
| 2019 | 15%    | 4567        |
| 2020 | 31%    | 3890        |

- To compute the average return on investment, we’ll use the geometric mean. 
- The geometric mean is particularly useful for calculating average rates of return over multiple periods, especially when dealing with percentages.

A. Convert the return percentages to their decimal equivalents:

     36% = 0.36, 23% = 0.23, -48% = -0.48, -30% = -0.30, 15% = 0.15, 31% = 0.31

B. Add 1 to each decimal return value:

     0.36 + 1 = 1.36, 0.23 + 1 = 1.23, -0.48 + 1 = 0.52, -0.30 + 1 = 0.70, 0.15 + 1 = 1.15, 0.31 + 1 = 1.31 
    = ( 1.36 * 1.23 * 0.52 * 0.70 * 1.15 * 1.31 )1/6  - 1
    = (0.9173066448)1/6 - 1
    = 0.98571740091933 – 1
    = -0.014282599080
    = -1.42 %

### Question 6
Suppose you have been told to measure the average height of all the males on the earth. What would be your strategy for the same? Would the average height be a parameter or a statistic? Justify your answer.

- To measure the average height of all males on Earth, my strategy would involve collecting a representative sample of male heights from different regions and populations across the globe. 
- I would ensure that the sample is diverse and adequately represents the variability in male heights worldwide.
- Once the sample is collected, I would calculate the mean height to estimate the average height of all males on Earth.

### Question 7
Calculate the z score of the following numbers:  
X = [4.5, 6.2, 7.3, 9.1, 10.4, 11]

- To calculate the z-score of each number in the given list, we use the formula:
##### Z=X−μ/ σ
##### X is the value in the list,
##### μ is the mean of the list,
##### σ is the standard deviation of the list.
##### Mean (μ): 
##### μ =(4.5+6.2+7.3+9.1+10.4+11)/6
##### μ =8.08
- To calculate the standard deviation, we will first find the variance, then take the square root.
##### Variance=((4.5−8.08)2+(6.2−8.08)2+(7.3−8.08)2+(9.1−8.08)2+(10.4−8.08)2+(11−8.08)2) / 6
##### Variance=6.00772
##### Standard deviation, σ= Cube root (6.00772) = 2.450
##### So, for 
##### X= 4.5, Z = −1.457
##### X = 6.2, Z = −0.768
##### X = 7.3, Z = −0.325
##### X = 9.1, Z = 0.416
##### X = 10.4, Z = 0.945
##### X = 11, Z = 1.188

## Section 2: Practical Questions with Dataset
You are expected to perform statistical analysis for the Bank Personal Loan Modelling dataset. Below is the data dictionary:

| ID               | Customer ID                                             |
|------------------|---------------------------------------------------------|
| Age              | Customer's age in completed years                       |
| Experience       | # years of professional experience                      |
| Income           | Annual income of the customer ($000)                    |
| ZIPCode          | Home Address ZIP code.                                  |
| Family           | Family size of the customer                             |
| CCAvg            | Avg. spending on credit cards per month ($000)          |
| Education        | Education Level. 1: Undergrad; 2: Graduate; 3: Advanced/Professional |
| Mortgage         | Value of house mortgage if any. ($000)                  |
| Personal Loan    | Did this customer accept the personal loan offered in the last campaign? |
| Securities Account | Does the customer have a securities account with the bank? |
| CD Account       | Does the customer have a certificate of deposit (CD) account with the bank? |
| Online           | Does the customer use internet banking facilities?       |
| CreditCard       | Does the customer use a credit card issued by UniversalBank? |

For questions 8 to 20, we'll be using the Bank Personal Loan Modelling dataset and Jupyter Notebook for answer the questions.

[JUPYTER NOTEBOOK](https://github.com/shishir1991/Python/blob/main/Descriptive%20Statistics%20%26%20Bank%20Personal%20Loan%20Modelling/Descriptive%20Statistics-Jupyter%20FIle.ipynb)

## Deliverables for Solution
- A Jupyter notebook detailing the steps.

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/shishir1991/Descriptive-Statistics-PythonPackage/blob/main/LICENSE.txt) file for more details.

## Contact
For any further questions or contributions, please contact us:

- Project Lead: Shishir KHerod
- Email: shishirdma@gmail.com

Thank you for visiting our project repository!







