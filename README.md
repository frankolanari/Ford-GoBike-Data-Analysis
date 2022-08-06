# Communicate-Data-Findings---Ford-GoBike-Dataset
Data Visualization, Matplotlib, Seaborn, EDA


# (Ford GoBike System DataSet Exploration)

## by (Frank Emmanuel Azibolanari)

------------------------------------------------------------------------

## Dataset

> This data set includes information about individual rides made in abike-sharing system covering the greater San Francisco Bay area. The dataset comprises of 183412 rows and 16 columns. The columns are;

-   duration_sec
-   start_time
-   end_time
-   start_station_id
-   start_station_name
-   start_station_latitude
-   start_station_longitude
-   end_station_id
-   end_station_name
-   end_station_latitude
-   end_station_longitude
-   bike_id
-   user_type
-   member_birth_year
-   member_gender
-   bike_share_for_all_trip

In addition to these columns, I created 3 extra columns to hold the month, day of the week, and hour of the day, of which I extracted from the 'start_time' column. Some of the datatypes in this dataset had to be changed to a more appropriate datatype for analysis.

------------------------------------------------------------------------

## Summary of Findings

> The findings from the data exploration includes:

-   Thursday is the busiest day of the week, and the more active times
    of the day is between 7am to 7pm... i.e by number of rides counted.

-   People travel for longer durations during the weekends, and those
    who started between 1am and 2am usually rode for the longest
    duration.

-   On average, men took the shortest time on their trips, followed by
    women and the 'other' genders took the most time. This could imply
    that the men are faster riders or perharps travel shorter
    diastances.

-   There were signifiacntly more users that didn't share bike, than
    those that shared bikes, Despite this the average trip duration were
    very close. This leads me to speculate that sharing bike or not did
    not significantly influence trip duration.

-   Generally, customers spend more time on their trips than subscribers

-   Men rode bikes more than any other gender everyday and every time during the day

-   Males have the highest number of rides and the lowest average trip
    duration.

-   subscribers are seen more during all time during the day in contrast
    to customers who are seen in mostly working hours, barely seen in
    the very late and very early hours of the day.

------------------------------------------------------------------------

## Key Insights for Presentation

> During the course of this project, we've been able to answer several question brained stormed earlier. In summary these are my findings I'll be presenting..

-  How long does the average trip take? 
-  When are most busiest start times during the day and during the week?
-  How does bike sharing, user type and gender, day of the week and start time during the day influnce trip duration?
-  How does the day of the week and time of the day influence number of rides based on gender and user type.

The average duration is 726 seconds.

The weekdays are the most busiest time during the week, with lesser activity in the weekends. During the day, the most busiest times are 8am in the morning and 5pm in the late afternoon.

Bike sharing doesn't seem to strongly determine trip duration. Customers spend more time in trips than subscribers. The other gender spend the most time during trips, followed by women, and men spend the least time on their trips. Riders that start between 2am to 3am spent the longest time during their trips, followed by users who started bewtween 11am to 3pm. Ironically, during the week riders spent the most time on their trips during the weekends and lesser during weekdays, cause there were more riders during the week and less during the weekends.  

Subscribers are more active during all times of the day than customers. Also, Men are the most active during all times of the day.
