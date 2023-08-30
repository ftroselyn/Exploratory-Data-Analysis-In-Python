# Exploratory-Data-Analysis-In-Python
----
# Exploratory Data Analysis of Roller Coaster Attributes
----
# Description
This exploratory data analysis (EDA) aims to uncover insights into the relationships between various attributes of roller coasters using a correlation matrix. The attributes under consideration include the year of introduction, speed in miles per hour, height in feet, number of inversions, and G-force experienced.

# Processes

# Data Loading
  The data containing roller coaster attributes is loaded into a DataFrame for analysis.

# Data Cleaning
  The dataset is cleaned to ensure consistency, accuracy, and uniformity in attribute names.
  
# Correlation Matrix
    A correlation matrix is computed to quantify the relationships between pairs of attributes. 
  Correlation values range from -1 to 1, where positive values indicate a positive correlation and negative values indicate a negative 
  correlation.
  
# Visualization
   The correlation matrix is visualized using Seaborn's heatmap to provide an overview of attribute correlations.

# Interpretation

  The correlation values are interpreted to understand the strength and direction of relationships between attributes. Based on the correlation matrix, we can observe the following correlations between the variables:
  
•	Year_intro vs. Speed_mph: There is a positive correlation of approximately 0.172 between the year of introduction and the speed in miles per hour. This suggests that, on average, newer roller coasters tend to have slightly higher speeds.

•	Year_intro vs. Height_ft: There is a positive correlation of approximately 0.135 between the year of introduction and the height of the roller coaster in feet. This implies that newer roller coasters tend to be slightly taller on average.

•	Speed_mph vs. Height_ft: There is a strong positive correlation of about 0.734 between the speed of the roller coaster and its height. This suggests that roller coasters with higher speeds tend to also have greater heights.

•	Year_intro vs. Inversions: There is a negative correlation of around -0.210 between the year of introduction and the number of inversions. This could indicate that older roller coasters were more likely to have inversions, but this correlation is not very strong.

•	Speed_mph vs. Inversions: There is a weak negative correlation of approximately -0.029 between the speed of the roller coaster and the number of inversions. This suggests that there isn't a strong relationship between speed and the presence of inversions.

•	Height_ft vs. Inversions: There is a weak negative correlation of around -0.080 between the height of the roller coaster and the number of inversions. Again, this correlation isn't strong, indicating that there isn't a significant relationship between height and the presence of inversions.

•	Year_intro vs. Gforce: There is a positive correlation of about 0.160 between the year of introduction and the G-force experienced on the roller coaster. This suggests that newer roller coasters might tend to have slightly higher G-force values.

•	Speed_mph vs. Gforce: There is a strong positive correlation of around 0.607 between the speed of the roller coaster and the G-force experienced. This indicates that roller coasters with higher speeds also tend to subject riders to greater G-forces.

•	Height_ft vs. Gforce: There is a moderate positive correlation of approximately 0.466 between the height of the roller coaster and the G-force experienced. This implies that taller roller coasters often subject riders to higher G-forces.

# Conclusion and Recommendations
    Insights from the correlation analysis are summarized to draw conclusions and make recommendations.
    
•	Roller coaster speed and height appear to be strongly correlated, suggesting that taller roller coasters tend to have higher speeds.

•	The year of introduction seems to have a modest correlation with certain attributes, indicating that newer roller coasters might have higher speeds, greater heights, and potentially higher G-forces.

•	The number of inversions doesn't show strong correlations with other attributes.


