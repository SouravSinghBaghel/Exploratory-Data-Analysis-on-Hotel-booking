# Exploratory-Data-Analysis-on-Hotel-booking
Hotel Bookings Exploratory Data Analysis

Objective
We have a dataset on hotel bookings. 
Our main goal is to perform an EDA on the given dataset and gain useful insights into the overall trends in hotel bookings and how factors drive hotel bookings.

Dataset
We are given a dataset on hotel bookings. This dataset contains booking information for a city hotel and a resort hotel. It contains the following features.
- hotel: City Hotel and Resort Hotel. 
- is_canceled: Whether the booking is cancelled or not (0 for not cancelled and 1 for cancelled).
- lead_time: time (in days) between booking transaction and actual arrival.
- arrival_date_year: Year of arrival.
- arrival_date_month: Month of arrival.
- arrival_date_week_number: Week number of arrival date.
- arrival_date_day_of_month: Day of month of arrival date.
- stays_in_weekend_nights: No. of weekend nights spent in a hotel.
- stays_in_week_nights: No. of weeknights spent in a hotel.
- adults: No. of adults in single booking record.
- children: No. of children in single booking record.
- babies: No. of babies in single booking record. 
- meal: Type of meal chosen (BB, HB, SC ….). 
- country: Country of origin of customers (PRT, GBR, FRA, ESP, DEU….).
- market_segment: Booking through medium (TA/TO, Direct, Corporate, ….).
- distribution_channel: Medium through which bookings were made (TA/TO, Direct, Corporate, ….).
- is_repeated_guest: Whether the guest visited before(0 for No and 1 for                     Yes)
- previous_cancellations: No. of previous cancelled bookings.
- previous_bookings_not_canceled: No. of previous non-cancelled bookings.
- reserved_room_type: Room type reserved by guests.
- assigned_room_type: Room type assigned to the guests.
- booking_changes: No. of booking changes done by guests.
- deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund).
- agent: I’d of agent for booking.
- company: I’d of the company making a booking.
- days_in_waiting_list: No. of days on waiting list.
- customer_type: Type of guests(Transient, Group,…..).
- adr: Average Daily rate.
- required_car_parking_spaces: No. of car parking asked during booking rooms.
- total_of_special_requests: total no. of special request made by guests.
- reservation_status: Whether guest checked out, cancelled bookings or not failed to show up. 
- reservation_status_date: Date of making reservation status.

•	Total number of rows in data: 119390
•	Total number of columns: 32


Data Cleaning
•	Creating the copy of the dataset
•	checking for duplicate values
•	checking the missing values
•	Replace the null values by 0 and NA in columns
•	Creating new column Total guest

Exploratory Data Analysis
Performed EDA and tried answering the following questions:
•	Q1- Which is the most booked hotel
•	Q2- which is busiest month in the year
•	Q3- Which hotel has the most booking for each year?
•	Q4- Which country has the highest booking and guest?
•	Q5- What is proportion of non-cancelled and cancelled reservations.
•	Q6- Which rooms in each hotel are the most frequently used?


The Matplotlib and Seaborn libraries were mostly used for pictorial representations, and the following graphs and plots were created:

•	Bar Plot.
•	Pie Chart.
•	Line Plot.
•	Heatmap


Conclusion.

After a thorough analysis of the provided csv data file, I came to the conclusion that
1.	City hotel has more booking than resort hotel. Overall, there are 27.5% Cancelled and 72.5% Non-Cancelled reservations.
2.	In the month of August and July hotel has more booking so there is lack vacant rooms available if, want to visit come in December and November months as there is less booking compared to peak times.
3.	In 2015 resort hotel has more booking whereas in 2016 city hotel has more booking.
1.	Most of the guests came from PRT (Portugal), followed by GBR (United Kingdom), FRA (France), ESP (Spain) and DEU (Germany).
4.	Room A was the most used in both hotels, followed by Room D. However, room C at the resort hotel was unused while room B at the city hall was no longer in use.


Challenges
•	There was a lot of duplicate data.
•	Data columns had lot of 0 and NAN values.
•	It was difficult to decide how to convey the data.
