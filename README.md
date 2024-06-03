# Google Fiber Dashboard
The final part of the Google Business Intelligence Certificate was to complete a capstone project.

The Google Fiber Call Centre Team have requested me to develop a dashboard that allows them to explore trends in repeat calls.
The team needs to understand how often customers call customer support after their first inquiry. This will help leadership understand how effectively the team can answer customer questions the first time.

# Dataset
The provided dataset is limited to the Quarter 1 of 2022.
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
You can interact with my dashboard here: [Google Fiber Dashboard | Tableau Public](https://public.tableau.com/app/profile/timothy5768/viz/GoogleFiber_Final_Project/Dash_day0andDay1Calls).


# Repeats by Month
![image](https://raw.githubusercontent.com/ctimothy14/Google-Fiber-Project/main/Dash_day%200%20and%20Day%201%20Calls.png)

The first tab of the dashboard includes two bar chats: The first chart visualises the number of repeat calls the customer service team has received in each month.
Day 0 represents the first date a customer called. For example, 1,636 customers called again one day after their initial call, but only 575 customers called again seven days later in January. 
The second chart visualised the percentage of the first contact calls by the day of the week. In January, only 8.71% of customers made first contact on Sunday. Where the majority of customers called in for the first time on Monday in January. 

# Tables
![image](https://raw.githubusercontent.com/ctimothy14/Google-Fiber-Project/main/Dash_Repeat_by_months.png)

The second tab of the dashboard includes two tables: Repeat Calls by First Call Date and Calls by Market and Type. 
The first table allows stakeholders to explore the number of different types of calls by date. The second table then separates calls into market and problem type to provide more specific information about what markets experience the most calls and the problems customers have that seem to prompt repeat calls.

# Market and Type for First Repeat Calls
![image](https://raw.githubusercontent.com/ctimothy14/Google-Fiber-Project/main/Dash_day%201%20calls%20by%20market.png)

The Market and Type for First Repeat Calls uses the data from the previous tabs table in order to further visualize the problem types that seem to generate the most repeat calls for different markets.

# Calls Across Quarter 1
![image](https://raw.githubusercontent.com/ctimothy14/Google-Fiber-Project/main/Dash_day%200%20and%20Day%201%20Calls.png)

The last tab of the dashboard inlcudes two charts to visualise the number of Day 0 calls accross amarkets and the problem types and the first repeat calls across markets and problem types.
This tab of the dashboard helps highlights and provides further insights into what markets and problems are generating calls in the first quarter of the year, as well as which products are causing the most issues for customers to be calling again after the first contact.

# Key insights
- Market_1 has the highest percentage of repeat calls, followed by Market_2 and Market_3.
- Internet and wifi (Type_5) and technician troubleshooting (Type_2) account for majority of the repeat calls

# Recommendations
- Provide further training to staff for handling internet and wifi & technician troubleshooting issues.
- Create a chatbot on the Google Fiber website which asks the customers about their issue and provide guided solutions to help solve their issue (including possible screenshots).
- Allocating more staff to market_1 to address the high call volume of repeat calls. 
