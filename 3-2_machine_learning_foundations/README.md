## machine_learning_foundations

Machine learning is used in this project. The probability of outflow is predicted (at the level of the next month) for each client; typical portraits of users are formed: the brightest groups are highlighted, their main properties are characterized; the main signs that most strongly influence outflow are analyzed.

## Data:
Customer data for the previous month before checking the outflow:
- `gender` — gender;
- `Near_Location` — living or working in the area where the fitness center is located;
- `Partner` — an employee of the club's partner company (cooperation with companies whose employees can receive discounts on a subscription - in this case, the fitness center stores information about the client's employer);
- `Promo_friends` — the fact of the initial recording within the framework of the "bring a friend" campaign (used a promo code from a friend when paying for the first subscription);
- `Phone` — availability of a contact phone;
- `Age` — age;
- `Lifetime` — the time since the first visit to the fitness center (in months).

Information based on the log of visits, purchases and information about the current status of the customer's subscription:
- `Contract_period` — the duration of the current valid subscription (month, 6 months, year);
- `Month_to_end_contract` — the period until the end of the current valid subscription (in months);
- `Group_visits` — the fact of attending group classes;
- `Avg_class_frequency_total` — the average frequency of visits per week for the entire time since the beginning of the subscription;
- `Avg_class_frequency_current_month` — average frequency of visits per week for the previous month;
- `Avg_additional_charges_total` — total revenue from other fitness center services: cafes, sporting goods, beauty and massage parlors.
- `Churn` — the fact of outflow in the current month.

## Results
In the course of this work, the following steps were performed:
1. a research analysis of the data was carried out;
2. columnar histograms of the distribution of signs were constructed for those who left (outflow) and those who remained, a correlation matrix was built;

3. a model for predicting customer outflow is constructed using two methods - logistic regression and random forest;

4. clustering of clients is determined by constructing a dendogram and training the model using the K-means method;
4.1 The program identified 4 types of clients by constructing a dendo gram. But according to the task, it was specified to take a value equal to 5.
5. we constructed the distribution of features for clusters and calculated the probability of outflow for each group.

Recommendations for the strategy of interaction with customers and their retention.

- Based on the common features of the most prominent groups prone to outflow, we will formulate a strategy for retaining customers:
* most of the clients are not members of the promotional program; (This may indicate that these clients do not have any takeaways in the hall. Hence, it can be assumed that this affects involvement in the process. Perhaps it is worth holding a "birthday club" in the format of a party. In order for clients to communicate with fitness trainers in an informal setting, and the clients themselves could find like-minded people.)
* most of the clients have a contract for 1 month; (it is logical that customers with the shortest contract term tend to outflow.)
* most of the clients do not attend group classes. (maybe it's worth working on expanding the range of services provided for group classes)

## Stage
Project is fully completed
