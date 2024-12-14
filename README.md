# Upliance.AI---Assignment
Repository Contents

The repository contains the following files:
      
**Excel Workbook**:
Includes cleaned and merged datasets.
Contains pivot tables and visualizations for analysis.

**Report Document**:
Summarizes the analysis, key findings, and actionable recommendations.

**Steps Performed**
1. Data Cleaning and Preparation: 
Removed duplicates and handled missing values (e.g., missing ratings for canceled orders).
Ensured proper formatting of data types (e.g., dates, numeric fields).
Verified consistency of Session ID and User ID across datasets.
2. Data Merging:
Merged OrderDetails with CookingSessions using Session ID to include session-related data (e.g., session ratings).
Incorporated user demographics (e.g., age, location) from UserDetails using User ID.
3. Data Analysis:

      a. Relationship Between Cooking Sessions and Orders
      Calculated the correlation coefficient between session ratings and order ratings using the CORREL function.

      Result: A moderate positive correlation (0.63), indicating that higher session satisfaction moderately influences order satisfaction.
      Visualized the relationship using a scatter plot with a trendline.

      b. Popular Dishes: 
      Identified the most frequently ordered dishes using pivot tables.
      Analyzed dish preferences by age group and location.

      c. Demographic Analysis
      Explored ordering patterns by age group and location using pivot tables.
      Found that certain dishes and meal types were more popular in specific regions.
      Key Insights


**Cooking Sessions and Orders**:
A moderate positive correlation suggests that improving cooking session quality can enhance order satisfaction.


**Location-Based Trends**:
Certain locations show higher order volumes and preferences for specific dishes.


**Menu Offerings**:
Popular dishes drive higher engagement and satisfaction.

**Recommendations** : 

**Enhance Cooking Sessions**:
    Improve session quality with interactive features and personalized content to boost user satisfaction.

**Targeted Marketing by Location**:
    Develop location-specific promotions to cater to regional preferences.

**Optimize Menu Offerings**:
    Highlight popular dishes and introduce new items tailored to user preferences.
