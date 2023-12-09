# US-Electric-Grid-Outages-Uncovering-Trends-and-Insights-from-21-Years-of-Data-2002-2023-
#### Created by-Saddam Ansari

[Live link at Maven Analytics](https://mavenanalytics.io/project/10804)

#

### Project Objective:
As a Senior Analytics Consultant hired by the U.S. Department of Energy (DOE), I was tasked with analyzing a dataset of event-level power outages spanning from 2002 to 2023. The goal was to understand patterns and trends in outages, quantify their impact on communities, and identify potential weaknesses in the US electric grid. However, the provided raw data suffered from significant quality and integrity issues, necessitating a thorough data cleaning and consolidation process before any meaningful analysis could be conducted.

### About Data Set:
Information on electric disturbance events is collected using Form DOE-417 and published online in an annual summary. The dataset contains 4 files for download: An Excel spreadsheet containing the annual summaries, and 3 PDF documents for reference (the survey form, instructions, and documentation for online form submissions).

### Data Cleaning & Preparing Journey:
In this project, I was tasked with cleaning and preparing a dataset of electric shortage incidents in the United States. The dataset was provided in 21 Excel sheets, each of which contained data for a single year from 2002 to 2023. The dataset contained a variety of data types, including dates, times, numbers, and text.

So its not wrong to say the main part of this project is or skills gain Data Cleaning & Modelling.

### Data Cleaning Technique:
The first step in the data cleaning process was to combine all 21 sheets of the dataset into a single sheet. This was done using the Power Query feature in Excel.

Once the data was combined, the next step was to identify and correct any errors or inconsistencies. The following errors were identified and corrected:

#### 1. Missing or incorrect data:

Some rows in the dataset contained missing or incorrect data, such as null values, incorrect dates or times, or inaccurate numbers. I used a variety of techniques to identify and correct these errors, including:

 * Using ISBLANK and IF functions to identify and replace null values.
 * Using FIND and REPLACE functions to correct incorrect dates or times.
 * Using CLEAN and TRIM functions to remove extra spaces or characters from numbers.

#### 2. Inconsistent data formats:

The data in the dataset was stored in a variety of inconsistent formats, such as different date and time formats, different number formats, and different capitalization. I used a variety of techniques to standardize the data formats, such as:

 * Using TEXT and FORMAT functions to convert numbers to text or text to numbers.
 * Using LEFT, MID, and RIGHT functions to extract specific parts of a date or time.
 * Using UPPER and LOWER functions to change the capitalization of text.

#### 3. Range values:

Some of the data in the dataset was represented as ranges, such as "100-200" or "200-300." I used a variety of techniques to convert these ranges to single values, such as:

 * Using MIN and MAX functions to identify the minimum and maximum values in a range.
 * Using AVERAGE functions to calculate the average value in a range.


### ✨# In Data Cleaning what's I done?

 * Null values: Any rows where the demand loss in (kWh) and total people affected columns were both null or zero were removed.

 * Incorrect data types: Any columns that contained numbers in text format were converted to the correct data type.

 * Incorrect dates and times: Any dates or times that were in an incorrect format were corrected.

 * Approximate values: Any values that were approximate were replaced with the correct value.

 * Range values: Any values that were in a range were replaced with the minimum or maximum value, depending on the column.

 * Incomplete dates and times: Any rows where only the start date or time was provided were corrected.

#

### ✨# In Data Preparation what's I done?

Once the data was cleaned, the next step was to prepare it for analysis. The following steps were taken:

 * Merged date and time columns: The date and time columns were merged into a single column.

 * Calculated time difference in hours: The time difference between the start and end of each incident was calculated in hours.

 * Created a new state column: A new column was created that only showed the state of the area affected by each incident.

#

### ✨# In Additional Implementation What's I done?

In addition to the above steps, the following columns were also created:

 * Year of incident: A column was created that showed the year of each incident.
 * Month of incident: A column was created that showed the month of each incident.
 * Day of week of incident: A column was created that showed the day of the week of each incident.

#

### Challenges and Overcoming Solutions:

The data cleaning and preparation process was challenging, but it was also rewarding. The following are some specific examples of the challenges I faced and how I overcame them:

 * Data in a variety of formats: The dataset was provided in a variety of formats, including mm-dd-yy, dd-mm-yy, dd-mm-yyyy, and dd-mmmm-yyyy. I used a variety of techniques to clean and format the data so that it was consistent and easy to analyze.

 * Missing or incorrect data: The dataset contained a lot of missing or incorrect data. I used a variety of techniques to identify and correct the missing or incorrect data.

➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖
#

## *****Analysis and Finding*****

I have created six separate pages for analysis, with each page dedicated to a specific aspect. Various analyses have been conducted on each particular page:

#

### Page 1. Home

![final 1](https://github.com/user-saddam123/US-Electric-Grid-Outages-Uncovering-Trends-and-Insights-from-21-Years-of-Data-2002-2023/assets/123800896/0805ba75-6496-4f01-8120-edb4dd1c55eb)

So, In Home page I created a kip's and some visuals that's are following:

 * Total events: 3347 The total number of events that occurred in the power grid from 2002 to 2023.

 * Events where loss countable: 2228 The total number of events that resulted in a loss. This represents 56.45% of all events.

 * Events where loss none: 1719 The total number of events that resulted in no loss. This represents 43.55% of all events.

 * Total demand loss: 1.80M The total amount of demand that was lost due to events.

 * Total people affected: 363.76M The total number of people who were affected by events.

 * Avg hours of shortage per event: 37.58 The average duration of an event.

#### Additional information:

The map visualization shows the location and bubble size shows a number of event happened.

#### Interpretation:

 * The majority of events (56.45%) resulted in a loss. This suggests that there is room for improvement in power grid reliability.

 * The percentage of events that resulted in no loss (43.55%) is relatively high. This suggests that the power grid is generally reliable.

 * The total amount of demand that was lost due to events is significant. This suggests that events can have a major impact on the power grid.

 * The total number of people who were affected by events is also significant. This suggests that events can have a major impact on the public.

 * The average duration of an event is relatively short. This suggests that events are typically resolved quickly.

➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖
#

### Page 2. NERC Region Analysis

![final 2](https://github.com/user-saddam123/US-Electric-Grid-Outages-Uncovering-Trends-and-Insights-from-21-Years-of-Data-2002-2023/assets/123800896/cdf2d004-6f66-495f-9d97-44629ecd499b)

In this page I analyze only NERC Region related kip's charts and visuals that's why I named this NERC Regional Analysis:

#### Insight 1: WECC Region has the most events

 * The WECC region had the most events, with 1,098 events occurring between 2002 and 2023. This represents 22% of all events. Of these events, 489 resulted in a loss, which also represents 22% of all events with a loss.

 * The WECC region also had the most customers affected, with around 81 million people affected. This represents 22.3% of all customers affected.

#### Insight 2: SERC Region has the most demand loss

 * The SERC region had the most demand loss, with 495,000 megawatts lost. This represents 27% of all demand loss.

##### Recommendations:

Based on these insights, the following recommendations can be made to improve reliability in the NERC regions:

 * The WECC region should focus on improving its infrastructure and operations to reduce the risk of events. This could include investments in new transmission lines and substations, as well as improved operating procedures.

 * The SERC region should focus on improving its resilience to demand loss. This could include investments in distributed generation and energy storage, as well as improved demand response programs. ➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖
#

### Page 3. Area Affected Analysis:

![final 3](https://github.com/user-saddam123/US-Electric-Grid-Outages-Uncovering-Trends-and-Insights-from-21-Years-of-Data-2002-2023/assets/123800896/fe98ea7f-ee04-4cf1-ab7b-399a191278ba)

In this page I analyze only AREA related kip's charts and visuals that's why I named this Area Affected Analysis:

#### Insight 1: California has the most events:

 * California had the most events, with 282 events occurring between 2002 and 2023. This represents 13% of all events with a loss. Of these events, 282 resulted in a loss, which also represents 13% of all events with a loss.

 * California also had the most customers affected, with around 42 million people affected. This represents 11% of all customers affected.

#### Insight 2: Carolinas has the most demand loss

 * The Carolinas had the most demand loss, with 247,000 megawatts lost. This represents 14% of all demand loss.

#### Recommendations:

Based on these insights, the following recommendations can be made to improve reliability in the areas affected:

 * California should focus on improving its infrastructure and operations to reduce the risk of events. This could include investments in new transmission lines and substations, as well as improved operating procedures.

 *The Carolinas should focus on improving its resilience to demand loss. This could include investments in distributed generation and energy storage, as well as improved demand response programs.

➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖
#

### Page 4. Event Reason Analysis:

![final 4](https://github.com/user-saddam123/US-Electric-Grid-Outages-Uncovering-Trends-and-Insights-from-21-Years-of-Data-2002-2023/assets/123800896/a90b3468-4fc1-4d43-95c4-7c91dde17709)

In this page I analyze only event reason related kip's charts and visuals that's why I named this Event Reason Analysis:

#### Insight 1: Severe weather is the leading cause of events:

Severe weather is the leading cause of events, accounting for 36% of all events with a loss. This includes events such as hurricanes, tornadoes, floods, and wildfires. These events can cause widespread damage to infrastructure, leading to outages.

#### Insight 2: Severe weather also affects the most customers:

Severe weather also affects the most customers, accounting for 36% of all customers affected by events. This is because severe weather can cause widespread outages, affecting large areas.

#### Insight 3: Severe weather also causes the most demand loss:

Severe weather also causes the most demand loss, accounting for 42% of all demand loss. This is because severe weather can cause outages at large generating facilities, leading to a loss of supply.

#### Recommendations:

Based on these insights, the following recommendations can be made to improve reliability:

 * Utilities should invest in infrastructure hardening to make their systems more resistant to severe weather events. This could include investments in storm shelters, tree trimming, and undergrounding.

 * Utilities should also develop plans to improve weather forecasting. This could help them to prepare for severe weather events and to mitigate the impact of outages.

➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖
#

### Page5. Time Series Analysis:

![final 5](https://github.com/user-saddam123/US-Electric-Grid-Outages-Uncovering-Trends-and-Insights-from-21-Years-of-Data-2002-2023/assets/123800896/9a1fca49-88ef-4dcd-ac7b-120d56ff5ead)

In this page I analyze only time related kip's charts and visuals that's why I named this Time Series Analysis:

#### Insight 1: Year-based analysis:

Based on these insights, the following recommendations can be made to improve reliability:

 * Utilities should invest in infrastructure hardening to make their systems more resistant to severe weather events. This could include investments in storm shelters, tree trimming, and undergrounding.

 * Utilities should also develop plans to improve weather forecasting. This could help them to prepare for severe weather events and to mitigate the impact of outages.

 * Severe weather is the leading cause of events, accounting for 36% of all events with a loss. This includes events such as hurricanes, tornadoes, floods, and wildfires. These events can cause widespread damage to infrastructure, leading to outages.

#### Insight 2: Severe weather also affects the most customers:

Severe weather also affects the most customers, accounting for 36% of all customers affected by events. This is because severe weather can cause widespread outages, affecting large areas.

#### Insight 3: Severe weather also causes the most demand loss:

 * Severe weather also causes the most demand loss, accounting for 42% of all demand loss. This is because severe weather can cause outages at large generating facilities, leading to a loss of supply.

 * Severe weather is the leading cause of events, accounting for 36% of all events with a loss. This includes events such as hurricanes, tornadoes, floods, and wildfires. These events can cause widespread damage to infrastructure, leading to outages.

 * The years 2020, 2011, and 2008 had the most events, with 294, 287, and 271 events, respectively. These years also had the most customers affected, with around 43 million, 42 million, and 41 million people affected, respectively. The years 2019, 2011, and 2003 had the most demand loss, with 2.06 million, 1.91 million, and 1.83 million megawatts lost, respectively.

#### Recommendations:

Based on these insights, the following recommendations can be made to improve reliability:

 * Utilities should develop plans to mitigate the impact of weather events. This could include investments in infrastructure hardening and weather forecasting.

 * Utilities should also develop plans to improve communication and coordination with customers during events. This could help to reduce the impact on customers.

#### Insight 2: Month-based analysis:

The months of August, July, and June had the most events, with 29, 28, and 27 events, respectively. These months also had the most customers affected, with around 4.3 million, 4.2 million, and 4.1 million people affected, respectively. The months of January and August had the most demand loss, with 206,000 and 205,000 megawatts lost, respectively.

#### Recommendations:

Based on these insights, the following recommendations can be made to improve reliability:

 * Utilities should develop plans to manage peak demand during the summer and winter months. This could include investments in demand response programs and energy storage.

 * Utilities should also develop plans to improve the reliability of their infrastructure during extreme weather events.

➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖
#

### Page 6. Advance Analysis:

![final 6](https://github.com/user-saddam123/US-Electric-Grid-Outages-Uncovering-Trends-and-Insights-from-21-Years-of-Data-2002-2023/assets/123800896/e875a329-0f9f-4ee0-b496-8985da9c7121)

In this page I analyze some advance kip's charts and visuals that's why I named this Advance Analysis:

#### Insight 1: Event Forecasting for Next 4 Years:

 * A line chart is a good choice for this insight because it is a simple and easy-to-understand visualization that can be used to show trends over time. The chart should show the number of events expected to occur in each year for the next four years.

 * The chart can be used to identify areas where additional investments in infrastructure and operations are needed to improve reliability. For example, if the chart shows that the number of events is expected to increase in the next four years, then utilities may need to invest in new infrastructure or improve their operating procedures to mitigate the impact of events.

#### Insight 2: Decomposition Tree:

 * A decomposition tree is a hierarchical visualization that can be used to break down complex data into smaller, more manageable pieces. The tree should be used to show the factors that contribute to events.

 * The tree can be used to identify areas where improvements can be made to reduce the risk of events. For example, if the tree shows that weather events are a major contributor to events, then utilities may need to invest in infrastructure hardening or weather forecasting to mitigate the impact of weather events.

#### Insight 3: Correlation between Event and Loss by Year:

 * A correlation coefficient is a statistical measure that can be used to quantify the relationship between two variables. A correlation coefficient of 1 indicates a perfect positive correlation, a correlation coefficient of -1 indicates a perfect negative correlation, and a correlation coefficient of 0 indicates no correlation.

 * The correlation coefficient can be used to determine if there is a relationship between the number of events and the amount of demand loss. If the correlation coefficient is positive, then there is a positive relationship between the two variables. This means that as the number of events increases, the amount of demand loss also increases.

➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖
#
IF you find any problem related to this project than you can connect with me at LinkedIn link- 📌
[Linkedln](https://www.linkedin.com/in/saddam-ansari-dataanalyst)

#
#### 🙏Don't forget to like this project because its motivate me and also please follow me on LinkedIn. and Please consider me for any internship or entry level data analyst role. I need a job or internship even thought its a free or paid. Thanks in Advance.
#

Created & Presented by -

Saddam Ansari

@ Aspiring Data Analyst

Date- 08/12/2023

Place- Bihar, India
