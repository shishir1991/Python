# Real Estate Data Analysis for Decision Making

Welcome to the Real Estate Statistics Project repository! This project focuses on analyzing real estate data to derive insights and make informed decisions. Through statistical analysis and hypothesis testing, we aim to provide valuable information for decision-making in the real estate industry.

## Table of Contents
- [Introduction](#introduction)
- [Project Description](#project-description)
- [Hypothesis Testing](#hypothesis-testing)
- [Instructions](#instructions)
- [Usage](#usage)
- [Results](#results)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project aims to analyze real estate data in Australia to make statistical inferences for decision making. The dataset contains information about various properties, including their prices, locations, and other attributes.

## Project Description
The project uses a dataset [Property Dataset](https://github.com/shishir1991/Python/blob/main/Real%20Estate%20Price%20Analysis-Statistics%20for%20Decision%20Making/Property%20Dataset.csv) containing information about real estate properties, including their prices, locations, and other relevant details. The dataset is used to test two hypotheses:
1. The typical property price in the suburb Altona is $800,000.
2. There is a difference in property prices between summer and winter months in the year 2016.
3. For the suburb of Abbotsford, what is the probability that out of 10 properties sold, 3 will not have car parking? Use the column car in the dataset. Round off your answer to 3 decimal places.
4. In the suburb Abbotsford, what are the chances of finding a property with 3 rooms? Round your answer to 3 decimal places.
5. In the suburb Abbotsford, what are the chances of finding a property with 2 bathrooms? Round your answer to 3 decimal places.

## Hypothesis Testing
1. **Altona Property Price Hypothesis**
   - Null Hypothesis: The mean property price in Altona is $800,000.
   - Alternative Hypothesis: The mean property price in Altona is greater than $800,000.
   - Test: One-sample t-test.

2. **Summer vs Winter Property Prices Hypothesis**
   - Null Hypothesis: There is no difference in the mean property prices between summer and winter months in 2016.
   - Alternative Hypothesis: There is a difference in the mean property prices between summer and winter months in 2016.
   - Test: Independent samples t-test.

3. **Car Parking Availability in Abbotsford**
   - For the suburb of Abbotsford, we test the hypothesis: 
   - **Hypothesis**: What is the probability that out of 10 properties sold, 3 will not have car parking?
   - **Result**: The probability is calculated to be 0.260.

4. **Room Availability in Abbotsford**
   - We also test the hypothesis:
   - **Hypothesis**: What are the chances of finding a property with 3 rooms in Abbotsford?
   - **Result**: The probability is calculated to be 0.357.

5. **Bathroom Availability in Abbotsford**
   - We also test the hypothesis:
   - **Hypothesis**: What are the chances of finding a property with 2 Bathrooms in Abbotsford?
   - **Result**: The probability is calculated to be 0.339.

## Instructions
1. Clone the repository to your local machine.
2. Install the required dependencies (Pandas, SciPy).
3. Download the dataset (property.csv) and place it in the project directory.

## Usage
- Run the provided Python scripts in Jupyter Notebook or any Python environment to perform the hypothesis tests.
- Modify the scripts or dataset paths as needed for your analysis.

## Results
- For Altona, the analysis suggests that there is not enough evidence to conclude that the typical property price is greater than $800,000.
- For 2016, the analysis indicates a significant difference in property prices between summer and winter months.
- The probability of 10 properties sold, 3 will not have car parking is calculated to be 0.260 or 26%.
- The probability of finding a property in suburb Abbotsford with 3 rooms in Abbotsford is calculated to be 0.357 or 35.7%.
- The probability of finding a property  in suburb Abbotsford with 2 Bathrooms in Abbotsford is calculated to be 0.339 or 33.9%.

## Conclusion
Based on the statistical analysis, it can be inferred that there is a need for further investigation to understand the trends in property prices and their implications.

## Contributing
Contributions to the project are welcome. Feel free to fork the repository and submit pull requests with your enhancements or suggestions.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


































