# Lending CLub Case Study EDA



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions) 

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- What is the background of your project?<br>
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. 
Borrowers can easily access lower interest rate loans through a fast online interface. 
- What is the business probem that your project is trying to solve?<br>
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). 
The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. 
In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 


- What is the dataset that is being used?<br>
Loan.csv is the dataset that has been used

## Conclusions
- Term : 36 months have less defaulters then 60. SO the Loans which has Loan Term with 60 months needs to be taken care.
- Grade : Higher Grade Loans have high percentage to default. (E,F,G) needs to be taken care.
- Sub Grade : Defaulters increases as sub-grades are increasing(Only F and G are exception)
- Loan-Amount: People Having High and Very High Loan AMounts tends to default more.
- Public Record Bankruptcies: People having bankrupties record tend to default more.
- Purpose: Small Bussiness have most defaulters percent than rest followed by renewable ENergy
- Annual-Income : Lower the Annual Income Higher Chances to Default
- Interest Rate : Higher the Interest Rate Higher are the chances of Default.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

Note. As plotly Graphs cannot be viewed on Github use this Viewer Link:[Viewer](https://nbviewer.org/github/shreyansbardia557/LendingCLubCaseStudy/blob/main/LendingClubCaseStudyEDA.ipynb)

