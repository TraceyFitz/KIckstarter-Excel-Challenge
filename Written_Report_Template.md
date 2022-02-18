# Kickstarting with Excel

## Overview of Project: This project utilizes prior campaign data to advise Louise on the most successful way to reach her funding goal for her new play. Analyzing prior campaign information such as location, type, goal, time of year, success and failed rates, etc we will be able to share our findings with Louise. Therefore developing the best plan of action for her campaign.

### Purpose - The purpose is to achieve funding for Louise's new play. By developing a campaign strategy similar to successful play campaigns, Louise has a better chance at achieving or perhaps even exceeding her funding goal.

## Analysis and Challenges - Analyze the most successful campaigns and which characteristics they had in common. For example timing. Is launching a campaign at different times of the year more successful or less than others? Analyzing the different types of campaigns such as theater vs technology, Film/TV, etc. We also take into account funding goals. Is there a relationship between higher goals being more or less successful? What range of funding seemed the most successful and which does not. Because there are so many types of campaigns, one of the challenges is filtering for relevant data within the same category/subcategory and removing irrelevant campaign data outside of the theater industry. There are also different countries to consider. We needed to filter by the US which is where Louise would like to run her play.

### Analysis of Outcomes Based on Launch Date - Pulling data from the main kickstarted work sheet to create a separate tab for Outcomes Based on Launch Date. Filtering by "successful," "failed," and "canceled" campaigns in the play subcategory and including the launch date filtering by years. Then adding a pivot table to drill down in the data to show for example months instead of years and the corresponding numbers of cancelled, failed and successful campaigns for each month. Then adding a line chart to visualize the data. 


### Analysis of Outcomes Based on Goals - By adding a new worksheet for Outcomes Based on Goals, we are able to see which fundraising goals are more successful. Splitting the goals into twelve dollar ranges (rows) allows us to break down the number of successful, failed and cancelled campaigns (columns) by their monetary goals. Taking into consideration the total number of projects per range in another column allowed us to calculate a percentage for each of the three categories - Successful, Failed and Cancelled. Once the percentages are calculated I created a line graph to display the data in a more visually appealing format. Percentages on the Y axis and goal ranges on the x.


### Challenges and Difficulties Encountered - The biggest obstacle when working large data sets is filtering for relevant information. Information on a technology campaign in Asia would have little use for our purposes. We want an apples to apples comparision of campaigns which will give the most insight into successful play funding campaigns.

It also would have been nice to drill down further on the location field to include city and state. Perhaps various cities are more successful than others to launch a new play fund raising campaign. 

Personally I preferred the percentages chart for the Analysis of Outcomes Based on Goals over the line chart for Outcomes Based on Launch Date. I think that would have been easier to interpret the data. I found myself calculating the percentage of the total number of campaigns in the month that were successful. It would have been easier at a glance to view a percentage of successful for each month. Although there may be a higher number of successful campaigns in a given month it should be noted there could also be a higher number of total campaigns.  

## Results - May and June are the best months to launch a theater/play campaign. In addition the $1000-$4999 funding range appears to be the most successful kickstarter goal for a play in the US. 

- What are two conclusions you can draw about the Outcomes based on Launch Date? - December appears to be the worst time of year to launch a campaign with just about half failing or canceled. In contrast May and June seem to be the most successful. 

- What can you conclude about the Outcomes based on Goals? The $1000-$4999 goal range appears to be the most successful. Followed by $5000-$9999 range. The success is relatively steady until the $25,000-$29,999 range. There are spikes trending back up to 50% in the $30,000-$34,999 range. $40,000-$49,999 range and $50,000 or more. However, that is a much smaller sample of campaigns with only about a 50% success rate.

- What are some limitations of this dataset? - We have donation amounts but it would be extremely helpful if this data set included a list of donors! If we had access to that information we could target donors who frequently give to the arts, specifically plays. Having names and contact information would be beneficial to Louise in finding funding for her play. 

- What are some other possible tables and/or graphs that we could create? As I mentioned it would have been nice to have calculated the outcomes by launch date into percentages per month. I would have liked to add that as a column in the pivot table and view the chart in that format as well. The current line chart does not take into account the total number of campaigns launched. You have to reference that in the table. If we have a percentage it would have been easier to view the success rate for each month. 
