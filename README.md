#Examining the Impact of Demographic and Employment Changes on Robbery Rates in San Francisco Neighborhoods
#Weichun_Liao
Introduction
San Francisco, a city renowned for its vibrant and diverse communities, has long been a prime pilot site for urban research. In recent years, San Francisco's crime problem has become increasingly difficult to ignore, with robbery playing an important part in it. Understanding the factors that influence these crimes is crucial for effective policy-making. This blog explores the relationship between changes in racial demographics, unemployment rates, and robbery rates across five key neighborhoods.
Research Goals and Methodology
My analysis aims to:
Identify the top five neighborhoods with the highest robbery numbers.
Analyze the correlation between changes in robbery rates and changes in racial demographic proportions.
Investigate whether unemployment rate changes influence robbery rates.


Data Sources
The data used in this analysis includes:
Robbery Data: Robbery incidents from 2018 to 2022 across various neighborhoods in San Francisco. https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/wg3w-h783/about_data. 
Demographic Data: Racial demographic proportions per neighborhood. https://data.census.gov/table/ACSDT5Y2022.B02001?t=Race%20and%20Ethnicity&g=050XX00US06075$1400000. 
Unemployment Data: Unemployment rates per neighborhood. https://data.census.gov/table?t=Employment&g=050XX00US06075$1400000. 

Identifying the Top 5 Neighborhoods
Aggregating robbery data across all years, I identified the following neighborhoods as having the highest total robbery counts:
Tenderloin, Mission, Financial District/South Beach, South of Market, Bayview Hunters Point
These neighborhoods are the focus of my subsequent analyses. Figure.1 shows how numbers of robbery incidents change overtime. 
![Description of the Image](top_5_robbery_neighborhoods_line_chart_2018_2022.png)
Figure.1

Analyzing Unemployment Rate Changes and Robbery Rates
To investigate whether unemployment rates impact robbery rates, I first visualized changes in unemployment rates over time in these five neighborhoods as Figure.2. Then, I came up with a  null hypothesis that the unemployment rate affects the number of robberies. I calculated the correlation coefficient and p-value between changes in the unemployment rate and robbery rates across the five neighborhoods. 
![Description of the Image](Unemployment_Rate_Change_Selected_Neighborhoods.png)
Figure.2

Results Summary:
Mission Neighborhood
Correlation: -0.24
P-Value: 0.70
Interpretation: No significant relationship found between the unemployment rate and robbery counts.
Tenderloin Neighborhood
Correlation: -0.88
P-Value: 0.0496
Interpretation: Significant negative correlation between the unemployment rate and robbery counts (P-Value < 0.05). As the unemployment rate decreases, robberies tend to increase.
Financial District/South Beach Neighborhood
Correlation: -0.91
P-Value: 0.0294
Interpretation: Significant negative correlation between the unemployment rate and robbery counts (P-Value < 0.05). As the unemployment rate decreases, robberies tend to increase.
South of Market Neighborhood
Correlation: -0.39
P-Value: 0.52
Interpretation: No significant relationship found between the unemployment rate and robbery counts.
Bayview Hunters Point Neighborhood
Correlation: -0.82
P-Value: 0.0917
Interpretation: Moderate negative correlation between the unemployment rate and robbery counts, but the relationship is not statistically significant (P-Value > 0.05).
Summary
For the Tenderloin and Financial District/South Beach neighborhoods, the p-values are below 0.05, indicating significant evidence to reject the null hypothesis in these neighborhoods.

Analyzing Demographic Changes and Robbery Rates
To understand the relationship between changes in robbery counts and racial demographics, I created line charts of these five neighborhood (From Figure.3 - Figure.7), and then decided to consider the proportions of four main racial groups:
White
Black
Asian
Other Race
![Description of the Image](Tenderloin_Race_Percentage_Change_Figure_Label.png)

![Description of the Image](Mission_Race_Percentage_Change_Figure_Label.png)

![Description of the Image](Financial_District_South_Beach_Race_Percentage_Change_Figure_Label.png)

![Description of the Image](South_of_Market_Race_Percentage_Change_Figure_Label.png)

![Description of the Image](Bayview_Hunters_Point_Race_Percentage_Change_Figure_Label.png)

I calculated the correlation coefficient, p-value, and R² score for changes in these proportions relative to changes in robbery counts in each neighborhood.
Correlation Analysis Results
Mission Neighborhood:
Black Proportion Change:
Coefficient: -8097
p-value: 0.8464
R² Score: 0.4800
White Proportion Change:
Coefficient: -128
p-value: 0.5081
R² Score: 0.0003
Asian Proportion Change:
Coefficient: -48444
p-value: 0.8997
R² Score: 0.6389
Other Race Proportion Change:
Coefficient: 4030
p-value: 0.0448
R² Score: 0.8288
Interpretation:
Strong negative correlations between changes in robbery counts and both Black and Asian proportion changes suggest that decreases in these demographics are associated with increases in robberies.
Positive correlation with Other Race proportion changes.

Tenderloin Neighborhood:
Black Proportion Change:
Coefficient: 2262
p-value: 0.0771
R² Score: 0.7153
White Proportion Change:
Coefficient: -461
p-value: 0.6054
R² Score: 0.0444
Asian Proportion Change:
Coefficient: -1616
p-value: 0.7194
R² Score: 0.1925
Other Race Proportion Change:
Coefficient: 136
p-value: 0.4726
R² Score: 0.0030
Interpretation:
Strong positive correlation between changes in robbery counts and Black proportion changes.
Moderate to weak negative correlations with Asian and White proportion changes.

Financial District/South Beach Neighborhood:
Black Proportion Change:
Coefficient: 781
p-value: 0.2991
R² Score: 0.1615
White Proportion Change:
Coefficient: -1367
p-value: 0.7698
R² Score: 0.2912
Asian Proportion Change:
Coefficient: -490
p-value: 0.7444
R² Score: 0.2390
Other Race Proportion Change:
Coefficient: 2347
p-value: 0.0570
R² Score: 0.7851
Interpretation:
Moderate positive correlation with Black proportion changes.
Strong positive correlation with Other Race proportion changes.
Moderate to strong negative correlations with White and Asian proportion changes.

South of Market Neighborhood:
Black Proportion Change:
Coefficient: -2030
p-value: 0.7059
R² Score: 0.1696
White Proportion Change:
Coefficient: 786
p-value: 0.2567
R² Score: 0.2369
Asian Proportion Change:
Coefficient: -1051
p-value: 0.6215
R² Score: 0.0591
Other Race Proportion Change:
Coefficient: -1823
p-value: 0.7918
R² Score: 0.3405
Interpretation:
Moderate negative correlations with changes in Black and Asian proportions.
Moderate positive correlation with White proportion changes.
Negative correlation with Other Race proportion changes.

Bayview Hunters Point Neighborhood:
Black Proportion Change:
Coefficient: -1807
p-value: 0.8080
R² Score: 0.3794
White Proportion Change:
Coefficient: -1986
p-value: 0.7415
R² Score: 0.2333
Asian Proportion Change:
Coefficient: -2716
p-value: 0.7767
R² Score: 0.3062
Other Race Proportion Change:
Coefficient: 6167
p-value: 0.0066
R² Score: 0.9736
Interpretation:
Strong negative correlations with Black, White, and Asian proportion changes.
Very strong positive correlation with Other Race proportion changes.


Conclusion
The analysis revealed different relationships between demographic changes and robbery rates in the top five neighborhoods. The results showed that changes in the proportion of blacks, whites and Asians did not significantly affect robbery crime in all five neighborhoods. But in the Mission and Bayview Hunters Point neighborhoods, changes in the proportion of the population of other races had a significant impact on robbery crime. Of course, more research is needed to explore whether changes in the racial composition of neighborhoods lead to changes in robbery crime rates. Second, and surprisingly, the study demonstrated no statistically significant relationship between unemployment and robbery rates, challenging the widely held assumption that high unemployment leads to increased crime. Understanding the complex interactions between unemployment, demographic changes, and crime rates can help policymakers and communities develop more effective crime prevention strategies. Exploring other socioeconomic factors, such as education, housing affordability, and community programs, can yield deeper insights into the crime phenomenon. This may be my goal for future projects.
