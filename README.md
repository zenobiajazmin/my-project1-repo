# my-project1-repo
Project 1


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

This proposal outlines a structured approach to analyzing seasonal trends and their impact on Airbnb pricing, aiming to provide valuable insights for both hosts and guests.
