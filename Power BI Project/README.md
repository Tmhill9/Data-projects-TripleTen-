# README: Power BI Project – Shopify App Analysis

This document outlines the steps, methodologies, and results of the Shopify App Analysis conducted in Power BI. Screenshots of each visualization and result are included in the attached folder for reference.

---

## Dataset Overview

The dataset (`shopify.xlsx`) contains information scraped from the Shopify App Store. The data includes:

1. **Apps**: Details about Shopify apps.
2. **Apps Categories**: Mapping apps to their respective categories.
3. **Categories**: Information about app categories.
4. **Reviews**: User reviews for apps, including ratings, comments, and developer responses.

---

## Analysis Process

### **Part 1: App Landscape**

#### Objective:
Understand the distribution and statistics of Shopify apps.

1. **KPI Card: Unique Number of Apps**  
   - A KPI card was created to display the total unique number of apps in the dataset.  
   - **Result:** A count of **7,341 unique apps** was determined.  
   - **Screenshot:** Refer to `Screenshot 1-KPI CARD.png` in the folder.

2. **Line Chart: Review Count Over Time**  
   - The sum of `reviews_count` was plotted over the `lastmod` date.  
   - **Result:** The chart shows fluctuating review activity over time, indicating key trends in app usage or activity.  
   - **Screenshot:** Refer to `Screenshot 2-Line Chart_Review Count Over Time.png` in the folder.

3. **Scatterplot: Reviews Count vs. Average Rating**  
   - A scatterplot visualizing `reviews_count` against `average_rating` was created.  
   - **Insights:** Apps with more reviews tend to have slightly lower ratings, suggesting a broader spectrum of opinions from users.  
   - **Screenshot:** Refer to `Screenshot 3-Scatterplot_Reviews Count vs. Average Rating.png` in the folder.

---

### **Part 2: Reviews**

#### Objective:
Analyze reviews and evaluate factors like helpfulness and developer responses.

1. **Helpful Reviews Calculation**  
   - A calculated column, `helpful_reviews`, was added using the formula: `rating * (1 + helpful_count)`.  
   - **Result:** The average of `helpful_reviews` is **5.48**.  
   - **Screenshot:** Refer to `Screenshot 4-Helpful Reviews.png` in the folder.

2. **Developer Answered Column**  
   - A column named `developer_answered` was added to indicate whether developers replied to reviews.  
   - **Scatterplot Insight:** Apps with developer responses tend to have slightly higher ratings on average.  
   - **Screenshot:** Refer to `Screenshot 5-Developer Answered.png` in the folder.

---

### **Part 3: App Reviews**

#### Objective:
Evaluate app developers' performance and responsiveness using combined app and review data.

1. **Relationship Between Tables**  
   - A many-to-one relationship was established between the `reviews` table and the `apps` table using `app_id` and `id`.  
   - **Screenshot:** Refer to `Screenshot 6-Relationship Between Tables.png` in the folder.

2. **Bar Chart: Developer vs. Sum of Rating**  
   - A bar chart was created to show the sum of ratings per developer.  
   - **Result:** Developers with more apps tend to have higher cumulative ratings.  
   - **Screenshot:** Refer to `Screenshot 7-Developer vs. Sum of Rating.png` in the folder.

3. **Bar Chart: Developer vs. Average Helpful Reviews**  
   - A bar chart showing developers against the average `helpful_reviews`.  
   - **Insight:** Developers with higher engagement produce more helpful reviews.  
   - **Screenshot:** Refer to `Screenshot 8-Developer vs. Average Helpful Reviews.png` in the folder.

4. **Bar Chart: Developer Responsiveness**  
   - A bar chart was created to display `developer_answered` values filtered by apps with more than 500 reviews.  
   - **Result:** The most responsive developers engage more with reviews, likely leading to better user satisfaction.  
   - **Screenshot:** Refer to `Screenshot 9-Developer Responsiveness.png` in the folder.

---

## Submission Details

### Screenshots
All required screenshots are attached in the folder with the following names:
1. `Screenshot 1-KPI CARD.png`
2. `Screenshot 2-Line Chart_Review Count Over Time.png`
3. `Screenshot 3-Scatterplot_Reviews Count vs. Average Rating.png`
4. `Screenshot 4-Helpful Reviews.png`
5. `Screenshot 5-Developer Answered.png`
6. `Screenshot 6-Relationship Between Tables.png`
7. `Screenshot 7-Developer vs. Sum of Rating.png`
8. `Screenshot 8-Developer vs. Average Helpful Reviews.png`
9. `Screenshot 9-Developer Responsiveness.png`

### Organization
The Power BI report contains individual pages for each analysis section:
- **App Landscape**
- **Reviews**
- **App Reviews**

---

## Conclusion

This Power BI project provides a comprehensive analysis of Shopify apps, their reviews, and developer interactions. Insights gained from the visualizations can be utilized to identify factors contributing to app success and improve user engagement strategies.
