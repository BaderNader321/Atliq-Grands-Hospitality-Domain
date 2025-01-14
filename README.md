# Atliq-Grands-Hospitality-Domain

### Quick Links
  * [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNzc3YjBjODAtODg1Ni00NTI4LWI2YTctNGU1NzEzNjUxMGJlIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
  * [LinkedIn Post](https://www.linkedin.com/posts/badernader_business-insight-360-activity-7264969422296031232-T1a7?utm_source=share&utm_medium=member_desktop)
  * [Presentation Video](https://youtu.be/4qEMS7RKdic)
  * [Presentation File](https://youtu.be/4qEMS7RKdic)

### Table of Contents
* [Company Details](#company-details)
* [Project Overview](#project-overview)
    * [Presentation](#presentation)
    * [Approach & Methodology](#approach-and-methodology)
    * [Key Insights & Outcomes](#key-insights-and-outcomes)
    * [Business Related Terms](#business-related-terms)
    * [Technical Details](#technical-details)
    * [Key Learnings](#key-learnings)
* [Understanding the Datasets](#understanding-the-datasets)
* [Data Modelling](#data-modelling)
* [Dashboards](#dashboards)

### Company Details

### Project Overview

### Business Problem 

### Approach and Methodology

#### How We’ll Tackle This Project
Here’s how we’ll approach the problem and turn the data into meaningful insights:

1. **Understanding the Business and Problem at Hand**
   We’ll start by breaking down the business model to fully grasp its goals and challenges. This helps us clearly define the problem we’re solving, keeping everything focused and    aligned with what matters most.

2. **Getting to Know the Data**
   We’ll dive into the datasets to understand their structure, key details, and quality. This step includes cleaning and fixing any missing or inconsistent data to ensure we’re      working with accurate and reliable information.

3. **Planning and Mockups**
   We’ll map out the entire project with clear milestones, deadlines, and resources. To keep everyone on the same page, we’ll create a mockup of the dashboard that shows what the    final product will look like, helping us visualize how the insights will be presented.

4. **Building a Solid Data Foundation**
   We’ll organize the data using a star schema, a simple structure that makes storing and analyzing information more efficient. This ensures we can quickly and effectively answer    any key questions.

5. **Applying Advanced Analysis**
   We’ll use advanced techniques like [add relevant examples, e.g., machine learning, statistical modeling] to dig deeper into the data and uncover patterns or trends. The tools     we choose will depend on the type of data and the questions we’re answering.

6. **Designing the Dashboard**
   The dashboard will be crafted with care to ensure it’s user-friendly, interactive, and visually appealing. It will be customized to the audience’s needs, making it easy to   
   understand and navigate.

7. **Delivering Clear Insights**
   At the end, we’ll present actionable recommendations backed by evidence. These insights will be shared in a straightforward way, ensuring everyone—regardless of their    
   technical expertise—can understand and act on the findings.

#### Key Insights and Outcomes 

#### Business Related Terms 

1. **Revenue:** To get the total revenue_realized
2. **Occupancy:** Occupancy means total successful bookings happened to the total rooms available(capacity)
3. **Average Rating:**	Get the average ratings given by the customers
4. **Total cancelled bookings:**	To get the "Cancelled" bookings out of all Total bookings happened
5. **Cancellation %:** calculating the cancellaton percentage.
6. **Total Checked Out:**	To get the successful 'Checked out' bookings out of all Total bookings happened
7. **Total No Show Bookings:**	"To get the""No Show"" bookings out of all Total bookings happened ("No show"" means those customers who neither cancelled nor attend to their   
   booked rooms)
8. **No Show rate %:**	calculating the no show percentage.
9. **ADR (Average Daily rate):** It is the ratio of revenue to the total rooms booked/sold. It is the measure of the average paid for rooms sold in a given time period.
10. **Realisation %:**	calculate  the realisation percentage. It is nothing but the succesful ""checked out"" percentage over all bookings happened.
11. **RevPAR (Revenue Per Available Room):** RevPAR represents the revenue generated per available room, whether or not they are occupied. RevPAR helps hotels measure their   
    revenue generating performance to accurately price rooms.
12. **DBRN	(Daily Booked Room Nights):** This metrics tells on average how many rooms are booked for a day considering a time period.
13. **DSRN	(Daily Sellable Room Nights):** This metrics tells on average how many rooms are ready to sell for a day considering a time period.
14. **DURN	(Daily Utilized Room Nights):** This metric tells on average how many rooms are succesfully utilized by customers for a day considering a time period.
15. **Bookings:** To get the total number of bookings happened
16. **Total Successful Bookings:** To get the total succesful bookings happened for all hotels

#### Technical Details 

#### Key Learnings 

### Understanding the Datasets

This datasets contains all the meta information regarding the columns described in the CSV files. Codebasics has provided 5 CSV files:
1. dim_date
2. dim_hotels
3. dim_rooms
4. fact_aggregated_bookings
5. fact_bookings

##### Column Description for dim_date:
1. **date:** This column represents the dates present in May, June and July.
2. **mmm yy:** This column represents the date in the format of mmm yy (monthname year).
3. **week no:** This column represents the unique week number for that particular date.
4. **day_type:** This column represents whether the given day is Weekend or Weekeday.

##### Column Description for dim_hotels:
1. **property_id:** This column represents the Unique ID for each of the hotels.
2. **property_name:** This column represents the name of each hotel.
3. **category:** This column determines which class[Luxury, Business] a particular hotel/property belongs to. 
4. **city:** This column represents where the particular hotel/property resides in.

##### Column Description for dim_rooms:
1. **room_id:** This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.
2. **room_class:** This column represents to which class[Standard, Elite, Premium, Presidential] particular room type belongs.

##### Column Description for fact_aggregated_bookings:
1. **property_id:** This column represents the Unique ID for each of the hotels.
2. **check_in_date:** This column represents all the check_in_dates of the customers.
3. **room_category:** This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.
4. **successful_bookings:** This column represents all the successful room bookings that happen for a particular room type in that hotel on that particular date.
5. **capacity:** This column represents the maximum count of rooms available for a particular room type in that hotel on that particular date.

##### Column Description for fact_bookings:
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

### Data Modelling

<img src="" class="center">

### Dashboards

As part of Codebasics' Resume Project Challenge Round 2, I developed four dashboards using a dataset comprising five tables (two dimension and two fact tables). The data spans from May 1st to July 31st, 2022, These dashboards provide insights into Performance Overview, Further Analysis Revenue, and Booking trends.

1. **Performance Overview:** This dashboard summarizes key performance indicators (KPIs) like RevPAR, DSRN, and ADR to provide a quick overview of the hospitality business's  
   financial health and operational efficiency.
2. **Further Analysis:** This dashboard allows for in-depth analysis of key metrics like Average Rating, Occupancy, and Cancellation rates by various dimensions such as 
   weekday/weekend, room class, and city.
3. **Revenue Insights:** This dashboard explores revenue trends across different dimensions like week, day type, hotel, platform, category, room class, and city to help optimize    revenue strategies and drive business growth.
4. **Booking Insights:** This dashboard provides insights into booking dynamics, including booking patterns, status distributions, and revenue generated/realized, to refine  
   booking strategies and optimize room utilization.

