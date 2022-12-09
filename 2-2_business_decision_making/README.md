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
