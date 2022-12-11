## telecom_company_tariff_determination
A preliminary analysis of the use of tariffs on a sample of customers was carried out, the behavior of customers when using the operator's services was analyzed and optimal sets of services for users were recommended. The data was preprocessed and analyzed. Hypotheses about the difference in revenue of subscribers of different tariffs and the difference in revenue of subscribers from Moscow and other regions have been tested.

## Data:
### users (user information):
- `user_id` — unique user id;
- `first_name` — user name;
- `last_name` — user surname;
- `age` — user age (years);
- `reg_date` — date of tariff activation (day, month, year);
- `churn_date` — date of termination of tariff use (if the value is omitted, the tariff was still valid at the time of data upload);
- `city` — the user's city of residence;
- `tariff` — the name of the tariff plan;

### calls (information about calls):
- `id` — unique call number;
- `call_date` — date of the call;
- `duration` — duration of the call in minutes;
- `user_id` — id of the user who made the call;
### messages (information about messages):
- `id` — unique message number;
- `message_date` — date of the message;
- `user_id` — id of the user who sent the message;
### Internet table (information about internet sessions):
- `id` — unique session number;
- `mb_used` — amount of internet traffic spent per session (in megabytes);
- `session_date` — date of the internet session;
- `user_id` — user ID;
### tariffs table (information about tariffs):
- `tariff_name` — name of the tariff;
- `rub_monthly_fee` — monthly subscription fee in rubles;
- `minutes_included` — the number of minutes of conversation per month included in the subscription fee;
- `messages_included` — the number of messages per month included in the subscription fee;
- `mb_per_month_included` — the amount of Internet traffic included in the subscription fee (in megabytes);
- `rub_per_minute` — the cost of a minute of conversation over the tariff package (for example, if the tariff has 100 minutes of conversation per month, then a fee will be charged from 101 minutes);
- `rub_per_message` — the cost of sending a message over the tariff package;
- `rub_per_gb` — the cost of an additional gigabyte of Internet traffic over the tariff package (1 gigabyte = 1024 megabytes).

## Results
In the course of this work, the following steps were taken:
- the quantitative characteristics of users were determined according to their spending on both tariffs;
- calculated monthly revenue from each user;
- two two-sided hypotheses were put forward and calculations were given to confirm or refute these hypotheses.

A quantitative analysis of user spending showed that users of the Smart tariff spend more minutes, SMS and GB. Which in turn leads to the fact that the smart tariff is more profitable for the company. This is also confirmed by the analysis of monthly revenue. The hypothesis put forward, in turn, also confirms that the smart tariff is more profitable in terms of monthly revenue. The hypothesis that monthly revenue in Moscow is not equal to revenue in other regions was also confirmed by calculations and statistical method. Both hypotheses put forward were two-sided, which means that we only consider whether the assumption is true or not, and in which direction if not, it does not matter to us in the context of this task. The significance level was chosen to be 5%. The significance level numerically determines where the boundary of the probability of getting too far from the center of the distribution passes.

Based on the data obtained in the work done, it can be concluded that the Smart tariff is the best.

## Stage
Project is fully completed
