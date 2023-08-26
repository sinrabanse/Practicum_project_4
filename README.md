# Practicum_project_4
 My fourth project from Practicum course

What was used in the project: Python, Jupyter notebook. Libraries: pandas, numpy, scipy, matplotlib, seaborn.

Project Description

I work as an analyst for the telecom operator Megaline. The company offers its clients two prepaid plans, Surf and Ultimate. The commercial department wants to know which of the plans brings in more revenue in order to adjust the advertising budget.
I am going to carry out a preliminary analysis of the plans based on a relatively small client selection. I'll have the data on 500 Megaline clients: who the clients are, where they're from, which plan they use, and the number of calls they made and text messages they sent in 2018. My job is to analyze clients' behavior and determine which prepaid plan brings in more revenue.

# Steps
1) Data preprocessing.
   - Convert the data to the necessary types
   - Find and eliminate errors in the data
2) Analyze the data.
   - Describe the customers' behavior. Find the minutes, texts, and volume of data the users of each plan require per month. Calculate the mean, variance, and standard deviation. Plot histograms. Describe the distributions.
3) Test the hypotheses.
   - The average revenue from users of Ultimate and Surf calling plans differs.
   - The average revenue from users in NY-NJ area is different from that of the users from other regions.
4) Overall conclusion.

# Description of the data
### Description of the plans
Note: Megaline rounds seconds up to minutes, and megabytes to gigabytes. For calls, each individual call is rounded up: even if the call lasted just one second, it will be counted as one minute. For web traffic, individual web sessions are not rounded up. Instead, the total for the month is rounded up. If someone uses 1025 megabytes this month, they will be charged for 2 gigabytes.

## Surf
- Monthly charge: $20
- 500 monthly minutes, 50 texts, and 15 GB of data

After exceeding the package limits:
- 1 minute: 3 cents
- 1 text message: 3 cents
- 1 GB of data: $10
## Ultimate
- Monthly charge: $70
- 3000 monthly minutes, 1000 text messages, and 30 GB of data

After exceeding the package limits:
- 1 minute: 1 cent
- 1 text message: 1 cent
- 1 GB of data: $7

The data is stored in 5 tables: users.csv, calls.csv, messages.csv, internet.csv, plans.csv
