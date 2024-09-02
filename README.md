# Aerofit Treadmill Product Analysis Case Study

## Project Overview

This project focuses on analyzing the characteristics of the target audience for different treadmill models offered by Aerofit. The analysis aims to provide insights that will guide product recommendations, marketing strategies, and potential areas for product development.

## Business Problem

The market research team at Aerofit wants to identify the characteristics of the target audience for each type of treadmill to better recommend products to new customers. The study explores whether there are differences in customer characteristics across different treadmill products.

## Tools

- **Jupyter Notebook**
- **Python Libraries**: pandas, matplotlib, seaborn, numpy

## Steps Involved

### 1. Data Collection
- **Dataset**: The dataset includes customer demographics, product usage, fitness levels, and other relevant attributes.

### 2. Data Preprocessing
- **Handling Missing Values**: Verified that the dataset contains no missing values, ensuring unbiased analysis.
- **Detection of Outliers**: Identified and addressed outliers in the dataset using techniques like clipping to reduce bias.

### 3. Exploratory Data Analysis (EDA)
- **Data Summary**: Summarized key statistics of numerical columns such as `Age`, `Usage`, `Fitness`, `Income`, and `Miles`.
- **Visual Analysis**: Used box plots and histograms to visualize data distribution and detect trends or anomalies.

### 4. Data Transformation
- **Age Grouping**: Categorized customers into age groups—Youngsters (18-25), Active Achievers (26-35), and Middles (36-45)—for more targeted analysis.
- **Income Grouping**: Segmented customers into income groups—Low-Medium, Medium-High, and High Income—based on their earnings.
- **Mileage Grouping**: Classified customers based on the distance covered—Short Range, Medium Range, and Long Range.

### 5. Visualization
- **Pie Charts**: Visualized the distribution of customers by product, gender, education level, marital status, usage frequency, and fitness level.
- **Bar Charts**: Displayed the distribution of age, education, and usage levels across different products.
- **Correlation Heatmaps**: Generated heatmaps to identify correlations between variables like `Age`, `Income`, `Usage`, `Fitness`, and `Miles`.
- **Box Plots**: Compared distributions of age, income, and miles covered across different products.

### 6. Business Insights
- **Product Preferences**: KP281 is the most popular treadmill model, especially among younger customers and those with medium-high income levels.
- **Usage Patterns**: Most customers use treadmills 3 to 4 times per week, with KP281 and KP481 being the most frequently used.
- **Income and Education**: Higher income and education levels are positively correlated with treadmill purchases, particularly for KP781.
- **Fitness Levels**: KP781 is favored by customers with higher self-rated fitness levels, while KP281 and KP481 are popular across all fitness levels.

### 7. Recommendations
- **Targeted Marketing**: Develop marketing campaigns targeting females, single individuals, and low-medium income groups to increase sales in these demographics.
- **Product Development**: Consider introducing new features or pricing strategies to appeal to older customers and those covering longer distances.
- **Content Customization**: Tailor marketing content to highlight specific product benefits based on customer segments, such as fitness goals or income levels.

## Conclusion

This analysis provides Aerofit with valuable insights into customer preferences and behavior, helping to optimize product offerings and marketing strategies. The recommendations aim to enhance customer engagement, increase sales, and drive overall business growth.
