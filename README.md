# surfs_up

## Overview
Fictional company Waves and Ice Cream wants to analyze weather data using SQLite to see if it is worth openning a surf shop on Oahu and determine if it has good business value. We ran the queries separately and turned the results into a data frame and we also gathered the statistics through the function .describe() to better understand and compare the data for the two months.

## Resources
- Jupyter Notebook
  - Python v3.x
    -Pandas
    -Numpy
    -SQLAlchemy
    
- [hawaii.sqlite](https://github.com/NensiH/surfs_up/blob/main/hawaii.sqlite)

## Results
- ### June and December Temperature Findings
Using Python, Pandas , and SQLAlchemy, the date column of the Measurements table was filtered in the hawaii.sqlite database to retrieve all the temperatures for the months of June and December. Those temperatures were converted to a list, a DataFrame was created from those lists, and then summary statistics were generated for each dataset. After conducting the analysis, we gather the following statistics for the months of June and December.

June temperature had a min of 64.00, max of 85.0 and a mean of 74.9.

<img width="146" alt="Screen Shot 2021-12-15 at 9 46 23 AM" src="https://user-images.githubusercontent.com/92277581/146618502-bd87bd03-cc15-4289-b710-e9c83e60dff9.png">

December temperature had a min of 56.00, max of 83.0 and a mean of 71.0.

<img width="167" alt="Screen Shot 2021-12-15 at 9 47 30 AM" src="https://user-images.githubusercontent.com/92277581/146618524-19ac6bc0-349c-4750-b653-17c30854f409.png">

The difference in the standard deviation between June and December temperature was only 0.49 since the standard deviation for June is "3.25" and "3.74" in December, showing there is not a significant difference in the two months.

- ## Additional Analysis
### June and December Precipitation Findings
The process to acquire statistics on precipitation for June and December was the same as the process for finding temperature statistics.

June and December precipitation statistics showed the following:

<img width="146" alt="Screen Shot 2021-12-17 at 5 22 10 PM" src="https://user-images.githubusercontent.com/92277581/146618706-ef8e99b3-96c8-499b-869b-32d7c7cbb3aa.png"> <img width="149" alt="Screen Shot 2021-12-17 at 5 22 19 PM" src="https://user-images.githubusercontent.com/92277581/146618745-f5b46627-053c-43c3-9c93-7b9b8df72188.png">

## Summary
The temperatures in December are slightly lower than June but suitable for a surf and ice cream shop business. That shows that for most months of the year, there will be enjoyable temperature for people to come and use the surf shop.

By looking at the further analysis it shows that there is little amount of percipitation on a normal day, but there is still days with excessive rainfall. This shows that the surf shop will be able to stay open on most days while a few rainy days will help keep the island ecosystem lush and inviting to people wanting to visit the surf shop.
