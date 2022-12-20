# Project name: A/B test results analysis

## Discription
**Context**

It is necessary to increase the revenue of a large online store, for this you need to select priority hypotheses, run an A/B test and analyze the results

**Data contains:**

*File /datasets/hypothesis.csv:*

- Hypothesis — brief description of the hypothesis;
- Reach — user coverage on a 10-point scale;
- Impact — impact on users on a 10-point scale;
- Confidence — confidence in the hypothesis on a 10-point scale;
- Efforts — resource costs for hypothesis testing on a 10-point scale. The larger the Efforts value, the more expensive it is to test the hypothesis.

*File /datasets/orders.csv:*

- transactionId — order ID;
- visitorId — ID of the user who made the order;
- date — the date the order was placed;
- revenue — order revenue;
- group — the A/B test group the order is in.

*File /datasets/visitors.csv:*

- date — date;
- group — A/B-test group;
- visitors — number of users on the specified date in the specified A/B test group

The **goal** of the project:
- Prioritize hypotheses using ICE and RICE methods
- Analyze A/B test results

## Key results:

### Hypotheses prioritization
Based on the results of the two methods, we can say that the most priority are hypotheses:
- Add a subscription form to all main pages to build a customer base for email newsletters
- Add blocks of product recommendations to the website of the online store to increase conversion and average check of the order
- Add two new channels to attract traffic, which will attract 30% more users

### A/B test results
- There are statistically significant differences in the average number of orders between groups for both raw and data after filtering out anomalies.;
- There is no statistically significant difference in the average check between the groups, neither according to the "raw" nor according to the data after filtering out anomalies;
- A graph showing the difference in conversion between groups shows that group B performed significantly better than group A.
- The graph of the difference in the average check shows that the results of group B are deteriorating day by day, but are now at about 30%

Thus, it is necessary to stop the test, recognize it as successful and move on to testing the next hypothesis.
