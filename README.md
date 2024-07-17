# Cyclistic-Bike-Share-Case-Study
Google Data Analytics Professional Certificate's final Project

## **About the company**
In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime.

Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments. One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members.

Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Although the pricing flexibility helps Cyclistic attract more customers, Moreno believes that maximizing the number of annual members will be key to future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a very good chance to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs.

In order to answer the key business questions, I will follow the steps of the data analysis process: **Ask**, **Prepare**, **Process**, **Analyze**, **Share**, and **Act**.

I will use

- Python for the Prepare, Process, and Analyze phases.
- Power BI for the Share and Act phases.


### **Ask**
The task is to use the previous 12 months of Cyclistic trip data to understand how casual riders and annual members use Cyclistic bikes differently.

The stakeholders are:

- **Lily Moreno**: The director of marketing and my manager.
- **Cyclistic Marketing Analytics Team**.
- **Cyclistic Executive Team**.


### **Prepare**
The data has been made available by Motivate International Inc. The data is available [here](https://divvy-tripdata.s3.amazonaws.com/index.html). I downloaded the data from 07/2022 till 06/2023 as csv files.

1- Import packages and libraries

- Numpy
- Pandas
- Matplotlib.pyplot
- Seaborn

2- Read csv files to a dfs
3- Inspect a sample dataset
4- Mearging all df in one new df  

### **Process**

In this step i droped the unneeded columns

### **Analyze**

In this step i run an EDA Process to:
- Get more information about the data, including data types of each column.
- Fixing data types and removing duplicates.
- Creating new columns needed fo my analysis.
- Detecting and handling outliers.

### **Share**
I finished the Share phase on Power BI, by creating a dashboard that contains the insights needed to make the decision. You can find the dashboard [here](https://app.powerbi.com/view?r=eyJrIjoiMWRhY2QxNWItZDk1NS00NDQ5LWFlN2QtZjY5NjU4MDY4M2FiIiwidCI6ImZkZGIwMWFkLTQ5ODMtNDM2ZS1hYjM1LTFhZjA0M2I4MThjOSIsImMiOjN9) or you can find the pdf file [here](https://drive.google.com/file/d/12XKyYm81ent5oSYA45JmXDnoUU2pLEmb/view?usp=sharing).

![image](https://github.com/user-attachments/assets/f72b0983-f8e4-4c64-8864-ce12a42ec47a)

![image](https://github.com/user-attachments/assets/67aacb5e-79c7-46c6-ada8-c0bd8575eb37)

![image](https://github.com/user-attachments/assets/4273be7b-a848-45db-93e7-42a479ecb34d)


### **Act**

#### Summary
- On average, casual riders spend 11.89 minutes per ride, which is longer than the 10.04 minutes that member riders spend.
- Both casual and member riders favor electric bikes over other types of bikes.
- Summer and spring are the seasons when casual and member riders use bikes the most.
- Casual riders tend to ride more in June, July, and August, and they also ride for longer durations than member riders.
- Weekends are the preferred days for casual riders to use bikes, while weekdays are more popular for member riders.
- Casual riders usually ride during midday hours, while member riders ride more in the early morning and late afternoon.
- By comparing the top 10 locations where casual and member riders start their rides, it can be inferred that casual riders are mostly tourists who start their rides near the coast and parks. On the other hand, member riders are more likely to be locals who start their rides near offices and residential areas.

#### Recomendations
- The marketing team can launch the marketing campaign by the end of spring and continue it throughout the summer, targeting the areas near parks and coastal roads where Casual riders are more likely to use bikes.
- To attract more Casual riders to become members, the marketing campaign can offer a new membership subscription with lower prices for the rides during weekends and midday using electric bikes, which are more convenient and eco-friendly.
- To support the marketing campaign and meet the preferences of Casual riders, more electric bikes should be provided at the stations near the parks and the coastal road, especially during midday hours.
