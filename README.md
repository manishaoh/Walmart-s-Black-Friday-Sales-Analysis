# Walmart-s-Black-Friday-Sales-Analysis
Walmart's Black Friday Sales Analysis using Descriptive Statistics
1.Defining Problem Statement and Analysing basic metrics

1.1 Problem Statement

The management team at Walmart Inc. wants to analyze customer purchase behavior, particularly the purchase amount, against various factors including gender, age, marital status, etc., to make informed business decisions. Their aim is to understand if there are differences in spending habits among different demographics. Specifically, they want to understand if there are differences in spending habits between male and female customers, and how factors like age and marital status affect spending.


1.2 Analyzing basic metrics









Observations:

I.Shape of the data: The dataset contains 10 columns and 550068 rows.
II.Data types: Most columns are numeric (integer), while some are categorical (objects).
III.Conversion of categorical attributes: Categorical attributes like Gender, Age, Occupation, City_Category, Stay_In_Current_City_Years, Marital_Status, and Product_Category have been converted to 'category' type.
IV.Statistical summary: A statistical summary is provided, including count, mean, standard deviation, minimum, 25th percentile, median (50th percentile), 75th percentile, and maximum values for numeric attributes.
This analysis provides a basic understanding of the dataset structure and characteristics, which is essential for further exploration and analysis.


1.3 Non-Graphical Analysis: Value counts and unique attributes 





Observations:

I.Gender:
There are two genders: Male and Female.
The number of male customers (414259) is greater than the number of female customers (135809).

II.Age:
Age is categorized into bins.
The age bins range from 0-17 years to 51+ years.
There is a varied distribution of customers across different age groups.
The majority of individuals fall within the (26-35) and (36-45) age range, while the least number of individuals are in the (0-17) age range. 

III.Occupation:
Occupation is a categorical variable representing different occupations of customers.
The dataset includes various occupation categories ranging from 0-20
The most common Occupation category is 4, followed by 0 and 7.
The least common Occupation category is 8.

IV.City_Category:
City_Category represents the category of the city where the customer resides (A, B, or C).
The dataset includes customers from different city categories.
The majority of individuals fall within B category and least number of individuals are found in the A Category.

V.Stay_In_Current_City_Years:
Stay_In_Current_City_Years column represents the number of years the customer has stayed in the current city.
The dataset includes customers stay ranging from (0-4+) years.
The value counts indicate that most customers have stayed in the current city for 1 year, followed by 2 years and then 3 years.
The number of customers decreases as the duration of stay increases beyond 3 years.
The value counts indicate that least no. of customers have stayed in the current city for less than 1 year i.e. 0 years.

VI.Marital_Status:
Marital_Status is binary, representing whether the customer is married (1) or unmarried (0).
The dataset includes both married and unmarried customers.
The majority of individuals are unmarried (324731), while fewer individuals are married (225337).


VII.Product_Category:
Product_Category is a categorical variable representing different product categories.
The dataset includes transactions from various product categories ranging from (1-20).
The majority of individuals purchase products of category 5 (150933), followed by category 1 (140378) and category 8 (113925). 
The least number of individuals purchase products from Category  9 (410).


1.4Visual Analysis - Univariate & Bivariate

1.4.1For continuous variable(s): Distplot, countplot, histogram for univariate analysis








1.4.2For categorical variable(s): Countplot












1.4.3For categorical variable(s): Boxplot












1.4.4For correlation: Heatmaps, Pairplots





2.Missing Value & Outlier Detection










3.Business Insights based on Non- Graphical and Visual Analysis
3.1Comments on the range of attributes.

Range of Attributes


User_ID : 

These have the highest number of unique entries, indicating a large user base.
The most common User_ID is 1001680(1026), 1004277(979) and 1001941(898), and the least common User_ID is 1000708(6).

Product_ID: 

These have the highest number of unique entries, indicating a large variety of products.
The most common Product_ID is P00265242(1880), P00025442(1615) and P00110742(1612), and the least common Product_ID’s are P00314842, P00298842, P00231642, P00204442 and P00066342(1).


Gender:

There are two genders: Male and Female.
The number of male customers (414259) is greater than the number of female customers (135809).
This implies men make more purchases then women.

Age: 

Age is categorized into bins.
The age bins range from 0-17 years to 51+ years.
There is a varied distribution of customers across different age groups.
The majority of individuals fall within the (26-35) and (36-45) age range, while the least number of individuals are in the (0-17) age range. 

Occupation: 

There are 21 distinct occupations represented in the data.
Occupation is a categorical variable representing different occupations of customers.
The dataset includes various occupation categories ranging from 0-20
The most common Occupation category is 4 (indicating occupation 4 makes the most purchase), followed by 0 and 7.
The least common Occupation category is 8 (indicating occupation 8 makes the least purchase).

City Category: 

City_Category represents the category of the city where the customer resides (A, B, or C).
The dataset includes customers from different city categories.
The majority of individuals fall within B category (indicating individuals in B Category make the most purchase) and least number of individuals are found in the A Category (indicating individuals in A Category make the least purchase).

Stay in Current City Years: 

Stay_In_Current_City_Years column represents the number of years the customer has stayed in the current city.
The dataset includes customers stay ranging from (0-4+) years.
The value counts indicate that most customers have stayed in the current city for 1 year, followed by 2 years and then 3 years.
The number of customers decreases as the duration of stay increases beyond 3 years.
The value counts indicate that least no. of customers have stayed in the current city for less than 1 year i.e. 0 years.

Marital Status: 

Marital_Status is binary, representing whether the customer is married (1) or unmarried (0).
The dataset includes both married and unmarried customers.
The majority of individuals are unmarried (324731), while fewer individuals are married (225337).

Product Category: 

There are 20 product categories represented.
Product_Category is a categorical variable representing different product categories.
The dataset includes transactions from various product categories ranging from (1-20).
The majority of individuals purchase products of category 5 (150933), followed by category 1 (140378) and category 8 (113925). 
The least number of individuals purchase products from Category  9 (410).

Purchase:

Purchase column represents the total amount spent by a customer during one visit.
The most common purchase value is 7011(191), followed by 7193(188) and 6855(187).


3.2Comments on the distribution of the variables and the relationship between them.
Distribution of Variables:
Purchase: 
The distribution plots (distplot and histogram) likely show a right skew, indicating that most purchases fall within a lower range, with a few outliers on the higher end. This suggests a focus on strategies to encourage more frequent purchases from a larger portion of the customer base.
Age: 
The count plot reveals a higher concentration of customers in the 26-35 age group, aligning with the non-graphical analysis. This age group might be a prime target for marketing campaigns.
Gender:
The count plot confirms a significant imbalance towards male customers. Further analysis is needed to understand if product offerings or marketing strategies resonate more with one gender over the other.
Occupation:
The countplot implies most customers belong to occupation 4, 0 and 7, these occupations might be a prime target for marketing campaigns.
City Category:
The count plot reveals a higher concentration of customers in the B category. This City Category might be a prime target for marketing campaigns.
Stay in Current City Years:
The count plot indicates most customers stay in a city for atleast 1 year, and the least no. of customers stay in a city for less than an year.
Marital Status: 
The count plot implies  a higher concentration of customers are unmarried, indicating further analysis is needed to understand if product offerings or marketing strategies resonate more with unmarried customers over married ones.
Product Category: 
The count plot implies  a higher concentration of customers purchase Product Category 5, followed by 1 and 8 and These Product Categories might be a prime target for marketing campaigns.

Relationships between Variables and Purchase Amount :
User_ID:
There appears to be a weak positive correlation between User_ID and Purchase. The heatmap shows a light red square with a value of 0.0047.
Gender:
I.The distribution of purchase amount appears to be higher for males compared to females. The center line in the male boxplot is positioned higher than the center line in the female boxplot. This suggests that the median purchase amount may be higher for males.
II.The interquartile range (IQR) appears to be similar for both genders. The IQR is the spread of the middle half of the data. The fact that the boxes are roughly similar in height suggests that the distribution of purchase amounts within each gender grouping is similar.
III.There are outliers in both the male and female data sets. Outliers are data points that fall outside of 1.5 times the IQR above the upper quartile (Q3) or below the lower quartile (Q1).
Age:
I.There appears to be a possible trend of increasing purchase amount with increasing age. The medians (represented by the center lines in the boxes) tend to increase as we move across the age groups.
II.There appears to be a weak positive correlation between age and purchase amount. Younger ages tend to have lower purchase amounts, while there is a slight upward trend in purchase amount with increasing age.
III.There is a lot of variability in purchase amount within each age group. This is indicated by the interquartile range (IQR) which is the spread of the middle half of the data. The boxes in the plot tend to be wide, especially for the younger age groups.
IV.There are outliers in all of the age groups. Outliers are data points that fall outside of 1.5 times the IQR above the upper quartile (Q3) or below the lower quartile (Q1).
Occupation:
I.Increasing Median Purchase Amount: Look closely at the center lines in the boxes. If there's a trend, the medians should generally increase as the occupation code goes from 0 to 20. This might suggest higher-coded occupations (potentially representing higher incomes) have higher median purchase amounts.
II.Variability within Occupations: The width of the boxes indicates the spread (IQR) of purchase amounts within each occupation. The IQR is quite similar for Occupations column ranging from (0-20)
III.The interquartile range (IQR) appears to be similar for all occupations. The IQR is the spread of the middle half of the data. The fact that the boxes are roughly similar in height suggests that the distribution of purchase amounts within each occupation category is similar.
IV.There are outliers in most of the Occupation categories. Outliers are data points that fall outside of 1.5 times the IQR above the upper quartile (Q3) or below the lower quartile (Q1).
City_Category:
I.The distribution of purchase amount appears to be higher for city category B compared to city categories A and C. The center line in the boxplot for city category B is positioned higher than the center lines in the other two boxes. This suggests that the median purchase amount may be higher for city B.
II.The interquartile range (IQR) appears to be similar for all three city categories. The IQR is the spread of the middle half of the data. The fact that the boxes are roughly similar in height suggests that the distribution of purchase amounts within each city category is similar.
III.There are outliers in all of the city categories. Outliers are data points that fall outside of 1.5 times the IQR above the upper quartile (Q3) or below the lower quartile (Q1).
IV.The distribution of purchase amount appears to be higher for city category B compared to city categories A and C. The center line in the boxplot for city category B is positioned higher than the center lines in the other two boxes. This suggests that the median purchase amount may be higher for city category B.
V.The interquartile range (IQR) appears to be similar for all three city categories. The IQR is the spread of the middle half of the data. The fact that the boxes are roughly similar in height suggests that the distribution of purchase amounts within each city category grouping is similar.
VI.There are outliers in all of the city categories. Outliers are data points that fall outside of 1.5 times the IQR above the upper quartile (Q3) or below the lower quartile (Q1).

Stay_In_Current_City_Years:
I.There does not appear to be a clear trend between the two variables. The medians (center lines in the boxes) for purchase amount are fairly similar across the four categories (1, 2, 3, and 4+ years).
II.The spread of the data (IQR - interquartile range) appears to be similar across the four categories as well. This means that the variability in purchase amount is similar regardless of how long someone has lived in their current city.
Marital_Status:
I.The distribution of purchase amount appears to be similar for married as well as unmarried individuals. The median purchase amount is quite similar for both the marital statuses.
II.The interquartile range (IQR) appears to be similar for all marital statuses. The IQR is the spread of the middle half of the data. The fact that the boxes are roughly similar in height suggests that the distribution of purchase amounts within each marital status grouping is similar.
III.There are outliers in all of the marital status categories. Outliers are data points that fall outside of 1.5 times the IQR above the upper quartile (Q3) or below the lower quartile (Q1).
Product_Category:
I.There is no clear linear relationship between product category and purchase amount. This means that the median purchase amount does not necessarily increase or decrease as the product category goes from 1 to 20.
II.There is a significant spread in purchase amount across all product categories. There are outliers  for most product categories. 


3.3Comments for each univariate and bivariate plot

Univariate Analysis:

Age:
The age distribution is fairly even, with a concentration of customers in the 26-35 age range.
The majority of customers fall between 18 to 45 years old, with smaller proportions in younger and older age groups.
There are no missing values in the age attribute.

Occupation:
Certain occupations are more common among Walmart customers, with occupation 4 and occupation 0 being the most prevalent.
There is a wide range of occupations represented among customers, indicating a diverse customer base.
There are no missing values in the occupation attribute.

Gender:
The gender distribution is approximately equal, with a similar number of male and female customers.
There are no missing values in the gender attribute.

Marital Status:
The majority of customers are married, with a smaller proportion of unmarried customers.
There are no missing values in the marital status attribute.

Purchase Amount:
The purchase amount distribution is positively skewed, with most transactions involving lower purchase amounts and some outliers with very high purchase amounts.
The mean purchase amount is $9,321.36, with a standard deviation of $5,186.60.
There are no missing values in the purchase amount attribute.

Bivariate Analysis:

Age vs. Purchase Amount:
There is a weak positive correlation between age and purchase amount.
Older customers tend to spend slightly more than younger customers.

Occupation vs. Purchase Amount:
Certain occupations have higher average purchase amounts compared to others.
Customers in occupation 4 tend to spend more than customers in other occupations.

Gender vs. Purchase Amount:
There is no significant difference in purchase amount between male and female customers.
Both genders have similar average purchase amounts.

Marital Status vs. Purchase Amount:
Married customers tend to have slightly higher average purchase amounts compared to unmarried customers.
This suggests that marital status may influence spending behavior, with married individuals potentially having higher purchasing power or different spending habits.


4. Data exploration and Answering questions
4.1What products are different age groups buying?



4.2Is there a relationship between age, marital status, and the amount spent?



4.3 Are there preferred product categories for different genders?



4.4  Are women spending more money per transaction than men? Why or Why not?
4.5 Confidence intervals and distribution of the mean of the expenses by female and male customers
4.6 Are confidence intervals of average male and female spending overlapping? How can Walmart leverage this conclusion to make changes or improvements?
4.7 Results when the same activity is performed for Married vs Unmarried 
4.8 Results when the same activity is performed for Age












4.9 How does gender affect the amount spent?




4.10 How does Marital_Status affect the amount spent?



5.Final Insights  - Illustrate the insights based on exploration and CLT

Final Insights:

Age vs. Purchase Amount:
I.There is a weak positive correlation between age and purchase amount, indicating that older customers tend to spend slightly more than younger customers.
II.Customers in the 26-35 age group make up the largest segment of Walmart's customer base, and they also contribute significantly to total sales.
III.However, it's essential to note that the correlation is not very strong, suggesting that age alone may not be a significant predictor of purchase behavior.

Occupation vs. Purchase Amount:
I.Certain occupations, particularly occupation 4, show higher average purchase amounts compared to others.
II.Understanding the spending habits of customers in different occupations can help Walmart tailor marketing strategies and product offerings to better meet the needs of these segments.

Gender vs. Purchase Amount:
I.There is a slight difference in purchase amount between male and female customers.
II.Both genders contribute to total sales, indicating that Walmart's product offerings appeal to a diverse customer base.

Marital Status vs. Purchase Amount:
I.Unmarried customers tend to have slightly higher average purchase amounts compared to married customers.
II.This suggests that marital status may influence spending behavior, with unmarried individuals potentially having higher purchasing power or different spending habits.
III.Understanding the preferences and needs of married customers can help Walmart create targeted marketing campaigns and promotions to encourage higher spending.


6.Recommendations

Recommendations:

Targeted Marketing Campaigns: Develop targeted marketing campaigns tailored to specific gender, age groups, occupations, and marital status to drive higher engagement and sales.
Product Offerings: Analyze the preferences of different customer segments to optimize product offerings and inventory management.
Customer Experience: Focus on improving the overall shopping experience to increase customer satisfaction and loyalty.
Promotions and Discounts: Offer personalized promotions and discounts based on customer demographics to incentivize spending.
Data Analysis: Continue to gather and analyze customer data to identify emerging trends and opportunities for growth.

These insights and recommendations provide valuable guidance for Walmart to enhance its marketing strategies, improve customer engagement, and drive higher sales. By understanding the diverse needs and preferences of its customer base, Walmart can better position itself as a leading retailer in the market.
