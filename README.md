# Lending club case study
> This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
 Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study..


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 
- The loan dataset has been used. The dataset has 39717 records and 111 columns

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Most of the loan amount is towards lower value and much availed by the borrowers
- The 50 percentile for Charged off loan is higher than the fully paid loans and suggests that loans with higher interest rates are more likely to default
- Higher interest rates are associated with a higher likelihood of loan default. The median interest rate for charged off loans is higher compared to fully paid loans
- Higher credit utilization is associated with a higher likelihood of loan default. Borrowers with higher revolving utilization are more likely to default
- Lower-grade loans (closer to G) have higher default rates. The default rate increases as the grade decreases from A to G. This has the highest impact on the loan default
- Among the lower grades – D to G which have the most likelihood to default, the top 5 sub grades with > 0.3 default rate are F5,G3,F4,G5,G2
- We see that even for the verified loans and source verified loans, there are defaults happening and thus, this should be looked in the lending company
- Renters and those have a mortgage have a significant number of charged off loansm/user-attachments/assets/82c29f10-4f95-4bea-b0c1-ff17ae4163fc)
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - pandas
- library - matplotlib
- library - seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by UpGrad
- This project was based on EDA


## Contact
Created by [@shobhit1604] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
