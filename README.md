# Telecom-Churn-Case-Study_Random-Forest
![pasted-image-0-1024x513](https://user-images.githubusercontent.com/84779271/174470083-9394270d-4440-461a-ab29-4925d99d84e7.png)

In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.
In this Telecom churn case study we are using Pareto principle which says that approximately 80% of revenue comes from the top 20% customers called high-value customers.
Revenue-based churn: Customers who have not utilised any revenue-generating facilities such as mobile internet, outgoing calls, SMS etc.
Usage-based churn: Customers who have not done any usage, either incoming or outgoing - in terms of calls, internet etc. over a period of time.
The dataset contains customer-level information for a span of four consecutive months - June, July, August and September. The months are encoded as 6, 7, 8 and 9, respectively.
The business objective is to predict the churn in the last (i.e. the ninth) month using the data from the first three months. In churn prediction, I assume that there are three phases of customer lifecycle.
The ‘good’ phase: In this phase, the customer is happy with the service and behaves as usual.
The ‘action’ phase: The customer experience starts to sore in this phase.
The ‘churn’ phase: In this phase, the customer is said to have churned.
We are working over a four-month window, the first two months are the ‘good’ phase, the third month is the ‘action’ phase, while the fourth month is the ‘churn’ phase
