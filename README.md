## END TO END ML PROJECT


1.	Loan Status Prediction Dataset for Exploratory Data Analysis
In this Loan Status Prediction dataset, we have the data of applicants who previously applied for the loan based on the property which is a Property Loan. The bank will decide whether to give a loan to the applicant based on some factors such as Applicant Income, Loan Amount, previous Credit History, Co-applicant Income, etc… The goal is to perform exploratory data analysis of the dataset. Specifically, statistical inference methods are applied to draw meaningful insights from the data. The project leverages Python libraries such as Pandas for data manipulation, Matplotlib and Seaborn for data visualization, and SciPy for statistical tests. 

1.1	Import Libraries or Packages
The first step in the EDA process is to import and install the required packages or libraries. Libraries such as Pandas, NumPy, Seaborn, Matplotlib, SciPy etc. are imported and installed for data manipulation and visualization. 
1.2	Description of the Dataset
Below is a description of the loan_data.csv file:
Loan_ID: A unique loan ID.
Gender: Either male or female.
Married: Weather Married(yes) or Not Marttied(No).
 Dependents: Number of persons depending on the client.
 Education: Applicant Education (Graduate or Undergraduate).
 Self_Employed: Self-employed (Yes/No).
 ApplicantIncome: Applicant income.
  CoapplicantIncome: Co-applicant income.
  LoanAmount: Loan amount in thousands.
  Loan_Amount_Term: Terms of the loan in months.
  Credit_History: Credit history meets guidelines.
  Property_Area: Applicants are living either Urban, Semi-Urban or Rural.
  Loan_Status: Loan approved (Y/N)

2	Data Wrangling
2.1	Checking Missing Values
Data wrangling process involves performing data checks. The first data check to perform is the missing values. In the loan status prediction dataset, the missing data comes with the question mark “?”. We replace “?” with NaN (Not a Number), Python’s default missing value marker for reasons of computational speed and convenience. The missing values in each column are counted and displayed. 

2.2	Checking Duplicates
Again, duplicates are checked to ascertain whether some of the values are duplicated. In the loan status prediction dataset, we observe that there are no duplicates. 

2.3	Check Data Types and Unique Values of each Column.
The data types and unique values of each column are checked and displayed. 

2.4	Check Statistics of the Dataset
The statistics of the datasets are determined the mean, standard deviation, and the minimum and maximum values of each numerical variable. 

3	Exploring Data (Visualization)
3.1	Data Standardization
Standardization is the process of transforming data into a common format, allowing the researcher to make the meaningful comparison.  Some of the loan status prediction datasets are standardized.
3.2	Data Normalization
Normalization is the process of transforming values of several variables into a similar range. Typical normalizations include scaling the variable, so the variable average is 0
scaling the variable so the variance is 1 scaling the variable so the variable values range from 0 to 1. This is done by performing label encoding on the categorical variables. To display boxplots, some datasets are normalized. 

4	Findings
From the results displayed in all the plots we can observe that:
•	The male gender has higher chance of getting approved for loan when compared to females. The reason is that there are more male loan applicants of 291 (77.4%) applicant compared to female applicants of 85 (22.6%).
•	The number of married people stand a chance of getting ‘Yes’ to loan status prediction because of the higher number of married people applying for loan compared to non-married ones. 
•	Higher number of graduates stand a chance of getting approved for loan when compared to non-graduates due to the higher application of graduates. 
•	From the plots, we observe that the applicant income is between 2000 and 4000 while their co applicant incomes are between 0 and 4000.

5	Conclusions
In summary, the male applicants, graduates, and married people are likely to get ‘Yes’ to their loan status prediction. 

6	Reflection
Further analysis such as chi-squared test, likelihood ratio and correlation co-efficient can be performed in future works. 


