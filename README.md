## About this project ##

## Data Preparation/ Transformation

I used Power Query to clean and transform the data before analysis. Some key steps taken include:

- Performed data profiling to check for data consistency.
- Created calculated columns.
- Changed data types to appropriate data types for the various columns.
- Created a separate Date Table for time series analysis.
- Split the date column into dates and components such as - Month, Quarter, Time, Hour, etc.
- Converted milliseconds to minutes by dividing milliseconds by 60000, which were then converted into hours.
- Loaded the data into Power BI Desktop to perform the following steps:
- Created a one-to-many relationship between the data table and the Spotify history table using the date as the primary key.
- Created a table for calculated measures to ensure a single collection for all the measures.
- Hide unnecessary columns from the report view.

## Dashboard Design

The dashboard consists of 4 pages, namely:-

- Summary level page with all the key and high-level metrics.
- A page dedicated to the analysis of different types of tracks.
- Time series analysis for in-depth analysis to find any patterns or trends.
- A page consisting of analysis at the artist and album level to find out the top preferences of the user.

## Insights

- Favourite track: Ode to the Mets 
  Favourite Artist: The Beatles 
  Favourite Album: The Beatles
- Android made up 93.43% of streams with Web Player accounting for the least. This can be further dug into to find the reasons behind such a stark difference between Android and mediums.
- Paraiso was the most skipped song (29 times).
- Ups and downs in listening activity have been observed over the years. The recent years have been less engaging compared to the 2020-21 period.
- Peak listening hours have been observed during the 5-7 pm window while the least preferred slot is the 12-1 pm shift.
- It had to be FRI-YAY. The day with the most activity.
- 3rd and 4th Quarters have been the biggest hits, hinting at a cool-off period for the user.
- The user prefers exploring new tracks on weekdays over weekends.
