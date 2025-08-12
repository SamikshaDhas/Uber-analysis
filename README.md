# Uber-analysis
🚖 Uber Trip Analysis – Power BI Dashboard
📌 Project Overview
This project presents a comprehensive analysis of Uber trips for the month of June 2024, leveraging Power BI for interactive data visualization. The dashboard provides insights into trip trends, booking patterns, payment preferences, location analysis, and vehicle performance.

📊 Dashboard Highlights
Key Metrics
Total Bookings: 103.7K

Total Booking Value: $1.6M

Average Booking Value: $15

Total Trip Distance: 349K miles

Average Trip Distance: 3 miles

Average Trip Time: 16 minutes

Insights & Analysis
1. Payment Mode Analysis
Uber Pay dominates with 71% of total booking value ($1.09M).

Cash contributes 29% ($443K), while other payment modes are minimal.

2. Day vs Night Trips
Night Trips: 63% of total value ($975K)

Day Trips: 37% ($579K)

3. Location Analysis
Most Frequent Drop-off: Upper East Side North

Most Frequent Pickup: Penn Station / Madison Sq West

Farthest Trip: Lower East Side → Crown Heights North (144.1 miles)

4. Vehicle Type Performance
Vehicle Type	Total Bookings	Total Value	Avg Value	Distance (miles)
UberX	38,744	$583,880	$15	131,496
Uber Comfort	17,078	$2,53,995	$15	56,790
Uber Black	16,710	$2,50,192	$15	56,149
UberXL	16,698	$2,49,424	$15	55,721
Uber Green	14,498	$2,16,181	$15	48,778

🛠 Tech Stack
Power BI Desktop – Dashboard creation

Power Query – Data cleaning & transformation

DAX Formulas – Custom measures & KPIs

Data Modeling – Relationship building between tables

File Format: .pbix

📂 Data Source
The dataset used for this analysis is Uber trip data, extracted from YouTube-provided datasets for educational and analytical purposes.

🎯 Key Questions Answered by Dashboard
What are the total trips, revenue, and average booking value?

Which payment methods are most used by customers?

How do day and night trips compare in terms of revenue?

What are the most common pickup and drop-off points?

Which vehicle type generates the most bookings and distance traveled?

📸 Dashboard Preview

📌 Conclusion
This Uber Trip Analysis Dashboard helps in identifying peak locations, preferred payment modes, and vehicle type preferences. Businesses can use these insights to improve fleet management, marketing strategies, and customer experience

![Uber Trip Analysis Dashboard](https://raw.githubusercontent.com/SamikshaDhas/Uber-analysis/main/Screenshot%202025-08-12%20112318.png)


⏳ Uber Trip Analysis – Time Analysis Dashboard
📌 Overview
The Time Analysis section of the Uber Trip Analysis project focuses on understanding when bookings happen, both by hour of the day and day of the week.
This analysis is crucial for:

Identifying peak demand periods

Optimizing driver allocation

Planning surge pricing strategies

Improving customer service availability during high-traffic times

The dashboard is built using Power BI and integrates time-based KPIs with interactive visuals to uncover patterns in booking behavior for June 2024.

📊 Key Performance Metrics
Total Bookings: 103.7K

Total Booking Value: $1.6M

Average Booking Value: $15

Total Trip Distance: 349K miles

Average Trip Distance: 3 miles

Average Trip Duration: 16 minutes

These figures remain consistent across all report pages, ensuring uniform KPI tracking.

🔍 Detailed Insights
1️⃣ Total Booking Value by Pickup Hour
The day starts slow with low demand between 12:00 AM – 5:00 AM.

Significant increase begins after 6:00 AM, with a steady rise until midday.

Peak booking value hours are 3:00 PM – 5:00 PM, each exceeding $20K in booking value.

Demand gradually declines after 8:00 PM, but remains higher than early-morning hours.

Business Implication:

Increase driver availability during peak afternoon slots.

Introduce time-specific promotions during early mornings to boost off-peak usage.

2️⃣ Total Booking Value by Day of the Week
Highest Booking Days:

Saturday & Sunday (~$0.28M each) – reflects strong weekend travel patterns.

Mid-range Booking Days:

Tuesday & Wednesday (~$0.22M – $0.24M) – midweek work travel spikes.

Lowest Booking Day:

Friday ($0.15M) – potential dip due to remote work or early weekend travel.

Business Implication:

Plan weekend surge pricing and extra driver coverage.

Investigate Friday dip – could be a marketing opportunity.

3️⃣ Hourly & Weekly Patterns – Heatmap View
Dark shades indicate high booking values.

Weekends: Afternoon and evening hours are the most lucrative.

Weekdays: Midday shows stable bookings but fewer extreme peaks.

Early mornings (Mon–Sun, 12 AM – 6 AM) consistently record the lowest activity.

Business Implication:

Target weekend afternoons for high-value rides.

Consider driver shift scheduling that overlaps with weekday midday and weekend evening peaks.

🛠 Tech Stack & Methodology
Power BI Desktop – Interactive dashboard creation

Power Query – Data cleaning and time-based grouping

DAX Formulas – Calculated measures for total bookings, average value, and peak hour detection

Data Modeling – Linking trip data with a calendar table for advanced time intelligence

Visualization Types:

Area charts for hourly trends

Line charts for day-of-week comparisons

Heatmaps for hourly-weekly patterns

📂 Data Source
The dataset is Uber trip data obtained from a publicly available source (YouTube dataset) and prepared for educational & analytical purposes.

🎯 Questions Answered by Time Analysis
When are the busiest hours of the day for Uber rides?

Which days of the week generate the highest revenue?

Are weekends or weekdays more profitable?

What is the relationship between time of day and booking value?

How can drivers’ schedules be optimized for maximum earnings?

📸 Dashboard Preview

📌 Conclusion
The Time Analysis Dashboard reveals clear patterns:

Afternoons and weekends dominate in booking volume and revenue.

Early mornings are consistently underperforming, representing untapped market potential.

The findings support data-driven scheduling, pricing adjustments, and marketing campaigns tailored to high-demand times

## Time Analysis Dashboard Preview

![Time Analysis Dashboard](https://raw.githubusercontent.com/SamikshaDhas/Uber-analysis/main/Screenshot%202025-08-12%20112344.png)

📄 Uber Trip Analysis – Detailed Trip Data
📌 Overview
The Details Page of the Uber Trip Analysis dashboard presents the raw trip-level dataset for June 2024, offering a complete view of individual bookings.
This section allows for deep-dive investigations into specific rides, enabling validation of aggregated insights from the Overview and Time Analysis dashboards.

📊 Data Table Columns
Column Name	Description
Trip ID	Unique identifier for each trip
Pickup Date	Date of trip pickup
Pickup Hour (bins)	Time bin for trip pickup, grouped into hourly intervals
Vehicle	Type of Uber service (UberX, Uber Comfort, Uber Black, UberXL, Uber Green)
Payment Type	Mode of payment (Uber Pay, Cash, Amazon Pay, Google Pay)
Passenger Count	Number of passengers for the trip
Trip Distance	Distance traveled in miles
Booking Value	Revenue generated from the trip (USD)
Total Booking	Count of bookings (generally 1 per row)

📌 Summary Totals (June 2024)
Total Trips: 146,478

Total Distance: 348,933.81 miles

Total Booking Value: $1,553,672.8

Total Bookings: 103,728

🔍 Insights from the Details Data
Most Frequent Vehicle: UberX leads in trip volume.

Payment Preference: Uber Pay is the dominant payment method, followed by Cash.

Passenger Count: Majority of rides have 1 passenger; some Uber Comfort trips have 2 passengers.

Distance Patterns: Trips vary from short city rides (~1 mile) to long-distance trips exceeding 10 miles.

High-Value Rides: Longer trips and premium vehicles (Uber Black, Uber Comfort) contribute more per booking.

🛠 How This Page Helps
Data Validation: Cross-check totals against aggregated KPIs in other dashboard views.

Trend Investigation: Filter by date, time, or vehicle type to find anomalies.

Operational Insights: Identify frequent high-value routes and potential areas for fleet optimization.

📸 Dashboard Preview

📌 Conclusion
The Details Page provides a transaction-level lens into Uber operations, complementing the aggregated views in the Overview and Time Analysis dashboards. This granular visibility ensures accuracy, supports decision-making, and helps uncover patterns not visible in summary charts.

##  Detailed Trip Data Overview

Explore the granular details of every trip taken in June 2024 in the **Details** section. This table offers a full breakdown of each booking, enabling validation and deep-dive analysis:

![Detailed Trip Data](https://raw.githubusercontent.com/SamikshaDhas/Uber-analysis/main/Screenshot%202025-08-12%20112409.png)

