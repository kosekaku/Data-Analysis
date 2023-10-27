# Data-Analysis
Udacity Data analysis
## Introduction to Data Analysis
> Data analysis process, wrangling,  exploring, analyzing, and communicating data, working with data in Python using libraries like Numpy and Pandas

> Project 1 - Investigate a dataset
> 
>>  Report communicating findings
>> 
>>  Python code written for the analysis
>> 
>>  The data set used-
>>  HTML and python code

> Project 2
>
>> Part I, Exploratory data visualization, using Python visualization libraries to systematically explore dataset, starting from plots of single variables and building up to plots of multiple variables.
>>
>> Part II, Explanatory data visualization, producing a presentation that illustrates interesting properties, trends, and relationships dataset.



# PROJECT DETAILS EXPLANATION

# Project 1 (Dataset Exploration Loans Dataset)
## by Kose Bilali Salim


## Dataset

> The Prosper Loan dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. I will explore about 10-15 variables both categorical variables


## Summary of Findings

> Prior to the visual explorations, I did some data cleaing to remove null ProsperRating with datetime before July 2009, Changed the datatype of the LoanOriginationDate column from object to datetime. I also filled missing values for TotalProsperLoans column. The null values implied people without prior loans.

> In the exploration, I found that people with;
* EmploymentStatus __employed__, and high StatedMonthlyIncome would completed their loan payment, while those with EmploymentStatus __'Not employed', 'Self-employed','Retired', 'Part-time'__ defaulted in their loan payment.

* Majority of people completed their loans payments.

* Most count of ListingCategory (numeric) belonged to the category 1 or Debt Consolidation group.

* Fewer LoanOriginalAmount mostly defaulted in loan payment

* Borrower with a high rating are those whose employment status is either Employed or Full-time, and they complete loan repayment.

* The relationship between statedMonthlyIncome, and LoanOriginalAmount is positive correlation.

* People with employment status Other, Employed, and have high stated monthly income get the most LoanOriginalAmount.

* People with a rating of about A and AA gets better investment from investors. This is implies more investors are willing to spend their money on crediting people with good rating and history of loan completion


## Key Insights for Presentation

> I first focused on the trends on employment status on the loan outcome whether defaulted or completed. I started with general overview of the count of employment status, and loan status.

> I then, used both the categorical and numberical variables on various ploting chart. bar plot, histogram plot, scatter plot, point plot, and finally utilized violin plot to get the multivariate relationship between ProsperRating, LoanOriginalAmount, and Loan status. The applied __shape__ and __color__ as the main non-positional encodings.
