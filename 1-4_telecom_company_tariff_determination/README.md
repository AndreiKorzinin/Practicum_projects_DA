## telecom_company_tariff_determination
A preliminary analysis of the use of tariffs on a sample of customers was carried out, the behavior of customers when using the operator's services was analyzed and optimal sets of services for users were recommended. The data was preprocessed and analyzed. Hypotheses about the difference in revenue of subscribers of different tariffs and the difference in revenue of subscribers from Moscow and other regions have been tested.

## Data description:
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
