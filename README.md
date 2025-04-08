# Shield_Insurance_Analysis:
![image](https://github.com/user-attachments/assets/a7579c26-c91c-42ac-b2ed-0c0aa8566caf)

Sheild Insurance is a insurance provider offering various policies. They have gathered data from Novemeber 2022 to April 2023. They want to look at this data to make their bussiness better. They've also asked for ideas on what to include in the report and I've created a dashboard based on their requests.

## Objective:
The objective of this project is to conduct an analysis of customer growth and revenue generation. Additionally, the company aims to extract insights regarding demographic and geographic trends based on sales mode and age group across six different cities over a six-month period to leverage and maintain customer trust and satisfaction, also identify areas for improvement.

## Data Model:
![Screenshot 2025-04-08 174313](https://github.com/user-attachments/assets/bb3a4ed1-c3b9-4e89-ac86-e15519afa9b7)
This pilot project consisted of 5 tables: two fact tables and three dimension tables. The dataset was compiled from November 2022 until April 2023 and includes customers from six different cities aged 18 to 65+. Shield Insurance offered six policies through four different selling methods.

- **Dim Customer:** Contains customer demographic information.
- **Dim Policies:** Contains details about different insurance policies.
- **Dim Date:** Contains date-related data to facilitate time-based analysis.
- **Fact Premiums:** Contains data about premiums collected.
- **Fact Settlements:** Contains data about insurance settlements.

## General View:
![General View](https://github.com/user-attachments/assets/a32ce630-6d35-42db-b34f-1f53b64fc6d1)

## Sales Mode View:
![Sales Mode View](https://github.com/user-attachments/assets/28ceedb8-fdbc-4c45-9ec4-59b5a3e745e0)

## Age Group View:
![Age Group View](https://github.com/user-attachments/assets/028c662a-3fee-4b30-94fc-59060ec9285c)


## Key Findings:
- For 6 months period of time, Shield Insurance has generated 989.3 millions INR revenue, and has 26841 customers.
- Delhi is the most contributing city in terms of revenue generation, with 401.6 million INR and 11,007 customers, making it the city with the highest revenue and customer count.
- People in the age group of 31-40 years constituted the most significant buyers, with 11,146 as customers and generated 343 million INR of revenue. The middle age group dominates the customer segmentation in every city.
- In the revenue trend chart, March 2023 has experienced a significant spike in revenue and customers, with approximately an 84% increase in revenue and an 82% increase in customers compared to the previous month.
- Most of the customers make a purchase with the Offline-Agent, which holds a 55.4% share, leading to this purchase contributing 55.6% of the revenue. This shows that most of customers still prefer the traditional offline method to purchase an insurance policy.
- The Policy ID “POL2005HEL” has become the highest generated revenue with 182,3 million INR. But the majority of customers prefer the Policy ID “POL4321HEL” as their insurance plan.
- Every age group has their policy preference, for the age group of 18-24 and 25-30 is “POL4321HEL”, 31-40 is “POL3309HEL”, 41-50 is ”POL5319HEL”, 51-65 and 65+ is “POL2005HEL”
- Expected settlement refers to the approximate amount of money an insurance company expects to pay out for a claim. The biggest expected settlement is coming from the age group of 31-40 with 528 million INR.
- The majority of customers is the age group of 31-40 for each month.

