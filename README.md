# my-project1-repo
Project 1
# Analyzing Seasonal Trends and Their Impact on Airbnb Prices

### Team Members
Bryan, Nebiat, Jazmin

### Project Description/Outline
This project aims to analyze how seasonal trends affect various metrics of Airbnb listings, such as price, number of reviews, reviews per month, and availability. By leveraging the date, we can find insights into seasonal variations and their correlation with Airbnb pricing. The project focuses on identifying patterns and trends that can inform hosts and potential guests about the best times to rent or stay at accommodations property.

### Research Questions to Answer
1. How do average nightly rental prices for Airbnb properties vary by season?
2. How do the number of reviews, reviews per month, and availability change with the seasons?
3. What is the correlation between average nightly rental prices and other metrics (number of reviews, reviews per month, availability) across different seasons?

### Datasets to Be Used
- **Airbnb Listings Data**: Information about Airbnb listings in the USA, focusing on metrics such as price, number of reviews, reviews per month, and availability.
- **Seasonal Information**: Derived from the date in the Airbnb dataset.

### Rough Breakdown of Tasks
1. **Data Loading and Cleaning**:
   - Load the Airbnb dataset.
   - Filter and clean the dataset as needed.

2. **Seasonal Analysis**:
   - Define a function to determine the season for each listing based on the `last_review` date.
   - Add a `season` column to the dataset using the defined function.

3. **Data Aggregation**:
   - Group the data by season.
   - Calculate average metrics (price, number of reviews, reviews per month, availability) for each season.

4. **Visualization**:
   - Create bar plots to visualize average metrics by season.
   - Use combined plots with twin axes to compare average prices with other metrics across seasons.

5. **Analysis and Interpretation**:
   - Analyze the visualizations to identify trends and correlations.
   - Summarize key findings and insights.

6. **Presentation**:
   - Prepare a formal presentation covering the research questions, data exploration, analysis process, visualizations, and conclusions.
   - Ensure the presentation is clear, engaging, and professionally formatted.

### Summary of Analysis vs. Hypotheses

**Hypotheses:**
- **H1**: There are significant seasonal variations in Airbnb metrics (price, number of reviews, reviews per month, availability).
- **H0**: There are no significant seasonal variations in Airbnb metrics.

**ANOVA Test Results:**
- **Price**: F-value = 42.14, P-value = 5.22e-59. This is statistically significant for price.
- **Number of Reviews**: F-value = 22.15, P-value = 5.99e-30. This is statistically significant for number of reviews.
- **Reviews per Month**: F-value = 78.04, P-value = 7.71e-111. This is statistically significant for reviews per month.
- **Availability**: F-value = 24.05, P-value = 1.07e-32. This is statistically significant for availability.

**Conclusion:**
All p-values are significantly below 0.05, confirming significant seasonal variations in Airbnb metrics.

### Findings/Analysis
**Average Availability and Price by Detailed Season:**
![Average Availability and Price by Detailed Season](Images/Average%20Availability%20and%20Price%20by%20Detailed%20Season.png)
- **Analysis**: Availability peaks in Early Summer, indicating high demand. Prices are highest in Late Summer, reflecting peak season pricing.
- **Implications**: Hosts can optimize revenue by adjusting prices during peak seasons and ensuring availability during high-demand periods.

**Average Number of Reviews and Price by Detailed Season:**
![Average Number of Reviews and Price by Detailed Season](Images/Average%20Number%20of%20Reviews%20&%20Price%20by%20Detailed%20Season.png)
- **Analysis**: Number of reviews peaks in Late Summer, indicating higher guest activity during this period. Prices also peak in Late Summer.
- **Implications**: Encouraging reviews during peak seasons can help improve property visibility and attract more guests.

**Average Price by Detailed Season:**
![Average Price by Detailed Season](Images/Average%20Price%20by%20Detailed%20Season.png)
- **Analysis**: Prices peak in Late Summer, with lower prices in Late Winter.
- **Implications**: Guests can find better deals in off-peak seasons, while hosts can maximize revenue during peak seasons.

**Average Reviews per Month and Price by Detailed Season:**
![Average Reviews per Month and Price by Detailed Season](Images/Average%20Reviews%20per%20Month%20&%20Price%20by%20Detailed%20Season.png)
- **Analysis**: Reviews per month peak in Early Fall, with prices peaking in Late Summer.
- **Implications**: Higher guest feedback during Early Fall can help hosts improve their services and attract more guests in subsequent seasons.

**Box and Whiskers Plot of Average Prices by Season:**
![Box and Whiskers Plot of Average Prices by Season](Images/box%20plot%20of%20average%20prices%20by%20season.png)
- **Analysis**:
  - **Summer**: Highest median prices and greatest variability, indicating peak demand.
  - **Spring and Fall**: Moderate median prices, with slight increases during Late Spring and Early Fall.
  - **Winter**: Lowest and most consistent prices, reflecting reduced demand.
  - **Outliers**: Likely represent luxury and premium listings.
- **Implications**:
  - **Hosts**: Understanding factors leading to outliers can help optimize pricing strategies.
  - **Guests**: Be aware of outliers representing higher-than-average prices and consider alternative dates/locations for better rates.
  - **Investors**: Identify high-revenue opportunities by analyzing outliers and understanding underlying causes of price surges.

### Recommendations
- **For Hosts**: Adjust prices and manage availability seasonally, encourage reviews year-round.
- **For Guests**: Book during off-peak seasons for better deals and availability, leave reviews to provide feedback.

### Filtering Out Data
There were significant outliers outside of the standard deviation, so we limited the data set to prices of $350 and below per night to focus on affordable properties/listings.

### Working on Manipulating Data to Change Dates to Seasons
- Struggled to sort data in a relevant way for the project.
- Only dates available in the CSV for Airbnb are 'last reviewed,' which only gives us a date of usage for that BNB for that given review, not a large amount of stays across the span of a year.

### Support and Resources
- **APIs**: For potential future extensions, consider using APIs for additional data (e.g., weather data, event data).
- **Team Members**: Support and teamwork to ensure each element of the project was complete
- **GitHub**: Use GitHub for version control and collaboration.


