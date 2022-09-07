# Bank_Marketing_Term_Deposits

## Project Overview

We have a marketing campaign dataset from a Portuguese bank offering clients to open term deposits. It is a telemarketing campaign that directly contacts the clients and persuade them to agree to opening term deposits. We will be creating a classification algorithm and also suggest them the insights we derive from this dataset and also help them to narrow down their leads into marketing funnel for a more successful campaign.

## Problem Statement

There has been a revenue decline for the Portuguese bank and they would like to know what actions to take. After investigation, we found out that the root cause is that their clients are not depositing as frequently as before. Knowing that term deposits allow banks to hold onto a deposit for a specific amount of time, so banks can invest in higher gain financial products to make a profit. In addition, banks also hold better chance to persuade term deposit clients into buying other products such as funds or insurance to further increase their revenues. As a result, the Portuguese bank would like to identify existing clients that have higher chance to subscribe for a term deposit and focus marketing effort on such clients.

## Dataset

- Available on [Kaggle](https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing)

## Tools Used
- Python (Pandas, Numpy, Matplotlib, Seaborn, Scikit-Learn)
- Jupyter Notebook

## About the Data

 The dataset contains 41,188 rows and 21 columns. The features are as follows :
 
 #### Bank Client Data
 
 1. Age : Age of the lead (numeric)
 2. Job : type of job (Categorical)
 3. Marital : Marital status (Categorical)
 4. Education : Educational Qualification of the lead (Categorical)
 5. Default: Does the lead has any default(unpaid)credit (Categorical)
 6. Housing: Does the lead has any housing loan? (Categorical)
 7. loan: Does the lead has any personal loan? (Categorical)
 8. Contact: Contact communication type (Categorical)
 9. Month: last contact month of year (Categorical
 10. day_of_week: last contact day of the week (categorical)
 11. duration: last contact duration, in seconds (numeric)
 12. campaign: number of contacts performed during this campaign and for this client (numeric)
 13. pdays: number of days that passed by after the client was last contacted from a previous campaign(numeric; 999 means client was not previously contacted))
 14. previous: number of contacts performed before this campaign and for this client (numeric)
 15. poutcome: outcome of the previous marketing campaign (categorical)
 16. emp.var.rate: employment variation rate - quarterly indicator (numeric)
 17. cons.price.idx: consumer price index - monthly indicator (numeric)
 18. cons.conf.idx: consumer confidence index - monthly indicator (numeric)
 19. euribor3m: euribor 3 month rate - daily indicator (numeric)
 20. nr.employed: number of employees - quarterly indicator (numeric)
 21. y - has the client subscribed a term deposit? (binary: 'yes','no') **Target Feature**

## Data Exploration and Visualization

#### Campaign Outcome

![](images/campaign_outcome.png)
 
