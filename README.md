# Ford GoBike System Data Analysis

## Introduction

This project explores the Ford GoBike System dataset, which contains information about individual bike rides in the San Francisco Bay area. The goal of this analysis is to gain insights into bike usage patterns and factors influencing trip duration.

## Dataset

The dataset contains 183,412 rows and 16 columns.
- The Columns include information such as duration, start time, end time, start station details, end station details, bike ID, user type, member birth year, member gender, and bike share status.

## Data Preprocessing

- Data cleaning was performed to handle missing values and data type conversions.
- Three new columns were added to extract the month, day of the week, and hour of the day from the 'start_time' column for analysis.

## Data Analysis

Throughout this project, various types of data analysis were conducted to explore and understand the dataset:

- **Univariate Analysis**: Univariate analysis involves examining individual variables in isolation. This helped us understand the distribution and characteristics of each variable, such as trip duration, user type, and gender.

- **Bivariate Analysis**: Bivariate analysis focused on exploring relationships between pairs of variables. We investigated how factors like user type and gender might relate to trip duration and ride frequency.

- **Multivariate Analysis**: Multivariate analysis delved deeper by considering the interplay of multiple variables simultaneously. This allowed us to uncover more complex patterns and correlations in the data.

## Summary of Findings

1. **Busiest Times**:
   - Thursday is the busiest day of the week for bike rides.
   - The most active hours are between 7 am to 7 pm.

2. **Trip Duration**:
   - Longer trip durations are observed on weekends.
   - Rides starting between 1 am and 2 am tend to have the longest durations.

3. **User Type and Gender**:
   - On average, male riders have the shortest trip durations, followed by females, and 'other' genders.
   - Bike sharing status does not significantly influence trip duration.

4. **User Type**:
   - Customers (non-subscribers) have longer trip durations on average compared to subscribers.

5. **Gender and Ride Frequency**:
   - Men have the highest ride frequency across all days and times.

6. **Day of the Week and Time of Day**:
   - Subscribers are more active throughout the day compared to customers.
   - Peak bike usage times are 8 a.m. and 5 p.m.

## Key Insights for Presentation

In the presentation, we will focus on the following key insights:

- The average trip duration is 726 seconds.
- Weekdays are busier than weekends, with peak times at 8 a.m and 5 p.m.
- Factors like bike sharing, user type, and gender do not strongly correlate with trip duration.
- Subscribers are more active throughout the day than customers.
- Men are the most frequent riders.

## Future Work

- Further analysis could explore the impact of weather conditions on bike usage.
- Incorporating additional demographic data could provide more insights into user behavior.

## Dependencies

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

## Conclusion

This analysis provides valuable insights into bike ride patterns in the San Francisco Bay area. It can inform decision-making for improving bike-sharing services and infrastructure.
