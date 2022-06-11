# Kickstarting with Excel

## Overview of Project
The following is a brief analysis of how launch date and goal amount affects the success or failure of a Kickstarter campaign in meeting its funding goals. 

### Purpose
Understanding the history of successes and failures in past Kickstarter campaigns can better inform a potential entrepreneur on what time of year might lend the most success in starting their campaign and how much money they can realistically expect to request to be successful in launching their product.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To see how different campaigns fared based on launch date, I created a pivot table comparing the number of successful, failed, and canceled campaigns across each month. This table is filterable by year, allowing sight into trends over the entirety of the dataset or drilled down into years of interest from 2009 to early 2017. It is also filterable by parent category to allow sight into other Kickstarter campaign types to determine if they follow similar trends based on the date launched.

![Theater Outcomes By Launch Date](https://user-images.githubusercontent.com/102555125/173203797-3322926a-f238-4640-a910-c5901bc268e3.png)

### Analysis of Outcomes Based on Goals
To see how different campaigns fared based on fundraising goal, I created a table aggregating the number of successful, failed, and canceled campaigns into dollar amount ranges. The chart further broke the data down into percent of how many total campaigns in those ranges succeeded, failed, or were canceled.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/102555125/173203923-c552929d-953d-4a73-b340-b65b1c6f6795.png)

### Challenges and Difficulties Encountered
The challenges in both these subsets of data is that some months and ranges have few campaigns that fit into them so it will not be possible to draw accurate conclusions if those months/ranges are the information you are interested in. It is difficult to see an accurate trend in such a small sample size.  For example: there are 534 campaigns with goals ranging from $1000 to $4999.  There is only one campaign in the goal range of $45,000 to $49,999.  While this graph may reasonably show a trend for campaigns with goals from $1000 to $4999, since there are 534 campaigns to draw inference from, the data for campaigns with goals ranging from $45,000-$49,999 only has one campaign to draw inference from.   

## Results
