# Online Hotel Reservation Analysis


## 	Project overview
This project analyzes full year online reservation from different online websites for the comfort inn hotels across the major U.S. cities. The objective is to understand revenue performance, platform usage and Monthly trends using real world style reservation data. 
This analysis helps hotel management and business analysts make data driven decisions related to pricing strategies, marketing channels and demand forecasting.

## 	Dataset description 
The dataset contains hundreds and thousands of comfort inn hotel reservations through different online websites:
	Reservation ID 
	Reservation Date 
	Hotel Name 
	City 
	Booking websites
	Check – in & Check – out Dates
	Number of Rooms 
	Number of Guests 
	Price (USD)
This Data spans the entire year, covering multiple cities and booking platforms.
## Data Privacy and Anonymization Note:
## Important Disclaimer:
This dataset is not 100% real world data. To protect customer privacy and maintain trust in the hotel business and booking platforms data masking, Value modifications and anonymization technique were applied. 
No personally identifiable information (PII) is included. The dataset is intended solely for academic, analytical and demonstration purposes.

# Investment Objective of the Data Analysis
The primary objective of this analysis is to evaluate hotel reservation data to identify the (Q1) Most revenue earned city?
(Q2) Most booked rooms in a different city?
(Q3) Which is the most used website for reservation?
(Q4) In which month are the highest reservations made?

## Answer 1) The objective of this analysis is to identify the city that generated the highest total revenue from hotel reservations during the year.
To conduct this analysis the dataset is processed using Jupyter Notebook. The total revenue is calculated by aggregating the Price_USD values for each city then sorted in descending order to clearly compare revenue performance across all cities. A bar chart is generated to visually represent total revenue by city and to highlight differences in revenue contribution. The results show that Miami generated the highest total revenue among all cities included in the dataset. 
<img width="940" height="536" alt="image" src="https://github.com/user-attachments/assets/733aa674-e4a0-44dd-be7a-f7b53923c475" />
<img width="940" height="560" alt="image" src="https://github.com/user-attachments/assets/4b524fec-4f8d-4b5d-a10c-2f2b1db002fe" />

Explanation: Miami recorded the highest total revenue among all cities.
Result: Miami – $20,816,582

## 	Answer 2) In this analysis we identify the city with the highest number of room bookings, which serves as an indicator of overall customer demand.

<img width="939" height="389" alt="image" src="https://github.com/user-attachments/assets/95c59850-b32e-48b5-a61d-c4a1aca019e7" />
The analysis performed using excel and Jupyter Notebook by counting the total number of reservations for each city. The data is grouped by city and sorted to determine which location recorded the highest booking volume. Line graph represents reservation count across cities. This result indicates that Miami recorded the highest number of room bookings among all cities analyzed.
<img width="940" height="626" alt="image" src="https://github.com/user-attachments/assets/8cd92754-8333-447e-a259-c63eac4020d0" />

## 3) The objective of this analysis is to determine which onlline booking platform is most frequently used by customer for hotel reservations.
<img width="940" height="668" alt="image" src="https://github.com/user-attachments/assets/93aa0cc6-09f6-46d1-ac83-fdf697f0289a" />
To perform this analysis, reservations count is grouped by Booking websites using power BI and total number of reservations for each platform was calculated. A pie chart was generated to visually represent the proportion of booking across different websites making it easy to compare platform usage. 
This analysis shows that Hotels.com had the highest number of reservations among all booking websites.
Result 
## Most used Booking Website: Hotels.com 
## Total Reservations : 20,143
The Pie chart illustrates that Hotels.com accounts the largest share of hotel reservations and it is slightly ahead of Expedia, Agoda, Airbnb and Booking.com. This indicates strong customer preference and trust in Hotel.com as a reservation platform.

## 	Answer 4) This analysis identify the month with the highest number of hotel reservations, which helps in understanding seasonal demand and planning for peak period.

<img width="940" height="420" alt="image" src="https://github.com/user-attachments/assets/efa74efb-76f4-4d9e-9f2f-0be8aab235da" />

<img width="926" height="570" alt="image" src="https://github.com/user-attachments/assets/8999b06e-4b7e-4b0a-91aa-9c699e32fbcd" />

<img width="939" height="643" alt="image" src="https://github.com/user-attachments/assets/7f55d02a-bd10-4e91-bae4-70250dd6c0c9" />
The analysis is performed in excel, Jupyter notebook and Power BI and the total number of reservations for each month was calculated. A bar chart and line chart are generated to visually compare monthly reservation volumes.
The results show that December recorded the highest number of reservations among all months.

## Conclusion: 
The project combines Excel, Power Bi and Jupyter notebook to perform comprehensive analysis of full year online reservation data for the comfort inn Hotels. Excel is used for initial data storage and structure and Jupyter notebook enabled data cleaning, transformation and analytical calculations and power Bi is utilized to create interactive visualization and dashboard for business insights.
