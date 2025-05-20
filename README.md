# Employee Sentiment Analysis
Exploratory data analysis as well as Linear regression performed on a test dataset
```
Top 3 Most Positive Employees:
employee_id
9    2.272727
6    2.181818
2    2.045455
```
```
Top 3 Most Negative Employees:
employee_id
8    0.909091
7    1.136364
1    1.227273
```
Flight Risk Employees:
['don.baughman@enron.com' 'john.arnold@enron.com']

**Key Insights & Recommendations:**
- Employees with consistently low sentiment scores may require managerial attention.
- Those with ≥4 negative messages in 30 days were flagged using a rolling window technique.
- Predictive modeling (linear regression) showed prior sentiment and score changes influence future sentiment.
- Suggest setting up ongoing sentiment tracking dashboards for proactive HR intervention.
"""
