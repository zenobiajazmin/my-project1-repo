
# Analyzing Seasonal Trends and Their Impact on Airbnb Prices

### Team Members
Bryan, Nebiat, Jazmin

### Project Description/Outline
This project aims to analyze how seasonal trends affect various metrics of Airbnb listings, such as price, number of reviews, reviews per month, and availability. By leveraging the data, we can find insights into seasonal variations and their correlation with Airbnb pricing. The project focuses on identifying patterns and trends that can inform hosts and potential guests about the best times to rent or stay at an accommodation property.

### Research Questions to Answer
1. How do average nightly rental prices for Airbnb properties vary by season?
2. How do the number of reviews, reviews per month, and availability change with the seasons?
3. What is the correlation between average nightly rental prices and other metrics (number of reviews, reviews per month, availability) across different seasons?

### Analysis and Conclusion

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

**Summary of Major Findings and Implications:**
- **Availability** peaks in Early Summer, indicating high demand. Prices are highest in Late Summer, reflecting peak season pricing. 
  - **Implications for Hosts**: Adjust prices during peak seasons and ensure availability during high-demand periods.
  - **Implications for Guests**: Book during off-peak seasons for better deals and availability.

- **Number of Reviews** peaks in Late Summer, indicating higher guest activity during this period. Prices also peak in Late Summer.
  - **Implications for Hosts**: Encourage reviews during peak seasons to improve property visibility and attract more guests.

- **Prices** peak in Late Summer, with lower prices in Late Winter.
  - **Implications for Guests**: Find better deals in off-peak seasons, while hosts can maximize revenue during peak seasons.

- **Reviews per Month** peak in Early Fall, with prices peaking in Late Summer.
  - **Implications for Hosts**: Higher guest feedback during Early Fall can help improve services and attract more guests in subsequent seasons.

**Findings Supported with Visualizations:**

**Average Availability and Price by Detailed Season:**
![Average Availability and Price by Detailed Season](Images/Average%20Availability%20and%20Price%20by%20Detailed%20Season.png)

**Average Number of Reviews and Price by Detailed Season:**
![Average Number of Reviews and Price by Detailed Season](Images/Average%20Number%20of%20Reviews%20&%20Price%20by%20Detailed%20Season.png)

**Average Price by Detailed Season:**
![Average Price by Detailed Season](Images/Average%20Price%20by%20Detailed%20Season.png)

**Average Reviews per Month and Price by Detailed Season:**
![Average Reviews per Month and Price by Detailed Season](Images/Average%20Reviews%20per%20Month%20&%20Price%20by%20Detailed%20Season.png)

**Box and Whiskers Plot of Average Prices by Season:**

![Box and Whiskers Plot of Average Prices by Season](Images/box%20plot%20of%20average%20prices%20by%20season.png)

**Histogram of Average Prices:**
![Histogram of Average Prices](Images/Histogram%20of%20Average%20Prices.png)

**Scatter Plot of Price vs. Number of Reviews by Season:**
![Scatter Plot of Price vs. Number of Reviews by Season](Images/Scatterplot%20Price%20vs%20number%20of%20reviews.png)

The scatter plot illustrates the relationship between price and the number of reviews across different seasons. Key observations include:
- **Price Range:** Most listings are priced between $50 and $200 per night.
- **Review Counts:** Higher review counts are seen in Late Summer and Early Fall, indicating increased guest activity.
- **Winter Seasons:** Lower review counts in Early and Late Winter suggest lower demand.
- **No Correlation:** There is no clear correlation between the number of reviews and the price.

### Recommendations
- **For Hosts**: Adjust prices and manage availability seasonally, encourage reviews year-round.
- **For Guests**: Book during off-peak seasons for better deals and availability, leave reviews to provide feedback.

### Filtering Out Data
There were significant outliers outside of the standard deviation, so we limited the data set to prices of $350 and below per night to focus on affordable properties/listings.

### Limitations with Data Manipulation
- Only dates available in the CSV for Airbnb are 'last reviewed,' which only gives us a date of usage for that BNB for that given review, not a large amount of stays across the span of a year.
- Massive amount of price outliers for each listing. Ranging from $20 to $12,000 - Limiting price to $350 a night and below was important for data relevance.
