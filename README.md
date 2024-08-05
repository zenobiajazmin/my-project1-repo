# my-project1-repo
Project 1



### Working on manipulating data to change dates to seasons 
- struggling with a good proper way to sort data in a relevant way for the project
- Only dates available in the csv for airbnb are 'last reviewed' which only gives us a date of usage for that bnb for that given review not a large amount of stays across the span of a year

### Project Proposal Summary

**Project Title**: Analyzing Seasonal Trends and Their Impact on Airbnb Prices

**Team Members**: Bryan, Nebiat, Jazmin

**Project Description/Outline**:
This project aims to analyze how seasonal trends affect various metrics of Airbnb listings, such as price, number of reviews, reviews per month, and availability. By leveraging the date, we can find insights into seasonal variations and their correlation with Airbnb pricing. The project will focus on identifying patterns and trends that can inform hosts and potential guests about the best times to rent or stay at accommodations property.

**Research Questions to Answer**:
1. How do average nightly rental prices for Airbnb properties vary by season?
2. How do the number of reviews, reviews per month, and availability change with the seasons?
3. What is the correlation between average nightly rental prices and other metrics (number of reviews, reviews per month, availability) across different seasons?

**Datasets to Be Used**:
- **Airbnb Listings Data**: The dataset includes information about Airbnb listings in the USA, focusing on metrics such as price, number of reviews, reviews per month, and availability.
- **Seasonal Information**: Derived from the date in the Airbnb dataset.

**Rough Breakdown of Tasks**:
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

**Support and Resources**:
- **APIs**: For potential future extensions, consider using APIs for additional data (e.g., weather data, event data).
- **Instructional Team**: Utilize office hours and support sessions for guidance and feedback.
- **GitHub**: Use GitHub for version control and collaboration.

**Deliverables**:
- **Completed Analysis**: Uploaded to GitHub with a complete README file.
- **Visualizations**: At least 6-8 visualizations, with clear labels with explanations.
- **Analysis and Conclusion**: A write-up summarizing major findings and implications, supported by statistical analysis and visualizations.
- **Group Presentation**: A 10-minute presentation covering all aspects of the project.

### Summary of Analysis vs. Hypotheses

#### Hypotheses
- **H1**: There are significant seasonal variations in Airbnb metrics (price, number of reviews, reviews per month, availability).
- **H0**: There are no significant seasonal variations in Airbnb metrics.

### Key ANOVA Test Results
- **Price**: P-value = 1.29e-11
- **Number of Reviews**: P-value = 1.00e-133
- **Reviews per Month**: P-value = 0.00e+00
- **Availability**: P-value = 1.17e-136

### Conclusion
All p-values are significantly below 0.05, leading us to reject the null hypothesis (H0) for each metric. This confirms that there are significant seasonal variations in Airbnb metrics.

### Implications
- **Price**: Hosts can adjust prices seasonally to maximize revenue.
- **Number of Reviews**: Seasonal trends affect guest review activity.
- **Reviews per Month**: Guest feedback frequency varies by season.
- **Availability**: Booking availability changes significantly throughout the year.
