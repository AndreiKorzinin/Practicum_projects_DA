## Investigation of the reliability of borrowers

Based on the data of the bank's credit department, investigated the influence of marital status and
the number of children on the fact of repayment of the loan on time. Information about
the data was received. Gaps have been identified and processed. Data types have been replaced with those corresponding to the stored data. Duplicates have been removed. The data is categorized. One dataframe is decomposed into three.

## Data:

- `children` — number of children's family;
- `days_employed` — total work experience in days;
- `dob_years` — client's age in years;
- `education` — the client's level of education;
- `education_id` — education level identifier;
- `family_status` — marital status;
- `family_status_id` — id of marital status;
- `gender` — client's gender;
- `income_type` — type of employment;
- `debt` — did the user have a loan repayment debt;
- `total_income` — monthly income;
- `purpose` — purpose of obtaining a loan.

## Results

From the point of view of the influence of the number of children in the family on the probability of loan arrears, there are two categories with one and two children. The percentage of problem borrowers with one and two children is 9.29% and 9.72%, respectively. The most reliable categories are families with three children and childless, the percentage of debtors is ~7.50%.

A little more than 10% is the number of loans that had arrears on payments from people who are in the status of "not married". This number is quite explicable, most likely, these are young people who are less responsible than people who are married. Family people are the largest category among those represented, having a 7.59% interest on debts, the most reliable. The percentage of the categories "widow" and "divorced" is also low, but these categories are few and therefore we do not place special emphasis on these data.

The influence of the lender's income level did not reveal any patterns in the results of the study. In view of the fact that the categories "A, D, E" (380 people, three categories combined) are quite small in comparison with the category "C" (1183 people), we can only single out a problematic category with an income level - category "C" - 8.54%.

A study on the purposes of the loan revealed the following pattern: people taking out a loan for a car or training are more likely to have problems paying on time - 9.39% and 9.25%, respectively. And real estate and wedding loans have the best percentage of non-repayment on time - 7.33% and 7.47%, respectively.

## Stage

Project is fully completed
