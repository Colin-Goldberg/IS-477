Title: Impact of Region and Hub Size on Flight Delays 

Contributors:
Shreya Anand (sanand11@illinois.edu)
Colin Goldberg (colinmg3@illinois.edu)

Summary: This project looks to identify patterns of flight delays across the United States airports hoping to understand how geographic location or size may affect delays. In order to accomplish this, two data sets were used. One that contains detailed information about flight delays and another that contains airport passenger traffic data. The first step in the project was for us to clean the data, which ended up being very essential to the process. Both datasets had issues such as missing values, inconsistent formatting, and extreme outliers. We were able to handle missing values by removing rows that had incomplete data allowing for the data to stay consistent. A lot of the numeric values, specifically in the enplanement dataset, were stored as strings with commas or percentage signs, resulting in us converting those values into the proper formats. Additionally, we also noticed some really large delay values which caught our eye. We flagged those and thought about how they might affect the analysis. Overall, cleaning the data made it much easier to work with and helped avoid problems later on.Upon cleaning the dataset, we then merged the datasets. This allowed us to connect delay information with airport characteristics like passenger volume and whether an airport was considered a hub or not. This step was necessary as it made it possible to analyze all the data at once in an organized manner and learn where different correlations existed.After creating out new dataset where all the information was combined and cleaned, we were able to move onto the exploratory data analysis(EDA) portion. In this process, we created several visualizations to understand what the data looked like and what columns connected. These included average delays by region, different types of delays across regions, comparisons between hub and non-hub airports, and delay trends based on airport size. From these graphs, we could already see that there were differences in delays across regions and that larger airports seemed to have higher delays. This gave us a good starting point before running any models overall allowing us to have a better understanding of the data we were working with. Next we moved onto creating two regression models to help answer our two main research questions. The first model looked at how regions affect delays. The coefficients showed that some regions had higher delays than others, but the R² value was extremely low (around 0.004). This told us that the region does not explain much when looking at the reason for the variation in delays. So even though there are slight differences, it is not a strong reliable predictor that can give us information. The second model looked at was based on airport size using passenger volume. This model had a much higher success rate with an R² around 0.81, showing that these factors explain more of the variation in delays. The results suggest that larger airports tend to have higher delays, which correlates since  more traffic results in more complexities when it comes to managing. Overall, the main takeaway from this project is that while delays do vary by region, airport size is a much stronger factor. Bigger airports are generally more prone to delays, likely because of congestion and how busy they are. This gives a better understanding of what actually drives delays and can be useful for both travelers and airports.

Data profile: 

Data quality:

Data cleaning: 

Findings:

Future work:

Challenges:

Reproducing:

References:
