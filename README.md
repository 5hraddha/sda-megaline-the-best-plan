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

## Libraries Used

1. `pandas`
2. `numpy`
3. `matplotlib`
4. `scipy`
5. `seaborn`
