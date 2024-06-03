# Google Fiber Dashboard
The final part of the Google Business Intelligence Certificate was to complete a capstone project.

The Google Fiber Call Centre Team have requested me to develop a dashboard that allows them to explore trends in repeat calls.
The team needs to understand how often customers call customer support after their first inquiry. This will help leadership understand how effectively the team can answer customer questions the first time.

# Dataset
The data provided has been anonymized and approved by the Google Fiber Call Center team which includes:
- Number of calls
- Number of repeat calls after first contact
- Call type
- Market city
- Date

In order to anonymize the data, the datasets the columns market_1, market_2, and market_3 to indicate three different city service areas the data represents. 
The data also lists five problem types:
- Type_1 is account management
- Type_2 is technician troubleshooting
- Type_3 is scheduling
- Type_4 is construction
- Type_5 is internet and wifi

I first uploaded the three different market.csv's into Big Query and performed a UNION ALL to have all three csv's merged into one target_table csv file. The target_table csv.file was then uploaded into Tableau to create the dashboard.

## Stakeholder's Questions:
- How often are customers calling repeatedly?
- The frequency of customers following up within the next 7 days after their first call with the customer service team?
- What are the main issues which are generating repeat calls?
- Which market city receives the most repeated calls?

## Deliverables and metrics:
The dashboard which I have created will provide further insights and answer the following questions for the Google Fiber team:
- Help them understand how often customers are calling customer support after their first inquiry; this will help leadership understand how effectively the team is able to answer customer questions the first time.
- Provide insights into the types of customer issues that seem to generate more repeat calls.
- Explore repeat caller trends in the three different market cities.
- Design charts so that stakeholders can view trends by week, month, quarter, and year.


# My Dashboard
The provided dataset is limited to the Quarter 1 of 2022. 
You can interact with my dashboard here: [Google Fiber Dashboard | Tableau Public](https://public.tableau.com/app/profile/timothy5768/viz/GoogleFiber_Final_Project/Dash_day0andDay1Calls).


# Repeats by Month
![image](https://raw.githubusercontent.com/ctimothy14/Google-Fiber-Project/main/Dash_day%200%20and%20Day%201%20Calls.png)

The first tab of the dashboard includes two bar chats: The first chart visualises the number of repeat calls the customer service team has received in each month.
Day 0 represents the first date a customer called. For example, 1,636 customers called again one day after their initial call, but only 575 customers called again seven days later in January. 
The second chart visualised the percentage of the first contact calls by the day of the week. In January, only 8.71% of customers made first contact on Sunday. Where the majority of customers called in for the first time on Monday in January. 

# Tables
![Dash_table](https://github.com/ctimothy14/Google-Fiber-Project/assets/93518336/8180fd8f-239b-45c3-bffa-6cf3f2d2fb44)

The second tab of the dashboard includes two tables: Repeat Calls by First Call Date and Calls by Market and Type. 
The first table allows stakeholders to explore the number of different types of calls by date. The second table then separates calls into market and problem type to provide more specific information about what markets experience the most calls and the problems customers have that seem to prompt repeat calls.

# Market and Type for First Repeat Calls
![Dash_day 1 calls by market](https://github.com/ctimothy14/Google-Fiber-Project/assets/93518336/3266d9d4-d3f5-404d-a34d-b0b63667927d)

The Market and Type for First Repeat Calls uses the data from the previous tabs table in order to further visualize the problem types that seem to generate the most repeat calls for different markets. 
