# Statistical Data Analysis - Megaline: Which plan is better?

**Megaline** is a telecom operator and it offers its clients two prepaid plans, **Surf** and **Ultimate**.

**Surf**

- Monthly charge: &dollar;20
- 500 monthly minutes, 50 texts, and 15 GB of data
- After exceeding the package limits:
  - 1 minute: 3 cents
  - 1 text message: 3 cents
  - 1 GB of data: &dollar;10

**Ultimate**

- Monthly charge: &dollar;70
- 3000 monthly minutes, 1000 text messages, and 30 GB of data
- After exceeding the package limits:
  - 1 minute: 1 cent
  - 1 text message: 1 cent
  - 1 GB of data: &dollar;7

The commercial department wants to know which of the plans brings in more revenue in order to adjust the advertising budget. We have the data on 500 Megaline clients: who the clients are, where they're from, which plan they use, and the number of calls they made and text messages they sent in 2018.

## Project Goal

We have the information related to 500 customers of **Megaline** which includes their identity, web sessions, plan type and the number of calls and text messages they made during the year 2018. We have 5 distinct files of data available:

`megaline_calls.csv` - contains details about calls made by the customers.  
`megaline_internet.csv` - provides information on web sessions.  
`megaline_messages.csv` - contains data about text messages sent by the customers.  
`megaline_plans.csv` - includes details about the plans used by the customers.  
`megaline_users.csv` - contains information on the customers themselves.

The ask is to analyze clients' behavior and **determine which prepaid plan brings in more revenue**.

## Points Analyzed

1. Number of calls made by each user per month
2. Amount of minutes spent by each user per month
3. Number of messages sent by each user per month
4. Volume of internet traffic used by each user per month
5. Monthly revenue for each user
6. Compare average duration of calls per each plan per each distinct month
7. Compare the number of minutes users of each plan require each month
8. Check whether users on the different plans have different behaviours for their calls
9. Distribution of the monthly call duration
10. Compare average number of messages per each plan per each distinct month
11. Compare the number of messages users of each plan require each month
12. Check whether users on the different plans have different behaviours for their text messages
13. Distribution of the monthly number of messages sent
14. Compare average amount of internet traffic consumed by users per each plan per each distinct month
15. Compare the number of internet GBs users of each plan require each month
16. Check whether users on the different plans have different behaviours for their internet traffic consumption
17. Distribution of the monthly internet traffic consumption by users
18. Compare average revenue per each plan per each distinct month
19. Check whether users on the different plans have different revenues
20. Distribution of the monthly revenues

## Hypotheses Tested

1. Average revenue from users of the Ultimate and Surf calling plans differs
2. Average revenue from users in the NY-NJ area is different from that of the users from the other regions

## Libraries Used

1. `pandas`
2. `numpy`
3. `matplotlib`
4. `scipy`
5. `seaborn`

## Kaggle Notebook Link

[Statistical Data Analysis for Telecom Operator](https://www.kaggle.com/code/shraddha0/statistical-data-analysis-for-telecom-operator)
