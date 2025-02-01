# Atliq Grands Hospitality Domain

### Quick Links
  * [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNzc3YjBjODAtODg1Ni00NTI4LWI2YTctNGU1NzEzNjUxMGJlIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
  * [LinkedIn Post]()
  * [Presentation Video]()
  * Presentation Files
    * [PPT](https://github.com/BaderNader321/Atliq-Grands-Hospitality-Domain/blob/cf1c853b82f3b4800259da54c4aa83e788318319/Solutions/AtliQ%20Hospitality%20Presentation.pptx)
    * [PDF](https://github.com/BaderNader321/Atliq-Grands-Hospitality-Domain/blob/cf1c853b82f3b4800259da54c4aa83e788318319/Solutions/AtliQ%20Hospitality%20Presentation.pdf)

### Table of Contents
* [Company Details](#company-details)
* [Project Overview](#project-overview)
    * [Business Problem](#business-problem)
    * [Approach & Methodology](#approach-and-methodology)
    * [Key Insights & Outcomes](#key-insights-and-outcomes)
    * [Business Related Terms](#business-related-terms)
    * [Key Learnings](#key-learnings)
* [Understanding the Datasets](#understanding-the-datasets)
* [Data Modelling](#data-modelling)
* [Dashboards](#dashboards)

## Company Details

**Atliq Grands**, a leading hospitality group with over two decades of experience, operates a chain of prestigious five-star hotels across India. Their portfolio includes Atliq Bay, Atliq City, Atliq Exotica, Atliq Grands, Atliq Palace, and Atliq Seasons, strategically located in four major metropolitan cities: Bangalore, Mumbai, Hyderabad, and Delhi.

## Project Overview

### Business Problem 

Atliq Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, Atliq Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of Atliq Grands wanted to incorporate “Business and Data Intelligence” in order to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

Their revenue management team had decided to hire a 3rd party service provider to provide them insights from their historical data.

#### Task List
You are a data analyst who has been provided with sample data and a mock-up dashboard to work on the following task. You can download all relevant documents from the download section.

- Create the metrics according to the metric list.
- Create a dashboard according to the mock-up provided by stakeholders.
- Create relevant insights that are not provided in the metric list/mock-up dashboard.

### Approach and Methodology

Here’s how we’ll approach the problem and turn the data into meaningful insights:

1. **Understanding the Business and Problem at Hand**
   We’ll start by breaking down the business model to fully grasp its goals and challenges. This helps us clearly define the problem we’re solving, keeping everything focused    
   and aligned with what matters most.

2. **Getting to Know the Data**
   We’ll dive into the datasets to understand their structure, key details, and quality. This step includes cleaning and fixing any missing or inconsistent data to ensure we’re  
   working with accurate and reliable information.

3. **Planning and Mockups**
   We’ll map out the entire project with clear milestones, deadlines, and resources. To keep everyone on the same page, we’ll create a mockup of the dashboard that shows what  
   the final product will look like, helping us visualize how the insights will be presented.

4. **Building a Solid Data Foundation**
   We’ll organize the data using a star schema, a simple structure that makes storing and analyzing information more efficient. This ensures we can quickly and effectively   
   answer any key questions.

5. **Applying Advanced Analysis**
   We’ll use advanced techniques to dig deeper into the data and uncover patterns or trends. The tools we choose will depend on the type of data and the questions we’re  
   answering.

6. **Designing the Dashboard**
   The dashboard will be crafted with care to ensure it’s user-friendly, interactive, and visually appealing. It will be customized to the audience’s needs, making it easy to   
   understand and navigate.

7. **Delivering Clear Insights**
   At the end, we’ll present actionable recommendations backed by evidence. These insights will be shared in a straightforward way, ensuring everyone—regardless of their    
   technical expertise—can understand and act on the findings.

### Key Insights and Outcomes 

#### Performance Overview Section 
[Link](#performance-overview)

##### Key Metrics Overview

  - **ADR (Average Daily Rate):** The average price paid for occupied rooms per day.
  - **Realisation %:** The percentage of potential revenue that was actually realized.
  - **RevPar (Revenue Per Available Room):** A key metric indicating how effectively a hotel is filling its rooms at a profitable rate.
  - **Occupancy %:** The percentage of available rooms occupied.
  - **Cancellation %:** The percentage of bookings canceled.

##### Performance Insights

  - **Overall Revenue:** The total revenue is 551.90M, with a slight decrease of 0.37% compared to the previous period (PM: 553.93M). This slight decline warrants further investigation to understand the contributing factors.
  - **ADR (Average Daily Rate):** The ADR is 12.72K, showing a slight increase of 0.34% (PM: 12.68K). This suggests that, on average, the hotel was able to charge slightly higher rates compared to the previous period.
  - **Realisation %:** The realization rate is 70.56%, with a slight improvement of 0.72% (PM: 70.05%). This indicates that the hotel is realizing a slightly higher percentage of its potential revenue.
  - **Trends Over Time (Weeks 27-31):**
    - **ADR & RevPar:** Both ADR and RevPar show fluctuating trends across the weeks. There is a noticeable dip in week 29 for both metrics, which requires further investigation to understand the underlying causes (e.g., seasonal factors, events, or specific issues during that week).
    - **Occupancy & Cancellation %:** Occupancy and cancellation rates also show fluctuations across the weeks. A spike in cancellations during week 30 corresponds with the dip in ADR and RevPar, suggesting a possible correlation.

##### Key Observations and Potential Areas for Investigation

  - **Revenue Decline:** The slight decline in overall revenue needs to be investigated to understand the reasons behind it. Was it due to lower occupancy, lower ADR, or a combination of factors?
  - **Week 29 Dip:** The significant drop in ADR and RevPar during week 29 requires immediate attention to understand the root cause and implement corrective measures. Was it due to a drop in demand, special promotions, or other factors?
  - **Week 30 Cancellation Spike:** The increase in cancellations during week 30, coinciding with the week 29 dip, suggests a potential connection. Were there specific events or issues during that week that led to increased cancellations?
  - **Fluctuations in Trends:** The fluctuations in ADR, RevPar, Occupancy, and Cancellations across the weeks indicate potential seasonality or other factors at play. Analyzing historical data and market trends would provide a better understanding.

##### Recommendations

  - **Revenue Analysis:** Conduct a detailed analysis of revenue by segment (e.g., room type, customer segment) to identify areas of weakness and opportunities for improvement.
  - **Week 29 Investigation:** Conduct a thorough investigation of week 29 performance to identify and address the factors contributing to the revenue decline and implement preventive measures to avoid similar occurrences in the future.
  - **Cancellation Analysis:** Analyze the reasons for cancellations, particularly the spike in week 30, and implement measures to minimize cancellations.
  - **Trend Analysis:** Analyze historical data and market trends to understand the fluctuations in key metrics and develop strategies to optimize performance during peak and off-peak seasons.
  - **Market Research:** Conduct market research to understand customer preferences and demand patterns, which can inform pricing and marketing strategies.

***

#### Further Analysis Section 
[Link](#further-analysis)

##### Key Metrics Overview:

1. **Average Rating:** A measure of guest satisfaction.
2. **RevPar (Revenue Per Available Room):** A key metric indicating how effectively a hotel is filling its rooms at a profitable rate.
3. **Occupancy %:** The percentage of available rooms occupied.
4. **Cancellation %:** The percentage of bookings canceled.

##### Insights by Room Class:

1. **Average Rating:** Presidential suites have a higher average rating compared to other room classes. Standard rooms have a comparatively lower average rating.
2. **RevPar:** Presidential suites generate the highest RevPar. Standard rooms have the lowest RevPar.
3. **Occupancy %:** Standard rooms exhibit the highest occupancy rate. Presidential suites have the lowest occupancy rate.
4. **Cancellation %:** Presidential suites experience the highest cancellation rate. Standard and Elite rooms share the lowest cancellation rate.

##### Insights by City:

1. **Average Rating:** Delhi has the highest average rating among the cities. Bangalore shows a comparatively lower average rating.
2. **RevPar:** Mumbai leads in RevPar generation. Bangalore has the lowest RevPar.
3. **Occupancy %:** Mumbai demonstrates the highest occupancy rate. Bangalore has the lowest occupancy rate.
4. **Cancellation %:** Hyderabad experiences the highest cancellation rate. Bangalore has the lowest cancellation rate.

##### Overall Performance Observations:

1. **Presidential Suites:** While they command the highest RevPar and a good average rating, they have the lowest occupancy and the highest cancellation rate. This suggests a 
   potential need to review pricing strategies or marketing to attract more guests to this premium offering or understand the reasons for high cancellations.

2. **Standard Rooms:** Despite having the lowest average rating and RevPar, they have the highest occupancy and low cancellation rates. This indicates a steady demand for 
   budget-friendly options, but there might be opportunities to enhance guest experience and potentially increase pricing.

3. **Mumbai:** Consistently performs well across all metrics (high RevPar, occupancy, and a decent average rating). This suggests a strong market presence in Mumbai.

4. **Bangalore:** Shows relatively weaker performance across most metrics (low RevPar, average rating, and occupancy). This might warrant further investigation into local market 
   dynamics and competition.

##### Additional Considerations:

* **Weekdays vs. Weekends:** The data shows fluctuations in occupancy and other metrics between weekdays and weekends. This is typical for hotels and should be factored into pricing and staffing strategies.

##### Recommendations:

1. **Presidential Suites:** Investigate the high cancellation rate. Consider targeted promotions or packages to improve occupancy. Analyze pricing compared to competitors.
2. **Standard Rooms:** Explore ways to improve guest satisfaction, potentially through minor upgrades or enhanced services. Evaluate if a slight price increase could be 
   justified.
3. **Bangalore Market:** Conduct a competitive analysis to understand why performance is lagging. Explore local partnerships or marketing initiatives to boost visibility and 
   demand.
4. **Overall:** Regularly monitor and analyze these metrics to identify trends and make data-driven decisions to optimize revenue and guest satisfaction.

***

#### Revenue Insights Section 
[Link](#revenue-insights)

##### Insights by Revenue Dimensions

1. Revenue by Weeks

  - **Overall Trend:** Revenue shows a fluctuating trend across the weeks, with a noticeable dip in week 29 followed by a recovery in week 30.
  - **Specific Observations:** Week 28 shows the highest revenue at 139.73M, while week 29 has the lowest at 42.93M. This sharp decline needs further investigation to understand the underlying causes (e.g., seasonal factors, events, or specific issues during that week).

2. Revenue by Hotels

  - **Dominant Hotels:** AtliQ Exotica and AtliQ Palace contribute the most significant revenue.
  - **Lowest Contributor:** AtliQ Seasons generates the lowest revenue among the listed hotels.

3. Revenue by Room Classes

  - **Top Performers:** Elite and Premium room classes generate the highest revenue.
  - **Lowest Contributor:** Standard rooms contribute the least revenue.
  - **Note:** It would be beneficial to understand the pricing and occupancy rates for each room class to provide more in-depth insights.

4. Revenue by Hotel Categories

  - **Luxury Dominance:** Luxury hotels constitute the majority (61.77%) of the total revenue, indicating a strong preference for this category among customers.
  - **Business Contribution:** Business hotels contribute a significant portion (38.23%) of the total revenue.

5. Revenue by Platforms

  - **Offline Dominance:** Offline channels (direct offline) contribute the most substantial portion of revenue, suggesting a strong reliance on traditional booking methods.
  - **Online Channels:** Among online platforms, "others" category and MakeMyTrip (MMT) are the leading contributors.

6. Revenue by Cities

  - **Top Cities:** Mumbai and Bangalore generate the highest revenue.
  - **Lowest Contributor:** Delhi contributes the least revenue among the listed cities.

7. Revenue by Day Types

  - **Weekday Preference:** Weekdays generate significantly more revenue (63.44%) compared to weekends (36.56%), indicating a higher demand for hotel stays during business days.

##### Overall Observations and Potential Areas for Investigation

- **Week 29 Decline:** The significant drop in revenue during week 29 requires immediate attention to understand the root cause and implement corrective measures.
- **AtliQ Seasons Performance:** The low revenue from AtliQ Seasons warrants a review of its operational strategies, pricing, and market positioning to identify areas for improvement.
- **Standard Room Revenue:** While standard rooms contribute the least, it's essential to analyze their occupancy rates and pricing strategy. There might be opportunities to optimize revenue through pricing adjustments or targeted promotions.
- **Offline Reliance:** While offline channels are currently dominant, it's crucial to continue strengthening online presence and optimize digital marketing efforts to capture the growing online travel market.
- **Delhi Performance:** The lower revenue from Delhi requires further investigation to understand the local market dynamics and competition. Targeted marketing campaigns or strategic partnerships might be needed to boost revenue in this city.
- **Weekday vs. Weekend Disparity:** The significant difference in weekday and weekend revenue highlights the need for strategies to attract more weekend guests. Special packages, events, or targeted promotions could be considered.

##### Recommendations

- Conduct a thorough analysis of week 29 performance to identify and address the factors contributing to the revenue decline.
- Review the operational and marketing strategies for AtliQ Seasons to improve its revenue generation.
- Analyze the pricing and occupancy of standard rooms to optimize revenue potential.
- Continue investing in online channels and digital marketing to capture a larger share of the online travel market.
- Develop targeted strategies to improve revenue generation in Delhi.
- Design attractive weekend packages and promotions to increase weekend occupancy and revenue.

***

#### Booking Insights
[Link](#booking-insights)

##### Overall Performance

  - **Total Capacity:** 75.84K (This represents the total available room nights)
  - **Total Bookings:** 43.37K (Overall booking volume)
  - **Total Checked Out:** 30.60K (Completed stays)
  - **Total Cancelled Bookings:** 10.62K (Significant cancellations)
  - **Total No-Show Bookings:** 2.15K (Lost revenue from no-shows)
  - **Overall Occupancy Rate:** Approximately 57.2% (Calculated as Total Bookings / Total Capacity)

##### Booking Insights by Dimension

1. Bookings by Day Type

  - **Weekday Dominance:** The majority of bookings (63.62% or 28K) are for weekdays, indicating business travel or weekday events as primary demand drivers.
  - **Weekend Bookings:** Weekends account for a smaller portion (36.38% or 16K) of total bookings.

2. Bookings by Booking Platforms

  - **Offline Dominance:** Direct offline bookings are the highest (17.75K), suggesting strong reliance on traditional booking methods.
  - **Online Channels:** Among online platforms, "others" category leads (8.61K), followed by MakeYourTrip (4.78K) and LogTrip (4.39K).
  - **Lowest Online Contribution:** Tripster and Journey platforms contribute the least to online bookings.

3. Bookings by Cities

  - **Top Cities:** Mumbai (14.04K) and Hyderabad (10.30K) are the top booking sources.
  - **Lowest Contributor:** Delhi (7.80K) generates the lowest number of bookings among the listed cities.

4. Revenue Generated & Realized by Booking Status

  - **Checked Out Revenue:** The highest revenue is associated with checked-out bookings, as expected.
  - **Cancelled & No-Show Revenue:** A significant amount of revenue is lost due to cancellations (32M) and no-shows (12M).
  - **Note:** It would be helpful to see the actual revenue figures for checked-out bookings to understand the full financial picture.

5. Bookings by Hotels

  - **Top Performers:** AtliQ Palace and AtliQ Exotica lead in total bookings.
  - **Lowest Contributor:** AtliQ Seasons has the lowest booking volume.

6. Bookings by Room Class

  - **Popular Room Class:** Elite rooms are the most booked (15.95K).
  - **Lowest Booked Room Class:** Presidential suites have the lowest booking volume (5.18K).

##### Key Observations and Potential Areas for Improvement

  - **High Cancellation Rate:** The 10.62K cancellation rate is a significant concern and needs further investigation. Understanding the reasons for cancellations (e.g., pricing, events, customer experience) is essential.
  - **No-Show Impact:** The 2.15K no-shows represent lost revenue and potential opportunities for optimization (e.g., stricter no-show policies or pre-payment options).
  - **Weekend Demand:** Strategies are needed to boost weekend occupancy. Targeted promotions, events, or packages could attract weekend guests.
  - **Offline Reliance:** While offline bookings are currently strong, it's crucial to continue growing online channels to capture the increasing digital travel market.
  - **Delhi Performance:** The lower bookings from Delhi require further analysis to understand the local market dynamics and competition.
  - **AtliQ Seasons Performance:** The low booking volume for AtliQ Seasons warrants a review of its offerings, pricing, and marketing strategies.
  - **Presidential Suite Occupancy:** The low bookings for Presidential suites suggest a potential need to review pricing or enhance marketing efforts for this premium category.

##### Recommendations

  - **Cancellation Analysis:** Conduct a thorough analysis to understand the reasons behind high cancellations and implement preventive measures.
  - **No-Show Policy Review:** Evaluate and potentially strengthen no-show policies to minimize revenue loss.
  - **Weekend Promotions:** Develop targeted promotions and packages to attract more weekend guests.
  - **Online Channel Development:** Continue investing in online channels and digital marketing to diversify booking sources.
  - **Delhi Market Analysis:** Conduct market research to understand the dynamics of the Delhi market and develop targeted strategies.
  - **AtliQ Seasons Review:** Review the offerings and marketing strategies for AtliQ Seasons to improve its booking volume.
  - **Presidential Suite Marketing:** Enhance marketing efforts and potentially review pricing for Presidential suites to increase demand.

### Business Related Terms 

1. **Revenue:** This metric measures the overall revenue earned by the hospitality business.
2. **Occupancy:** It indicates how effectively the available room inventory is utilized.
3. **Average Rating:** This metric reflects customer satisfaction and service quality.
4. **Total Cancelled Bookings:** It provides insight into customer behavior and potential issues leading to cancellations.
5. **Cancellation %:** This metric helps assess the rate at which bookings are canceled.
6. **Total Checked Out:** It measures the successful fulfillment of bookings.
7. **Total No Show Bookings:** This metric highlights cases of unutilized bookings despite prior reservations.
8. **No Show Rate %:** It helps identify the proportion of unutilized bookings.
9. **ADR (Average Daily Rate):** This metric evaluates the average price paid for rooms sold.
10. **Realization %:** It measures the success rate of completed stays relative to bookings.
11. **RevPAR (Revenue Per Available Room):** It assesses the efficiency of revenue generation from room inventory.
12. **DBRN (Daily Booked Room Nights):** It indicates daily booking activity trends.
13. **DSRN (Daily Sellable Room Nights):** This metric highlights the daily sellable inventory of rooms.
14. **DURN (Daily Utilized Room Nights):** It measures how many rooms were effectively occupied daily.
15. **Bookings:** It reflects the overall booking volume for the business.
16. **Total Successful Bookings** This metric provides an overview of fulfilled reservations.

### Key Learnings 
Working on this project was a great hands-on experience in data analysis, from understanding the business problem to delivering insights through dashboards. Here are some of the biggest takeaways:

1. **Understanding the Business First:** Before jumping into the data, I had to fully understand how the hotel industry works, what metrics matter (like RevPAR and ADR), and why Atliq Grands was struggling. This helped me stay focused on solving real problems instead of just crunching numbers.

2. **Data Cleaning is Crucial:** The raw data wasn’t perfect. I had to deal with missing values, inconsistent formats, and some duplicates. This reinforced how important data cleaning is—bad data leads to bad insights.

3. **The Power of Data Modeling:** I used a star schema to organize the data, which made it easier to build relationships between tables and extract insights efficiently. Learning how to structure data properly made my analysis much smoother.

4. **Building Interactive Dashboards:** Creating the dashboard wasn’t just about placing charts on a page. I had to think about user experience—what’s the most important info, how should it be displayed, and what filters would make it easier for stakeholders to explore the data themselves?

5. **Identifying Key Trends:** I noticed patterns like the revenue drop in Week 29 and the high cancellation rate for Presidential Suites. These weren’t just random numbers—they told a story about what was happening in the business. Recognizing these trends helped me provide useful recommendations.

6. **Importance of Storytelling with Data:** Presenting insights isn’t just about showing numbers; it’s about telling a story that makes sense to decision-makers. I had to make sure my insights were clear, actionable, and backed by data.

7. **Asking the Right Questions:** Throughout the project, I kept questioning the data. Why did revenue drop in a certain week? Why are some room types performing better than others? This mindset helped me dig deeper instead of just accepting surface-level insights.

This project helped me connect the dots between data and business strategy, and it showed me how powerful data analytics can be in solving real-world problems!

## Understanding the Datasets

This datasets contains all the meta information regarding the columns described in the CSV files. Codebasics has provided 5 CSV files:
1. dim_date
2. dim_hotels
3. dim_rooms
4. fact_aggregated_bookings
5. fact_bookings

#### Column Description for dim_date:
1. **date:** This column represents the dates present in May, June and July.
2. **mmm yy:** This column represents the date in the format of mmm yy (monthname year).
3. **week no:** This column represents the unique week number for that particular date.
4. **day_type:** This column represents whether the given day is Weekend or Weekeday.

#### Column Description for dim_hotels:
1. **property_id:** This column represents the Unique ID for each of the hotels.
2. **property_name:** This column represents the name of each hotel.
3. **category:** This column determines which class[Luxury, Business] a particular hotel/property belongs to. 
4. **city:** This column represents where the particular hotel/property resides in.

#### Column Description for dim_rooms:
1. **room_id:** This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.
2. **room_class:** This column represents to which class[Standard, Elite, Premium, Presidential] particular room type belongs.

#### Column Description for fact_aggregated_bookings:
1. **property_id:** This column represents the Unique ID for each of the hotels.
2. **check_in_date:** This column represents all the check_in_dates of the customers.
3. **room_category:** This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.
4. **successful_bookings:** This column represents all the successful room bookings that happen for a particular room type in that hotel on that particular date.
5. **capacity:** This column represents the maximum count of rooms available for a particular room type in that hotel on that particular date.

#### Column Description for fact_bookings:
1. **booking_id:** This column represents the Unique Booking ID for each customer when they booked their rooms.
2. **property_id:** This column represents the Unique ID for each of the hotels
3. **booking_date:** This column represents the date on which the customer booked their rooms.
4. **check_in_date:** This column represents the date on which the customer check-in(entered) at the hotel.
5. **check_out_date:** This column represents the date on which the customer check-out(left) of the hotel.
6. **no_guests:** This column represents the number of guests who stayed in a particular room in that hotel.
7. **room_category:** This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.
8. **booking_platform:** This column represents in which way the customer booked his room.
9. **ratings_given:** This column represents the ratings given by the customer for hotel services.
10. **booking_status:** This column represents whether the customer cancelled his booking[Cancelled], successfully stayed in the hotel[Checked Out] or booked his room but not   
    stayed in the hotel[No show].
11. **revenue_generated:** This column represents the amount of money generated by the hotel from a particular customer.
12. **revenue_realized:** This column represents the final amount of money that goes to the hotel based on booking status. If the booking status is cancelled, then 40% of the        revenue generated is deducted and the remaining is refunded to the customer. If the booking status is Checked Out/No show, then full revenue generated will goes to hotels.

## Data Modelling

<img src="https://github.com/BaderNader321/Atliq-Grands-Hospitality-Domain/blob/21d42417fc9a400c5f79c6c0d10394051b001f6a/Solutions/AtliQ%20Grands%20Data%20Model.png" class="center">

## Dashboards

As part of Codebasics' Resume Project Challenge Round 2, I developed four dashboards using a dataset comprising five tables (two dimension and two fact tables). The data spans from May 1st to July 31st, 2022, These dashboards provide insights into Performance Overview, Further Analysis Revenue, and Booking trends.

1. **Performance Overview:** This dashboard summarizes key performance indicators (KPIs) like RevPAR, DSRN, and ADR to provide a quick overview of the hospitality business's  
   financial health and operational efficiency.
2. **Further Analysis:** This dashboard allows for in-depth analysis of key metrics like Average Rating, Occupancy, and Cancellation rates by various dimensions such as 
   weekday/weekend, room class, and city.
3. **Revenue Insights:** This dashboard explores revenue trends across different dimensions like week, day type, hotel, platform, category, room class, and city to help optimize    revenue strategies and drive business growth.
4. **Booking Insights:** This dashboard provides insights into booking dynamics, including booking patterns, status distributions, and revenue generated/realized, to refine  
   booking strategies and optimize room utilization.

### Home Page
<br>
<img src="https://github.com/BaderNader321/Atliq-Grands-Hospitality-Domain/blob/a9de0c3b521f38cab61d14d223e6e01cecfda72a/Files/Images/AtliQ%20Grands_Hospitality%20Domain-1.png" class="center">

### Performance Overview
<br>
<img src="https://github.com/BaderNader321/Atliq-Grands-Hospitality-Domain/blob/a9de0c3b521f38cab61d14d223e6e01cecfda72a/Files/Images/AtliQ%20Grands_Hospitality%20Domain-2.png" class="center">

### Further Analysis
<br>
<img src="https://github.com/BaderNader321/Atliq-Grands-Hospitality-Domain/blob/a9de0c3b521f38cab61d14d223e6e01cecfda72a/Files/Images/AtliQ%20Grands_Hospitality%20Domain-3.png" class="center">

### Revenue Insights
<br>
<img src="https://github.com/BaderNader321/Atliq-Grands-Hospitality-Domain/blob/a9de0c3b521f38cab61d14d223e6e01cecfda72a/Files/Images/AtliQ%20Grands_Hospitality%20Domain-4.png" class="center">

### Booking Insights
<br>
<img src="https://github.com/BaderNader321/Atliq-Grands-Hospitality-Domain/blob/a9de0c3b521f38cab61d14d223e6e01cecfda72a/Files/Images/AtliQ%20Grands_Hospitality%20Domain-5.png" class="center">

