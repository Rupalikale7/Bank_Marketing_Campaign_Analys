# Bank Marketing Campaign Analysis
Introduction:
This report presents a comprehensive analysis of a bank’s marketing campaign data. The primary goal is to understand customer behaviours and campaign effectiveness and economic indicators to understand customer behaviour and improve marketing strategies. The final goal is to predict whether a client subscribes to a term deposit based on historical data.
This report aims to explore and analyse the dataset on Bank Marketing Campaign Analysis. Let's delve into the details:
1.	Data Overview:
•	The dataset contains detailed information about a bank’s marketing campaigns. 
•	It includes customer details such as age, job, marital status, and education. Financial information is also provided, including whether the customer has a housing loan, personal loan, or any credit in default. Additionally, the dataset includes economic indicators like employment rate, price index, and consumer confidence index at the time of contact. The final outcome indicates whether the customer subscribed to a term deposit (1 for yes, 0 for no). There are no missing values in the dataset.
2.	Data Acquisition and Preprocessing:
•	The Bank Marketing Campaign data was loaded from a CSV file using pandas. Data types were validated and no missing values were found. Columns with text values like job, marital status, and education were checked to make sure the data was clear and consistent. Number based columns were checked for any unusual values and to understand basic things like average, minimum, and maximum.
3.	Exploratory Data Analysis (EDA):
•	To begin the analysis, we examined both the numerical and categorical features in the dataset. For the numerical columns, we used df.describe() to view basic statistics like the average (mean), minimum, and maximum values. Next, we explored categorical columns using value_counts() to see how the data is distributed.
•	Customer profiles such as job and education were examined to identify trends in term deposit subscription rates. Bar plots showed that certain job categories and education levels had higher proportions of successful subscriptions (y = 1).
•	The correlation matrix in the provided analysis explores the relationships between input features (age, campaign, duration) and 
the target variable y (term deposit subscription).

4.	Client Profile Analysis:
•	Analysis of customer profiles revealed that how a person’s marital    status affects their decision to subscribe to a bank’s offer. It shows that married and divorced people are a little more likely to say “yes” compared to single people. The chart also shows that most people said “no”, and only a small number said “yes.
5.	Campaign Effectiveness:
•	The analysis aimed to find out if longer phone calls increase the chances of a customer saying “yes” to a bank offer. To do this, we used a box plot and scatter plot to compare call durations between those who subscribed and those who didn’t. The plots showed that people who said “yes” usually had longer calls. We also calculated the average duration and found that subscribers talked for about 553 seconds on average, while non-subscribers talked for only about 221 seconds. A bar chart confirmed this difference. So, in simple terms, the longer the call, the more likely the customer is to say “yes” to the offer.
•	The analysis aimed to find out which contact method (telephone or cellular) is more effective for getting customers to subscribe. We grouped the data by contact method and looked at how many people said "yes" to the bank offer. We found that cellular contact had a higher success rate (about 14.3%), while telephone contact had a lower rate (around 5.2%). We used a bar plot to compare both methods visually, and it clearly showed that cellular is more effective.
•	The analysis aimed to find out how many times does a customer need to be contacted before they say “yes”. To find out, we calculated the average number of contacts (calls) made before customers subscribed. The results showed that people who said "no" were contacted about 2.63 times on average, while those who said "yes" were contacted fewer times, about 2.05 times. We also used a box plot to see the distribution and found that more contacts don’t always help. which means that reaching out too many times may not increase success and could even reduce interest.
6.	Preview Campaign Impact :
•	The outcome of previous marketing campaigns has a clear influence on the success of the current campaign. Customers with a successful previous campaign are much more likely to subscribe (65%) than those with no contact (9%) or past failure (14%).
•	Clients with previous contacts generally have higher subscription rates, especially when contacted 3–5 times, where success exceeds 50%, compared to only 8.8% with no prior contact.
7.	Temporal Analysis :
•	The analysis aimed to find out in which month have higher subscription rates, Subscription rates are highest in March (50.5%), December (48.9%), October (43.9%), and September (44.9%), while lowest in May (6.4%) and July (9.0%).
•	Subscription rates are similar across weekdays, ranging from about 10% to 12%, with no significant day-of-week advantage.
8.	Conclusion :
•	This project focused on analyzing the Bank Marketing Dataset, which contains information on clients, previous marketing campaigns, and whether the client subscribed to a term deposit (y). The main objective was to explore patterns, understand key influencing factors, and identify strategies to improve future campaign success.


