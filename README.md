# Bike Sales Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaningpreparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Result/Finding](#resultfinding)
- [Recommendations](#recommendations)
- [Limitation](#limitation)
  
### Project Overview

This project analyzes a bike sales dataset to uncover the key factors that influence customer purchasing behavior. The dataset includes demographic details (age, gender, marital status, education, income), lifestyle attributes (cars owned, commute distance, occupation, home ownership), and regional information. By examining these variables against bike purchase decisions, the project aims to identify patterns and provide actionable business insights.

### Data Sources

The dataset used in this project is the Bike Buyers dataset.xlsx file. It consists of the following column:
ID: Unique identifier for each customer record, Marital Status: Whether the customer is single or married, Gender: Male or Female, Income: Annual income of the customer, Children: Number of children in the household, Education: Highest level of education attained (Partial High School< High School< Partial college< Bachelor< Graduate), Occupation: Customer’s job category (Professional, Clerical, Skilled Manual, Management), Home Owner: Indicates if the customer owns a home, Cars: Number of cars owned by the household, Commute Distance: Distance traveled to work (e.g., 0–1 miles, 2–5 miles, 10+ miles), Region: Geographic region (Europe, Pacific, North America), Age: Age of the customer.

### Tools

Microsoft Excel was used for data cleaning, analysis, and visualization. [Download here] (https://microsoft.com)

### Data Cleaning/Preparation

To ensure accuracy and consistency, the following steps were performed on the Bike Buyers dataset.xlsx file:
- Removed duplicates: Checked for and eliminated duplicate customer records.
- Find and Replace: Utilized the find and replace function to replace abbreviations in Gender and Marital Status columns.
  - Replaced M - Male and F - Female in the Gender Column.
  - Replaced M - Married and S - Single in the Marital Status Column.
- Created category: Categorized age data into age brackets (<31;Adolescent , >=31;Middle Age, >54;Old).

### Exploratory Data Analysis

- How does age group affect bike purchases?
- Does income level influence the likelihood of buying a bike?
- What is the relationship between commute distance and bike purchases?
- Does the number of cars owned impact bike buying behavior?
- Are there differences in bike purchases across regions?
- Do gender and marital status play a role in bike purchase decisions?
- Is education level associated with bike buying trends?

### Data Analysis

For the analysis, Pivot Tables in Excel were used to summarize and explore relationships within the dataset. Key comparisons included:
- Bike Purchases by Communte Distance – to see how travel distance influences buying behavior.
- Bike Purchases by Age Bracket  – to identify the most active buyer age groups.
- Average income per purchse – to explore income distribution across male and female customers.
- Bike Purchases by Education – to understand how education level relates to buying trends.
- Interactive slicers were also applied for Cars Owned,Region,Marital Status,Occupation.

 ### Result/Finding

- Age: Customers aged 31–54 are the strongest bike buyers; purchases drop after 55.
- Commute Distance: Customers with shorter commute distances (0–5 miles) are more likely to purchase bikes, since biking is practical for short trips. Those with longer commute distances (10+ miles) tend to rely more on cars or other transport, making them less likely to buy bikes.
- Cars Owned: Customers with 0–1 cars are far more likely to purchase bikes; owning 2+ cars lowers likelihood.
- Income: Purchasers generally fall into the moderate income range; very high-income groups rely more on cars.
- Region: Europe shows higher purchase counts; Pacific customers have higher incomes but lower purchase rates.
- Occupation: Professional, clerical, and skilled manual workers are stronger buyers compared to management roles.
- Education: Partial College and High School and Bachelors groups show higher purchase rates; Graduate Degree holders purchase fewer bikes due to lifestyle factors (cars, commute, age).

### Recommendations

- Target the sweet spot profile: Middle-aged (31–54), moderate income, short commute, 0–1 cars.
- Regional focus: Strengthen marketing in Europe; in Pacific, promote premium/lifestyle bikes.
- Lifestyle positioning: Emphasize affordability and convenience for commuters with fewer cars.
- Segmented strategy:
  - For professionals and clerical workers: highlight commuting benefits.
  - For management roles: position bikes as fitness, leisure, or eco-conscious choices.

 ### Limitation

The dataset only indicates whether a bike was purchased (Yes/No) but does not include the order quantity. Having the number of bikes purchased would have provided deeper insights into customer demand and sales volume.


