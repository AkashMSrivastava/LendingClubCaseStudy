# Lending Club Case Study
> In this project we are to analyse the risks for consumer finance company while approving loans for applicants.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- A dataset has been provided which contains data of applicants whos loan was approved
- The dataset has information of 39717 applicants and 111 columns providing details about each applicant.
- Analysing this data we need to find patterns and should be able predict which applicants in future are likely to pay back the loan, and which are more likely to default


## Conclusions
##### Numerical data
- loan_amnt is a weak indicator, higher amount indicates more chances of defaulting
- funded_amnt is a weak indicator, higher amount indicates more chances of defaulting
- int_rate is a strong indicator, int_rate between 11 and 16 indicates more chances of defaulting
- installment is a weak indicator, higher installment indicates more chances of defaulting
- emp_length is a weak indicator, higher duration indicates more chances of defaulting
- annual_inc is a strong indicator, lower amount indicates more chances of defaulting
- dti is a strong indicator, higher ratio indicates more chances of defaulting
- inq_last_6mths is a strong indicator, less inqueries indicates more chances of defaulting
- revol_util is a strong indicator, higher rate indicates more chances of defaulting
- total_pymnt is a strong indicator, lower amount indicates more chances of defaulting
- total_rec_prncp is a strong indicator, lower amount indicates more chances of defaulting
- last_pymnt_amnt is a strong indicator, lower amount indicates more chances of defaulting

##### Categorical data
- term is a strong indicator, lower term indicates more chances of defaulting
- grade is a strong indicator, defaulting percentage increase going from A to G
- sub_grade is a strong indicator, defaulting percentage increase going from 1 to 5 for higher grades like A,B,C,D but for lower grades like E and F sub_grade has low impact
- home_ownership is a strong indicator, defaulting chance is low for Mortgage, higher for Own and Rent, and highest for Other
- verification_status is a strong indicator, defaulting chance is low for Not Verified, higher for Source Verified, and highest for Verified
- purpose is a strong indicator.<br/> major_purchase, wedding, car, credit_card, home_improvement has low chance of defaulting<br/> vacation, debt_consolidation, medical, moving, house, other, educational has higher chance of defaulting<br/> renewable_energy, small_business has the highest chance of defaulting
- addr_state is a weak indicator, all states has 10-20% chance of defaulting accept, WY has very low chance of defaulting, while NE has very high chance of defaulting (though we have only 5 records from NE)


## Technologies Used
- python
- numpy
- pandas
- matplotlib
- seaborn


## Acknowledgements
- This project was inspired by <strong>UpGrad</strong>


## Contact
Created by [@AkashMSrivastava] - feel free to contact me!
