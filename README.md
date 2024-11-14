# CRM-Analysis
**Business Question:** What factors are most predictive of customer churn in a subscription-based service, and how can we identify at-risk customers early?

For this analysis, I have used an IBM dataset called ‘Telco Customer Churn.’ It consists of 21 columns and 7043 unique values. The key metrics I have used were tenure, contract type, total spendings, and finally tech-support usage. 

**Methodology:** The analysis included multiple nested ‘if statements’ in Excel. The dataset had a churn column; but the tenure and the total spending columns contained a lot of different values. Hence, I have divided them into different groups. For the tenure column, based on months, I created the ‘New Customer’, ‘Early Customer’, ‘Established Customer’, and finally ‘Long Term Customer’ categories. For the total spendings column, I created the ‘Low’, ‘Moderate’, ‘High’ and ‘Premium’ spender categories. The tech-support and the contract type columns did not need any adjustments


<img width="669" alt="Screenshot 2024-11-14 at 22 32 25" src="https://github.com/user-attachments/assets/82374278-cf54-4740-93b6-52905e8699fb">


**Findings:** As seen from the graphs, over 50% of new customers, 43% of month-to-month contract customers, over 35% of low spenders, and finally the 42% of customers who do not use tech-support tend to churn. To have a general overlook at the churn risk situation, I have created a model where I gave 1 point to each of these parameters. A customer who is new, who does not use tech-support, who has a month-to-month contract, and who is a low spender would have 4 points and would be considered a ‘high-risk customer.’ The customers who scored only a single point were ‘low-risk customers;’ the customers who scored 2-3 points were ‘medium-risk customers’ and the ones who did not score any points were the ‘safe customers.’ Luckily, the dataset did not have any high-risk customers. Here’s a graph of the total distribution: 


<img width="408" alt="image" src="https://github.com/user-attachments/assets/9300d2ab-c00c-4213-b04a-6d7c407bf54f">


**Suggestions:** For the new customers, our objective should be to make them long term. Thus, we may plan certain incentives for them such as regular follow-ups for the first couple of months. Furthermore, we should also focus on encouraging long-term contracts. I believe that discounts or certain merits would be very effective for this goal. The tech-support accessibility is also worth considering. Although only 7% of the customers do not have internet access, we can still make the tech-support channel more accessible and easier to use for those who already have internet access as most of the churned customers did not even use this service. Lastly, we can consider implementing loyalty awards for customers who spend up to a certain limit. As the amount a customer spends in total goes up, they become less likely to churn. 
