# AI Ethics Audit on Predicting Drug Consumption from Psychological Assessment Data
Authors: D. Dhameliya, L. Ng, W. Singh
Fall 2022, San Francisco State Univerisity

## Primary Motive

We are are primarily interested in implementing a rigorous AI Ethics Auditing procedure which can be utilized in any AI based model deplyment. For doing this, We develop a potential use-case based model for a hypothetical enterprise. We then try to instill transparency in our model development and describe in detail the capability and implications of using such a model. We also analyse the models using feature based explainability methods.

## Project Description
### Description of Training Data
Our team has used data from the UCI ML Repo: Drug Consumption Data Set for analysis, which contains 1885 samples and 32 attributes. Twelve attributes are personal information such as age, gender, education, and results of personality assessments, while the remaining attributes are categorical data regarding respondents’ most recent use of specific legal and illegal substances.

### Description of Application
The goal of this project is to explore how Machine Learning can find meaningful predictive variables from psychological assessment data to predict if a given individual is likely to have used drugs recently. Of particular interest is the split between predicting the use of legal vs illegal drugs, and of harmful vs benign drugs. This may be of interest to companies or public health workers who have access to psychological assessment data but not pharmacokinetically based drug use monitoring equipment or programs due to expense or logistical difficulty.

### Tools and Evaluation Method
We will use R as our data analysis and machine learning tool, and Random Forest as the algorithm. In terms of technical and explainability auditing and analysis, we have drawn inspiration from materials like lecture slides by Dr. Petkovic at SF State University, as well as best practices from relevant sources such as the UC Irvine Machine Learning Dataset Repository, where we obtained our data. As far as ethics evaluation, our team will analyze the results with an eye toward bias, harm, fairness, transparency, and other best practices from the ethics in AI field of study, especially as we progress through peer-reviewed research, details of our references can be found in the final report available at the repo.
