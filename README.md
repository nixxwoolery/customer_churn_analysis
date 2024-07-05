# Digital Audio Broadcasting (DAB) Radio Station Analysis Application


Welcome to the DAB Analysis Application repository!

## Welcome! 👋

Thanks for checking out my repo.

## Table of Contents

- [About the Project](#about-the-project)
  - [Overview](#overview)
  - [Goals](#goals)
- [Technologies Used](#technologies-used)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [The Design](#the-design)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## About the Project

### Overview

This project aims to predict customer churn and identify high-value customers who are at risk of leaving the bank. By understanding the factors driving customer churn, we can develop effective retention strategies to enhance customer satisfaction and loyalty.

### Goals

The key objectives of this project included:

Data Cleaning
- Identify and handle missing values, anomalies, and errors in the dataset.
- Ensure the data is fit for analysis by correcting and removing inconsistent entries.

Data Reshaping
- Reshape the data based on requirements, including restructuring columns or combining data from different resources.

Statistical Analysis
- Develop and test functions for statistical analysis, including mean, mode, and median calculations for specific columns.

Visualization
- Produce suitable graphs displaying information extracted from DAB Multiplexes.
- Explore visualizations to demonstrate correlations and trends within the data.


## Technologies Used

This project was built using the following technologies:

Programming Language
Python

Libraries
- Pandas: For data manipulation and analysis.
- NumPy: For numerical operations.
- Seaborn & Matplotlib: For data visualization.
- Scikit-learn: For machine learning algorithms and model evaluation.

File Formats
- XLS

Development Environment
Jupyter Notebook: For interactive and collaborative data analysis.

### What I Learned

During the development of this Digital Audio Broadcasting (DAB) Radio Station Analysis project, several key learnings and skills were acquired:

- Data Cleaning and Preprocessing: Developed proficiency in identifying and handling missing values, anomalies, and errors in datasets. Explored techniques to ensure data integrity and fitness for analysis.
- Data Reshaping: Acquired skills in reshaping data to meet specific project requirements. This included restructuring columns and combining data from various sources.
- Statistical Analysis: Implemented functions for statistical analysis, including mean, mode, and median calculations for targeted columns. Gained insights into deriving meaningful information from datasets.
- Data Visualization: Explored the use of Matplotlib and Seaborn libraries to create visually appealing and informative graphs. Demonstrated correlations and trends within the data.
- Python Libraries: Utilized Pandas for efficient data manipulation, NumPy for numerical operations, and leveraged the capabilities of Python for comprehensive data analysis.
- Continuous Learning: Recognized the importance of staying updated with the open-source community, accessing valuable resources, and leveraging insights to enhance project success.

- Clustering and Profile Creation
K-Means clustering was used to group customers based on high-attrition attributes, creating distinct customer profiles. Descriptive statistics summarized the customer profiles, and the attrition rate for each profile was calculated to identify the profile with the highest probability of churning.

Evaluation of Solutions
The effectiveness of the presented solutions was evaluated using the following metrics:

Accuracy: The proportion of true results (both true positives and true negatives) among the total number of cases examined.
Precision: The proportion of true positive results among all positive results predicted by the model.
Recall: The proportion of true positive results among all actual positive cases.
F1 Score: The harmonic mean of precision and recall.
High-Value Client Identification
High-value targets were identified by calculating the correlation between the “balance” attribute and other attributes in the dataset. Customers with a balance exceeding a threshold of 175,000 were considered high-value targets.

Results

The project successfully identified key attributes associated with high levels of attrition actions and created three customer profiles:

Profile 1: Total Transaction Amount, Tenure, Total Transaction Count
Profile 2: Total Transaction Count, Tenure, Income Category
Profile 3: Is Active Member, Number of Products, is_fraud
The profiles were evaluated, and Profile 3 was identified as having the highest attrition rate, indicating a need for targeted retention strategies for customers fitting this profile.

These skills collectively contribute to a robust foundation in data analysis, cleaning, and visualization, which are crucial elements in data science and analytics projects.

The analysis demonstrated that advanced machine learning techniques and data mining methods could effectively predict customer churn and identify high-risk customers. The insights gained from this project can help the bank develop targeted retention strategies, improve customer satisfaction, and ultimately reduce attrition rates.

### Continued Development

Future developments will concentrate on the following aspects:

Enhanced Statistical Modules: Introduce advanced statistical modules to deepen the analysis and provide more sophisticated insights into the DAB data.
Machine Learning Integration: Explore the integration of machine learning algorithms to predict trends, anomalies, or future patterns in DAB radio station data.
Real-time Data Visualization: Implement real-time data visualization features to enable dynamic tracking of changes and trends in the radio station metrics.
User Feedback Mechanism: Incorporate a feedback mechanism in the GUI to collect user insights and improve the overall user experience.
Extended File Format Support: Expand the file handling capabilities to support additional data formats, making the tool more versatile.
Community Collaboration: Establish avenues for collaboration within the data science and broadcasting communities to gather feedback, insights, and potential enhancements.


### The Design

The project follows a modular design, separating concerns for data cleaning, reshaping, analysis, and visualization. 


## Author

- Website - [Nicolette Woolery](https://www.nicolettewoolery.com)
- Instagram - [@nixxintech](https://www.instagram.com/nixxintech)

## Acknowledgments

I appreciate the open-source community for providing valuable resources and insights that contributed to the success of this endeavor.
