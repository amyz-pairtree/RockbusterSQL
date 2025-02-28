# Rockbuster Stealth LLC - SQL Queries
📌 **Project Overview**
Analyzing Rockbuster Stealth LLC’s 2005-2006 rental data to uncover trends, optimize customer targeting, and guide the launch of their new streaming platform.

**Key Insights & Recommendations**:

✅ Normalize Customer Behavior Metrics
To avoid overestimating market potential, focus on normalized averages rather than raw totals—especially given Rockbuster’s highly dispersed and unevenly distributed customer base.

✅ Top Growth Genres (Normalized by Inventory)
Sci-Fi, Action, Animation, Classics, and Drama show the highest growth potential. However, in outlier countries (where rentals per customer are unusually high or low), a localized genre analysis is recommended.

✅ Retention Strategies Needed
Rental frequency and spending decline as customers move from “New” to “Long-Tenured.” Implementing subscription models or loyalty programs can stabilize long-term revenue.

✅ Late Fees: A Risky Crutch
Over 25% of revenue comes from late fees—a fragile source as streaming competition grows. Introducing tiered subscription plans would help transition to a sustainable revenue model.

🔗 View full storyboard here: [Rockbuster Stealth Analysis](https://public.tableau.com/app/profile/amy.zhang8641/viz/Rockbusterdataanalysis_1/Story1)

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

🔥 co-author: ChatGPT
