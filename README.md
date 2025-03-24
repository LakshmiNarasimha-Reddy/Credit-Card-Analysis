# CRPC8: Mitron Bank: Analysis for New Credit Card Launch 

#
## Table of Content
1. [About Mitron Bank](#about-mitron-bank)
2. [Objective of the Project](#objective-of-the-project)
3. [Problem Statment](#problem-statment)
4. [Customer Demographic Analysis](#customer-demographic-analysis)
5. [Income Utilization & Spending Analysis](#income-utilization--spending-analysis)
6. [Table Grid View Page](#table-grid-view-page)
7. [Recomendation](#recomendation-for-next-credit-card)

#
### About Mitron Bank 
[🔁Home](#table-of-content)

Mitron Bank is a legacy financial institution headquartered in Hyderabad. They want to introduce a new line of credit cards, aiming to broaden its product offerings and reach in the financial market.

### Objective of the Project 
 [🔁Home](#table-of-content)

The objective is to analyze this data and provide actionable, data-driven recommendations to guide Mitron Bank in tailoring the new credit cards to customer needs and market trends. 

### Problem Statment   
[🔁Home](#table-of-content)

 * Demographic classification: Classify the customers based on available demography such as age group, gender, occupation etc. and provide insights based on them.
   
 * Avg income utilisation %: Find the average income utilisation % of customers (avg_spends/avg_income). This will be your key metric. The higher the average income utilisation %, the more is their likelihood to use credit cards.
   
 * Spending Insights: Where do people spend money the most? Does it have any impact due to occupation, gender, city, age etc.? This can help you to add relevant credit card features for specific target groups.

 * Key Customer Segments: By doing above, you should be able to identify and profile key customer segments that are likely to be the highest-value users of the new credit cards. This includes understanding their demographics, spending behaviours, and financial preferences. 

 * Credit Card Feature Recommendations: Provide recommendations on what key features should be included in the credit card which will improve the likelihood of credit card usage. This should be backed by the insights from data provided and also some secondary research on the internet for this.
#


## Customer Demographic Analysis:   
[🔁Home](#table-of-content)

For demographic classification, I have conducted a thorough customer demographic analysis using Power BI, and here are the key findings presented in a visually engaging manner:

[![Page 1](https://github.com/LakshmiNarasimha-Reddy/Credit-Card-Analysis/blob/8162ca3b0b6f6d49fc6f2e3645090223c4fb6648/Customer%20Analysis.png)

#### Total Customers:

![1](https://github.com/LakshmiNarasimha-Reddy/Credit-Card-Analysis/blob/5d4f9d87fdf4a53a5eeff5fd24036c0ccc300978/Total%20Customers.png)

The dataset encompasses a substantial pool of 4000 customers, forming the foundation of our analysis.


#### Gender Dynamics:
![2](https://github.com/LakshmiNarasimha-Reddy/Credit-Card-Analysis/blob/9be1bd6f0275ef42727321aaaef9a123d0c50bd9/Gender.png)

 * The majority of our customer base comprises males, accounting for 64.93%, indicating a slightly male-dominated demographic.
 * However, the substantial presence of females (35.08%) highlights a diverse customer landscape.

#### Age Group Profiling:

![3](https://github.com/LakshmiNarasimha-Reddy/Credit-Card-Analysis/blob/dbe7802cf8e978fa74ee738b96746f42ac506b74/Age%20Group.png)

 * The age group 25-35 emerges as the most significant segment, with 1498 customers. This group, especially males, exhibits a strong presence.
 * Customers aged 35-45 also form a substantial portion (1273), demonstrating a balanced distribution between genders.
 * The 45+ age group, while smaller, remains a noteworthy segment that shouldn't be overlooked.

#### City-wise Distribution:

![4](https://github.com/LakshmiNarasimha-Reddy/Credit-Card-Analysis/blob/e233d5f8d184b1ba9036377f1274fe208cea7811/City.png)

 * Mumbai takes the lead in terms of customer concentration, with 1078 customers, predominantly males.
 * Other major cities like Chennai, Bangalore, and Delhi NCR also contribute significantly to our customer base.

#### Occupational Insight:

![5](https://github.com/user-saddam123/CodeBasics-Resume-Project-Challenge-8/assets/123800896/11674e74-f43c-4a41-a23b-c57f86c4a211)

 * Salaried IT Employees represent a large portion of our customers (1294), showcasing a tech-centric demographic.
 * The diversity in occupations, including freelancers and business owners, presents an opportunity to tailor services for varied professional needs.

#### Marital Status Overview:

![6](https://github.com/user-saddam123/CodeBasics-Resume-Project-Challenge-8/assets/123800896/dd8f3226-ed4e-472a-a08e-b44594b306d7)

 * A significant majority of our customers are married (78.41%), emphasizing the importance of considering family-centric financial solutions.
 * Unmarried customers, though a smaller segment, still constitute a substantial 21.6% of our customer base.
#

## Income Utilization & Spending Analysis  
 [🔁Home](#table-of-content)

In pursuit of illuminating critical insights into customer spending patterns and understanding the average income utilization across diverse segments, a dedicated analytical exploration has been undertaken. To facilitate a comprehensive understanding, a bespoke "Customers Spend Analysis" page has been meticulously crafted within Power BI. This page serves as the epicenter for unraveling intricate details, housing a plethora of Key Performance Indicators (KPIs) and insightful charts and graphs.

![Screenshot 2024-01-01 174050](https://github.com/user-saddam123/CodeBasics-Resume-Project-Challenge-8/assets/123800896/71827241-ce42-49cd-a7a0-380143a5c138)

#

#### Average Income Utilization:

![a1](https://github.com/user-saddam123/CodeBasics-Resume-Project-Challenge-8/assets/123800896/787df1ca-f219-4304-84d5-66ea1cb9f33e)

* Average Income Utilization stands at 42.82%

#### Key Metrics:

![a2](https://github.com/user-saddam123/CodeBasics-Resume-Project-Challenge-8/assets/123800896/6955c9c1-cf28-4955-9492-a1ba909b4b5f)

 * Total Income in 6 months: $1240M
 * Total Spends in 6 months: $531M

#### Total Spends by Category:

![a4](https://github.com/user-saddam123/CodeBasics-Resume-Project-Challenge-8/assets/123800896/ad937819-67b7-4136-bf61-487cd950d1d6)

 * Highest spending in bills category ($105M) with an average utilization of 46%.
 * Other significant categories: Grocery ($86M), Electronics ($80M), and the least in Others category ($16M).

#### Total Spend by Payment Type:

![a7](https://github.com/user-saddam123/CodeBasics-Resume-Project-Challenge-8/assets/123800896/5f11bc4a-cb23-4a66-821e-ce79eda9250e)

 * Credit cards dominate spending, accounting for $216M with a utilization rate of 17.45%.
 * Other payment types include UPI, debit cards, and net banking.

#### Total Spend by Gender:

![a8](https://github.com/user-saddam123/CodeBasics-Resume-Project-Challenge-8/assets/123800896/efa98410-ce19-4e79-8ce9-9930690ad91c)

 * Males lead in spending with $357M, while females contribute $154M.

#### Spend by Marital Status:

![a9](https://github.com/user-saddam123/CodeBasics-Resume-Project-Challenge-8/assets/123800896/431b646c-97a2-4d43-97ed-d8902f65bf43)

Married individuals top the spending charts with $429M, surpassing unmarried individuals at $102M.

#### Total Spend by Month:

![a10](https://github.com/user-saddam123/CodeBasics-Resume-Project-Challenge-8/assets/123800896/fe253527-5d96-464e-9f00-6df960d2fe6c)

September emerges as the highest spending month, accounting for $116M, constituting 21.84% of the total spend.

#

## Table Grid View Page:  
 [🔁Home](#table-of-content)

![3 page](https://github.com/user-saddam123/CodeBasics-Resume-Project-Challenge-8/assets/123800896/5e5baf0d-0dc8-47c1-a153-3d2ed1fa7116)

In addition to these insights, a third page has been dedicated to a detailed Table Grid View, offering a granular examination of all customer data. This tabular format enables an in-depth exploration of individual customer details, facilitating more nuanced and personalized analyses.

#
## Recomendation for Next Credit Card
[🔁Home](#table-of-content)

To improve the likelihood of credit card usage among the identified target customers (salaried employees, self-employed individuals, and freelancers), consider incorporating the following key features in the credit card:

#### Tailored Rewards Program:

Create a rewards program that aligns with the spending patterns of salaried employees, self-employed individuals, and freelancers. This could include cash back on common categories of spending such as groceries, dining, and business-related expenses.

#### Flexible Payment Options:

Offer flexible payment plans to accommodate different income structures. This could include customizable monthly payment options, allowing users to adjust their payment schedule based on their cash flow.

#### Expense Tracking and Budgeting Tools:

Provide built-in tools or partner with budgeting apps to help users track their expenses, categorize spending, and set budget goals. This can be particularly beneficial for freelancers and self-employed individuals managing variable income.

#### Low Annual Fees and Interest Rates:

Keep annual fees competitive and offer reasonable interest rates to attract and retain customers. Consider providing introductory offers, lower rates for loyal customers, or special promotions for specific spending categories.

#### Contactless and Mobile Payments:

Ensure the credit card supports contactless payments and integrates with popular mobile payment platforms. This adds convenience for users who prefer digital and contactless transactions.

#### Security Features:

Implement advanced security features such as fraud alerts, biometric authentication, and virtual card numbers to enhance the safety of transactions. Communicate these security measures to build trust among users.
#

 [🔁Home](#table-of-content)



Created & Presented by -Saddam Ansari @ Aspiring Data Analyst


Date- 03/01/2024


Place- Bihar, India
