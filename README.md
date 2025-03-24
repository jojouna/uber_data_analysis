# Uber - Insights from City Supply and Demand Data

This is an analysis of Uber's dataset that contains 2 weeks data of app user and the driver. Please see the [Data Analysis-Uber.ipynb](https://github.com/jojouna/uber_data_analysis/blob/main/Data%20Analysis-Uber.ipynb) to deep dive into how the analysis was performed. 

This readme contains only the answers to the questions. 

## Data Description
`Time`: Hour in 24 hours format (e.g 16 = 4pm)
`Eyeballs`: Number of people who opened the app on that time
`Zeroes`: Number of people who did not see any car
`Completed Trips`: Number of trips that were completed
`Requests`: Number of people who requested the car
`Unique Drivers`: Total drivers who logged in during that time


## Assignment
Using the provided dataset, answer the following questions:

1. Which date had the most completed trips during the two week period?
  <br>Answer: Date with the most completed trip: 2012-09-22

2. What was the highest number of completed trips within a 24 hour period?
  <br>Answer: Highest number of completed trips in 24 hour period: 278.0

3. Which hour of the day had the most requests during the two week period?
  <br>Answer: Time with the most requests: 23 hour

4. What percentages of all zeroes during the two week period occurred on weekend (Friday at 5 pm to Sunday at 3 am)? Tip: The local time value is the start of the hour (e.g. 15 is the hour from 3:00pm - 4:00pm)
  <br>Answer: Percentage of all zeroes on weekend: 44.86%

5. What is the weighted average ratio of completed trips per driver during the two week period? Tip: "Weighted average" means your answer should account for the total trip volume in each hour to determine the most accurate number in whole period.
  <br>Answer: Weighted average ratio of completed trips per driver: 0.83

6. In drafting a driver schedule in terms of 8 hours shifts, when are the busiest 8 consecutive hours over the two week period in terms of unique requests? A new shift starts in every 8 hours. Assume that a driver will work same shift each day.
  <br>Answer: The busiest 8 consecutive hours: 2012-09-21 16:00:00 - 2012-09-22 00:00:00

7. True or False: Driver supply always increases when demand increases during the two week period. Tip: Visualize the data to confirm your answer if needed.
  <br>Answer: False

8. In which 72 hour period is the ratio of Zeroes to Eyeballs the highest?
 <br> Answer: 72 hour period with the highest ratio of Zeroes to Eyeballs: 2012-09-15 05:00:00 - 2012-09-18 05:00:00

9. If you could add 5 drivers to any single hour of every day during the two week period, which hour should you add them to? Hint: Consider both rider eyeballs and driver supply when choosing
  <br>Answer: Hour to add 5 drivers: 23

10. True or False: There is exactly two weeks of data in this analysis
 <br> Answer: False

11. Looking at the data from all two weeks, which time might make the most sense to consider a true "end day" instead of midnight? (i.e when are supply and demand at both their natural minimums) Tip: Visualize the data to confirm your answer if needed.
  <br>Answer: True end day: 4 am
  
