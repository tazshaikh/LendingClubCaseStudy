# AIMLC53 Lending Club Case Study
> The purpose of the Lending Club Case Study is three fold :
    - Apply the techniques learnt in EDA Course to understand how consumer attributes and loan attributes influence the tendency of default.
    - Develop a basic understanding of risk analytics in banking and financial services. 
    - Understand how data is used to minimise the risk of losing money while lending to customers.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

- General information about the project
Lending Club Bank is a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
    If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
    If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.
The aim is to identify patterns which indicate if a person is likely to default

- What is the business problem that your project is trying to solve?
Lending Club Bank is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
The main purpose of this analysis is to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.

-The Approach

1.Data Understanding : Identification Data quality issues  
                       Correct Interpretation of variable meanings
2.Data Cleaning and Manipulation : Addressing Data Quality Issues like missing value imputation
                                   Outlier treatment and other kinds of data redundancies. 
                                   Converting Data to a suitable convinient format Manipulation of string and dates
3.Data Analysis : Right problem is solved which is coherent with the needs of the business
                  Performed Univeriate Analysis : Identifying 5 important drivers which are strong indicators of default 
                  Business-driven, type-driven and data-driven metrics are created for the important variables and utilised for analysis                       Performed Biveriate Analysis : Appropriate plots are created to present the results of the analysis
                  
4.Recommendations And Assumptions : The recommendations to solve the problems
                                    Stating any Assumptions made clearly


-DataSet being used

Lending Club Bank has provided the loan.csv file which has consumer and loan attributes from year 2007 to 2011.
The Loan Dataset has data about the accepted loans only. It does not contain rejected applicant loan details.

## Conclusions

Following are the Conclusions based on the above Analysis

1) The data provided to provide clear default profile paramaters is insufficient. Out of the 111 columns only 57 columns had meaningful data and finally ended up using only 54 columns which is approximately 50% of the columns only. Recommendation is to invest in a proper data gathering exercise and redo the Analysis

2) The following variables were analysed and compared 

For the borrower : Annual Income , Employement length and home ownership
For the Loan : Loan Amount , term of loan , grade , interest rate , Loan status

If the data for other attributes provided then Analysis can be more accurate

3) out of the total loan count of 38420 for Lending Club Bank only approximately 4% loans are charged off which indicates there is a roboust mechanism in place to identify defaulter borrower profiles

4) grade and loan status indicates that for A ,B grades the loan status is fully paid as compared to F , G E and D. so bank should give more of A,B and C graded loans.

5) Even though the percentage of total Charged off loans is 4% , it is increasing only a YOY basis . Therefore Lending Club Bank should invest in thorough Data Analysis with good quality data.

6) Home ownership of the applicant could be a good indicator for identifying defaulters. But there are many 'other' types which does not provide correct insight into the defaulter profile.

7) Loan amount and Loan status are directly correlated. As the loan amount increases charged off count also goes up so bank should avoid giving higher value loans.

8) 36 months or 60 months term period does not have much impact on charged off and fully paid ratio.So bank can go upto 60 month terms period

9) Annual income of the borrower applicant if high is able to pay off the loan and does not default. So bank should target high net worth individuals for loans.

10) The bank is giving approximately equal number of loans with 1 year employement and 10 year employment. Bank can look into increasing loans to applicants with more number of employment years as we have noticed more defaulters with less employment years.


## Technologies Used

- library - numpy
- library - pandas
- library - seaborn
- library - matplotlib


## Acknowledgements

- Sameer Inamdar my team member for his contribution
- This projecthas taken inputs from the Lending Club Case Study session conducted by Dr Pooja Jain from IIITB Nagpur


## Contact
Created by [@tazshaikh] - feel free to contact me!


