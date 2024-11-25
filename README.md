# Car Claims Dashboard

This project is an overview of car claim trends and patterns over the past 5 years and current year. It highlights the claim amounts, claim frequency, rish and dempgraphic insights. The dashboard offers insights for managing insights for managing risks, optimizing pricing strategies, and targeting specific groups for safer driving initiatives.

## Tools-Used
- Ms. Excel
  1. Data Cleaning
  2. Data Analysis
## MicroSoft PowerBi
  1. DAX Analysis
  1. Major tool for visualization
### Data Cleaning
I performed the following actions
  1. Data loading and inspection
  2. Data cleaning and formatting
### Exploratory Data Analysis
The EDA involved exploring the data to solve some questions such as:
- The claim frequecy over the years
- Create income band
- Experience band
- Distance of work band
- Claim amount by the income and age band


![Car Claims Analysis](https://github.com/user-attachments/assets/455255c2-7d4b-4566-b16f-ea1b9504de56)

### Data Analysis
Basic DAX Analysis
```
Income Band = SWITCH(TRUE(),'Car Claims'[Income]>=0 && 'Car Claims'[Income]<=10000,"Below Minimum Wage"
,'Car Claims'[Income]>10001 && 'Car Claims'[Income]<=50000,"Low Income"
,'Car Claims'[Income]>=50001 && 'Car Claims'[Income]<=100000,"Mid Income"
,'Car Claims'[Income]>=100001 &&'Car Claims'[Income]<=150000,"High Income"
,'Car Claims'[Income]>150000,"High Net Income")
```
### Suggestions and Reccomendations
From the result of the analysis carried out here are few suggestions
- Develop specialized insurance packages tailored to new car owners, providing comprehensive coverage for higher repair costs. Create policies for short- and long-distance drivers to align premiums with risk exposure and introduce flexible options for specific age groups like middle-aged and elderly customers.
- Premiums should be increased for high-risk groups, such as low-income individuals and new car owners, as they account for higher claim amounts. Discounts can be offered to high-income groups, older car owners, and customers with no-claims history to incentivize safe driving.

  ![Car Claims Analysis](https://github.com/user-attachments/assets/6c21358d-1778-44d2-b2e7-ca4ea8cbdfc6)
