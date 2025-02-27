# Rockbuster Stealth LLC - SQL Queries
**Project Overview**: Analyzing **Rockbuster Stealth LLC**'s 2005-2006 movie rental data to generate actionable insights and guide the launch strategy for their new online streaming platform. 

Main Recommendations: 
1) Focus on normalized averages for customer behavior to mitigate the risk of overestimating markets influenced by outliers (important for Rockbuster in particular, with their highly dispersed and unevenly distributed customer base); this provides a more reliable foundation for predicting growth opportunities.
2) Normalizing rentals against the inventory for each genre shows that the top 5 genres with greatest growth potential are: 1) Sci-Fi; 2) Action; 3) Animation; 4) Classics; 5) Drama. For outlier countries, however (i.e. significantly higher or lower rentals per customer), a more localized exploration of genre popularity is advisable.
3) Rental frequency and spending show a clear decline, from New Customers to Long-Tenured Customers-- strategies such as subscription models or loyalty programs will help enure long-term revenue stability and growth.
4) **Above all**, over 25% of Rockbuster's revenue came from **late fees**--a fragile source of income as customer behavior shifts and competition from streaming services increases. Experimenting with **tiered subscription plans** would be a good first step to designing a business model that does not rely on transactional penalties.  

View full storyboard here: [Rockbuster Stealth Analysis](https://public.tableau.com/app/profile/amy.zhang8641/viz/Rockbusterdataanalysis_1/Story1)

## Index (Storyboard Slide # : SQL Query for the corresponding visualization)

Slides 1&2: Maps of Customer Distribution 
granular_rental_table_2

Slide 2: Histograms of Customer Distribution 
district_histogram
country_histogram
 
Slide 3: Scatterplots of Avg. Rental Frequency & Revenue Per Rental  
country_engagement_TABLE (composite of: 'country_analysis' & 'country_engagement_analysis' queries)
stddev_absolutes

Slide 5: Bar Graph - Genre Popularity (normalized by Inventory)  
genre_popularity_norm

Slide 5: Heatmap - Outlier Countries Genre Analysis  
avg_rentals_outliers 
(post-facto) Correction
genre_popularity_country

Slide 6: Scatterplot & Box-Whisker Graph - Tenure Length Analysis  
customer_engagement_district
(post-facto) Correction

Slide 7: Pie Chart - Revenue Breakdown
late_charge_noneg

Slide 7: Rental Rate Mode Graph
country_engagement_TABLE (same as 'Slide 3: Scatterplots'; **see above**)

