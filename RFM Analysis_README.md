# RFM Analysis

### Overview

By analyzing your customer spending and engagement behavior, it is possible to solve many problems within your organization and you can use the RFM Analysis to do it. 
RFM stands for recency, frequency and monetary value, by analyzing these three factors you can divide your customers into groups, based on their spending and engagement with your business. 
That way, you are going to be able to identify the best and the worst customers and can create custom communications and promotions according to their profiles.

This analysis is easy to implement compared to others, it is pretty simple to understand and will give you quick insights that can help you make decisions to improve your business results. 
Since the only data that you need is a **customer identification** (it could be the name, email address, phone number, client id number, etc), 
**the date of their purchases** and **the amount of each purchase**, it can be used for many business segments.

With this data, it is possible to calculate the number of transactions performed by each customer, the dates of their first and most recent purchases, 
how many months have they been in the base and the average amount of their spent per month. 

### The process

For this project, since it was a small database, I used Google Sheets and got these numbers with the following functions: **UNIQUE**, **COUNTIF**, **MAXIFS**, **MINIIFS**, **DATEDIF** and **SUMIFS**.

The next step was to rank the customers by recency, frequency and monetary value, using the **RANK** function and give them a score from 1 to 5, 
using the **PERCENTILE** and **IF** functions. 

Finally, it was time to segment the customers in six key clusters: 
- High Value
- Core
- New
- Promising
- Need Attention, and
- Lost

The results of this analysis can be used to develop different marketing strategies, for example: a company can launch a new product or service for its High Value 
customers first, so they can feel appreciated. Also, since they are the best customers to have, they can be used to create a LOOKALIKE audience when doing paid online 
advertising. For the Need Attention Customers, limited-price offers, price incentives or product recommendation are good examples of strategies to give them the 
attention they need.

### Link to the project

This project was built using Google Sheets and you can see it by clicking [here](https://docs.google.com/spreadsheets/d/1pWtgRpeL7_i6sgYP-6lpGO2wnN4cSY2VKLIf6fPsd1U/edit?usp=sharing).
