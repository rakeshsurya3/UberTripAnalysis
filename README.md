#Uber Trip Analysis

1. Project Overview
This Power BI project aims to analyze Uber trip data to provide actionable insights into booking trends, revenue generation, and trip efficiency. The analysis is structured across three dashboards: Overview Analysis, Time Analysis, and a Details Tab for granular data exploration. The insights gained from these dashboards will enable stakeholders to make data-driven decisions to optimize operations, pricing strategies, and enhance customer satisfaction. 
2. Dashboard 1: Overview Analysis
•	Purpose: Provides a high-level summary of key performance indicators (KPIs) and trip characteristics. 
•	Key Performance Indicators (KPIs): 
o	Total Bookings: The total number of trips booked. 
o	Total Booking Value: The total revenue generated from all bookings. 
o	Average Booking Value: The average revenue per trip. 
o	Total Trip Distance: The total distance covered by all trips. 
o	Average Trip Distance: The average distance traveled per trip. 
o	Average Trip Time: The average duration of trips. 
•	Visualizations: 
o	Measure Selector: Allows users to dynamically switch between Total Bookings, Total Booking Value, and Total Trip Distance.
o	Analysis by Payment Type: Charts showing KPIs segmented by payment methods (e.g., Card, Cash, Wallet). 
o	Analysis by Trip Type: Charts comparing Day and Night trips. 
o	Vehicle Type Analysis: A grid view (table or matrix) displaying KPIs for different vehicle types (e.g., UberX, UberXL, Uber Black). 
o	Total Bookings by Day: A chart illustrating daily booking trends. 
o	Location Analysis: 
	Most Frequent Pickup Point: Identifies the most common trip starting locations. 
	Most Frequent Drop-off Point: Identifies the most common trip ending locations. 
	Farthest Trip: Shows the trip with the maximum distance traveled. 
	Total Bookings by Location (Top 5): Shows the top 5 locations with the highest trip bookings. 
	Most Preferred Vehicle for Location Pickup: Shows the most frequently booked vehicle type at each pickup location. 
•	Additional Enhancements: 
o	Dynamic Titles: Chart titles update based on the selected measure. 
o	Slicers: Filters for Date, City, and other relevant dimensions. 
o	Tooltips: Interactive tooltips to display additional details. 
o	Bookmarks: "Data Details" bookmark for explanations. 
o	Clear Slicer Button: Button to reset all filters. 
o	Download Raw Data Button: Button to export data. 
3. Dashboard 2: Time Analysis
•	Purpose: Analyzes trip patterns and demand trends across different time intervals. 
•	Global Dynamic Measure: A measure selector to switch between Total Bookings, Total Booking Value, and Total Trip Distance, applied across all visuals in this dashboard. 
•	Visualizations: 
o	By Pickup Time (10-Minute Intervals): An area chart showing bookings in 10-minute intervals. 
o	By Day Name: A line chart showing booking trends across days of the week. 
o	By Hour and Time: A heatmap (matrix grid) visualizing the selected measure (e.g., Total Bookings) by hour of the day and day of the week. 
4. Dashboard 3: Details Tab
•	Purpose: Provides a detailed, granular view of trip data. 
•	Features: 
o	Grid Table: A table displaying essential trip details. 
o	Drill-Through Functionality: Enables users to navigate from other dashboards to this tab to see detailed records. 
o	Bookmark for Full Data View: A bookmark to toggle between filtered (drill-through) data and the complete dataset. 

5. Key Insights 
•	Overview Analysis 
o	Total bookings are 103.7K, and the total booking value is $1.6M, with an average booking value of $15.
o	The average trip distance is 3 miles, and the average trip time is 16 minutes.
o	"Uber Pay" and "Cash" are the two dominant payment types.
o	Day Trips are slightly more than Night Trips.
o	UberX has the highest number of bookings, while UberXL has the highest average booking value.
o	Penn Station/Madison Sq West is the most frequent pickup point, and Upper East Side North is the most frequent drop-off point.
•	Time Analysis 
o	The highest number of bookings is on Friday.
o	Bookings vary throughout the hours of the day, showing peak and off-peak times.

