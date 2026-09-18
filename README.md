## Tools I Used
Python, along with Pandas and NumPy for data handling, and Matplotlib/Seaborn 
for the charts.

## What I Did
- Cleaned up the data first — there were some missing values and a few 
  columns that needed their data types fixed before I could work with them
- Went through the dataset to get a feel for the customers — who they are, 
  what services they use, how long they've stayed
- Dug into which factors seemed to line up with churn the most
- Made a few charts to see the patterns more clearly instead of just staring 
  at numbers

## What I Found
- Contract type turned out to be the single biggest driver of churn — 
  customers without a long-term contract were far more likely to leave
- Customers on month-to-month contracts churned at 42.7%, compared to just 
  11.3% for one-year contracts and 2.8% for two-year contracts
- Newer customers churned far more — 47.7% of customers with less than a 
  year of tenure left, compared to only 11.9% for those with 3-6 years
- Churned customers paid more on average ($74.44/month) than retained ones 
  ($61.31/month), suggesting price sensitivity plays a role too

## What I'd Do Next
If I had more time, I'd try building a basic prediction model to flag 
customers who look like they're about to churn, so a company could actually 
step in before losing them.
