# Analysis-of-Airline-On-Time-Performance-Dataset   

## Project Overview
This project focuses on analyzing the Reporting Carrier On-Time Performance Dataset from the United States Bureau of Transportation Statistics. The dataset consists of approximately 200 million domestic US flights. It contains detailed information on each flight, such as the flight date, departure time, departure and arrival airports, arrival delays, and reasons for delays. The aim is to analyze various flight patterns, delay behaviors, and identify insights related to flight timings, airlines, and destinations.

The dataset can be used for various purposes, including predicting the likelihood of a flight arriving on time and understanding factors influencing delays. The dataset can be found here : https://dax-cdn.cdn.appdomain.cloud/dax-airline/1.0.1/data-preview/index.html

## Data Summary
The dataset includes the following columns (with basic definitions):

Date: The date the flight was operated.
Time: The scheduled departure time.
Departure Airport: The airport from which the flight departs.
Arrival Airport: The airport where the flight arrives.
Departure Delay: The delay in departure, in minutes.
Arrival Delay: The delay in arrival, in minutes.
Carrier: The airline reporting the flight.
Flight Number: The unique identifier for the flight.
Reason for Delay: If the flight was delayed, this column indicates the reason (e.g., weather, security, etc.).
## Visualizations and Findings
1. Scatter Plot (Distance vs Departure Time)
What I Did:

I created a scatter plot to analyze the relationship between distance and departure time. This allowed me to explore whether shorter or longer flights are more likely to have specific departure times.
How I Did It:

I grouped the data by flight distance and departure time.
A scatter plot was generated using Plotly to compare distance (x-axis) with departure time (y-axis).
Findings:

Shorter flights have a more evenly distributed set of departure times, whereas longer flights are limited to specific times across the day, indicating operational constraints.
Key Insight:

Shorter flights tend to have more flexible departure windows, while longer flights are more restricted to certain times due to their duration.
2. Line Plot (Average Flight Delay Time by Month)
What I Did:

I created a line plot to show the variation of average flight delay times over the months of the year.
How I Did It:

The data was grouped by month, and I calculated the average arrival delay for each month.
A line plot was created to visualize how average delays change from month to month.
Findings:

June showed the highest average arrival delay, with delays around 17.31 minutes.
November had the lowest average delay, where the average delay was negative (indicating that many flights arrived early).
Key Insight:

June seems to be a peak season for delays, possibly due to increased travel demand or weather conditions.
3. Bar Chart (Number of Flights per Reporting Airline to a Destination State)
What I Did:

I used a bar chart to represent the number of flights each airline operates to various destination states.
How I Did It:

Data was grouped by destination state and reporting airline.
A bar chart was plotted to show the number of flights from each airline to each state.
Findings:

California (CA) had the highest number of flights, with 68 flights.
Vermont (VT) had the least number of flights, with only 1 flight.
Key Insight:

California, being a major travel hub, received the highest number of flights, while smaller states like Vermont had fewer flights, likely due to lower demand.
4. Histogram (Arrival Delay Distribution)
What I Did:

I created a histogram to visualize the distribution of arrival delays.
How I Did It:

Missing values for arrival delays were handled appropriately, and the data was plotted as a histogram using Plotly.
Findings:

Most arrival delays were in the 20-25 minute range, with approximately 17 flights falling into this category.
The maximum number of flights with delays over 50 minutes was only 5.
Key Insight:

Most flights had relatively short delays, with only a few experiencing significant delays of over 50 minutes.
5. Bubble Chart (Month vs Number of Flights by Destination State)
What I Did:

I created a bubble chart to show the number of flights per destination state across different months.
How I Did It:

I grouped the data by month and destination state.
The number of flights was visualized as bubbles whose size represented the count of flights for each destination state by month.
Findings:

The airline WN had the highest number of flights, with approximately 86 flights.
The chart revealed the seasonal fluctuation of flights to various destinations.
Key Insight:

WN dominated the market for this dataset in terms of flight frequency, and the number of flights varied seasonally, indicating peak travel times.
6. Pie Chart (Proportion of Distance Groups by Month)
What I Did:

I analyzed the proportion of flights in each distance group and how they varied by month.
How I Did It:

Data was classified into distance groups, and the proportions were calculated for each month.
A pie chart was created to visualize the proportion of each distance group in the dataset.
Findings:

Distance group 2 (representing medium-range flights) had the highest proportion of flights, with 27.2% of total flights.
Key Insight:

Medium-range flights were the most frequent in this dataset, possibly reflecting a balance between short and long-haul travel.
7. Sunburst Chart (Month and Destination State)
What I Did:

A sunburst chart was used to visualize the distribution of flights by month and destination state.
How I Did It:

The data was organized hierarchically, with the month at the center, and destination states as branches.
The sunburst chart visually displayed the number of flights for each month and its associated destination states.
Findings:

The chart clearly depicted how flights were distributed across different months, showing the monthly trends and their respective destination states.
Key Insight:

The sunburst chart was helpful in visualizing seasonal trends and the distribution of flights across different destinations over time.
## Conclusion
The analysis of the Reporting Carrier On-Time Performance Dataset provided significant insights into various aspects of air travel, such as:

The relationship between flight distance and departure time.
Monthly variations in flight delays and the impact of peak seasons.
The distribution of flights to various destination states and airlines.
The proportion of medium-distance flights relative to short and long-distance flights.
A detailed view of flight trends over months using the sunburst chart.
This analysis highlights the complexity of air travel and offers valuable insights into flight operations, delays, and patterns, which could be further applied to predictive models for on-time performance and operational improvements in the airline industry.

Author(s)
Saishruthi Swaminathan

Lakshmi Holla
Other Contributor(s)
Lavanya T S
Completed by:
Qazi Fabia Hoq (as part of the Data Science Professional Certification by IBM)

## Acknowledgments
Special thanks to IBM for providing the resources and framework to complete this analysis as part of the Data Science Professional Certification. Their educational materials were essential in helping develop the skills and knowledge to successfully undertake this project.







