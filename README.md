# Analysis of Airline On-Time Performance Dataset

## Project Description

This project analyzes the Reporting Carrier On-Time Performance Dataset from the United States Bureau of Transportation Statistics, containing about 200 million domestic US flights. The main goal is to explore flight patterns and delay behaviors to better understand factors influencing flight delays and timings. This analysis aims to identify actionable insights that could improve airline operations and customer experience by highlighting patterns in delays and flight schedules.

## Who Will Benefit and Why

* **Airlines and Flight Operators**: To optimize scheduling and reduce delays by understanding delay patterns and peak travel times.
* **Airport Authorities**: To improve ground operations and resource allocation based on flight frequency and delay trends.
* **Travelers and Customers**: To gain realistic expectations of flight punctuality and choose flights with lower delay risks.
* **Data Scientists and Analysts**: To build predictive models and operational tools using detailed flight performance data.

## Dataset Description

The dataset covers domestic US flights and includes key columns such as flight date, scheduled departure time, departure and arrival airports, carrier, flight number, arrival and departure delays, and delay reasons. The dataset is publicly available at:
[https://dax-cdn.cdn.appdomain.cloud/dax-airline/1.0.1/data-preview/index.html](https://dax-cdn.cdn.appdomain.cloud/dax-airline/1.0.1/data-preview/index.html)

## Methodology and Approach

* Grouped and summarized flight data by variables such as distance, departure time, month, airline, and destination state.
* Used multiple visualization techniques (scatter plots, line plots, bar charts, histograms, bubble charts, pie charts, sunburst charts) created mainly with Plotly for interactive analysis.
* Examined relationships between flight distance and departure timing, seasonal delay trends, airline flight volumes by state, delay distributions, and monthly destination patterns.
* Handled missing values and outliers to ensure accurate representation of delay distributions.

## Key Findings

**1. How does flight distance relate to departure times?**
Shorter flights depart more evenly throughout the day, while longer flights are scheduled at specific times, reflecting operational constraints.

**2. Which months have the highest and lowest average flight delays?**
June shows the highest average arrival delay (\~17.31 minutes), likely due to peak travel or weather, while November has the lowest average delay, with many flights arriving early.

**3. Which states receive the most and fewest flights?**
California has the highest number of flights (68), being a major travel hub. Vermont has the fewest flights (1), reflecting lower demand.

**4. What is the distribution of arrival delays?**
Most delays cluster between 20-25 minutes (about 17 flights), with very few experiencing long delays over 50 minutes (5 flights).

**5. Which airline operates the most flights?**
Airline WN leads with approximately 86 flights, showing dominance in the dataset’s market share.

**6. What types of flights are most frequent by distance?**
Medium-range flights make up the largest share at 27.2%, indicating a balance between short-haul and long-haul travel.

**7. How do flights distribute across months and destinations?**
Flights show clear seasonal patterns, with variations in destination frequencies across months, well visualized by the sunburst chart.

## Conclusion

The analysis reveals clear patterns in flight scheduling, delays, and airline operations. Seasonal variations significantly impact delay times, and major hubs like California receive far more flights than smaller states. Medium-range flights dominate the flight profile. These insights can help stakeholders optimize scheduling, predict delays, and improve passenger satisfaction. Understanding such patterns is crucial for operational improvements and enhancing the efficiency of air travel.

## Recommendations

Focus on optimizing flight schedules for longer routes to reduce operational constraints. Airlines could also pay attention to peak delay months like June to better manage resources. Further predictive modeling using this dataset could enable more accurate on-time arrival forecasts and help in proactive delay management.

## Credits and Acknowledgments

**Author(s):**
Saishruthi Swaminathan
Lakshmi Holla

**Other Contributors:**
Lavanya T S

**Completed by:**
Qazi Fabia Hoq (as part of the Data Science Professional Certification by IBM)

Special thanks to IBM for providing educational resources that supported the completion of this project.
