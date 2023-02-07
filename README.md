# Project Name
> Exploratory Data Analysis on the historical data of Lending Club. The Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- The Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return. The Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return. 
- We have the historical data of the applicants with their loan data. With this,the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilize this knowledge for its portfolio and risk assessment.
- The data given contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.



## Conclusions
- We observe that the applicants whose loan status is Charged Off i.e. Defaulters have slightly higher interest rate in the distribution. We can infer that the lower the interest rate, the easier it is to pay.
- We observe that annual income of the applicants doesnt have any visible impact on the loan_status. Hence it hasn't been a major decisive factor, from the historical evidences.
- We observe that loan_amnt of the applications has a minor difference on the loan_status. Hence it can be considered as a low-weightage decisive factor, from the historical evidences.
- We don't see any significant impact of the loan purpose in deciding the loan_status.
- We see that home ownership is kind of proportionate in both the loan statuses. Hence, it doesn't make much impact on the ultimate loan status.
- We see that in case of Fully Paid loan status, Grade A has more frequency. Whereas, In case of Charged-of, Grade A is significantly lesser. Hence, it can be observed that Higher Grades have very less chance of Defaulting or Charging off.
- We observe that the applicants whose loan status is Charged Off i.e. Defaulters have slightly higher debt-to-income ratio. It makes sense as more the debt, the difficult it becomes to handle it.
- We observe that the applicants who have loan term as 36 months instead of 60 months. are more likely to Paid off the loan.
- We observe that the applicants whose investors have been careful while alocating the funds and have allocated the appropriate funds (upon analysis) instead of approved amount. Such applications have seen significantly lesser default rates.



## Technologies Used
- python - version 3.0
- library - numpy, Pandas, matplotlib, seaborne

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by the business problem of Lending Club - the Company.
- https://www.lendingclub.com/


## Contact
Created by [@rajneeshdubey] - feel free to contact me!

