## business_decision_making

Data analysis was carried out. Various metrics were calculated, cohort analysis was used: LTV, CAC, Retention rate, DAU, WAU, MAU, etc. Previously written metric calculation functions were used. Correct conclusions have been drawn based on the data obtained.

## Data:
### hypothesis:
- `Hypothesis` — a brief description of the hypothesis;
- `Reach` — user coverage on a 10-point scale;
- `Impact` — impact on users on a 10-point scale;
- `Confidence` — confidence in the hypothesis on a 10-point scale;
- `Efforts` — the cost of resources to test the hypothesis on a 10-point scale. The greater the value of Efforts, the more expensive hypothesis testing is.

### orders:
- `TransactionID`— order ID;
- `visitorID` — ID of the user who made the order;
- `date` — the date when the order was made;
- `revenue` — order revenue;
- `group` — the A/B test group that the order fell into.

### visitors:
- `date` — date;
- `group` — A/B test group;
- `visitors` — the number of users on the specified date in the specified A/B test group.

## Results
The P-value for the average receipt after data extraction changed from 72.9% to 61.7%, but still remained more than 5%. So we still cannot reject the null hypothesis and assume that there are differences in the average check. But after clearing the data, the ratio of the average check of group B to group A. Before clearing the data, the average check of group B was significantly higher than the average check of group A - 25.9%, and now they have changed places. Now the average check of group A is more than the check of group B - 6%.
- p-value=1.4% for conversion after data clearing, which is less than the 5% threshold value. So, we reject the null hypothesis that there are no statistically significant differences in conversion between the groups. The relative gain of Group B over Group A increased from 13.8% to 18.1% after clearing the data.

## Stage
Project is fully completed
