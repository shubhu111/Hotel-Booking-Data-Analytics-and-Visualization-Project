# Hotel-Booking-Data-Analytics-and-Visualization-Project
Analyze hotel booking data to identify trends and insights using Power bi. Visualizations include time series charts, bar charts, donut charts. Key findings highlight seasonal trends, customer preferences, and revenue insights. Files include the analysis `hotel booking and cancellation.pbxi` and raw data `hotel_bookings_raw_data.csv`.

# Hotel Booking Data Analytics and Visualization using Power Bi.

# About Dataset :-
This dataset contains 119390 observations for a City Hotel and a Resort Hotel. Each observation represents a hotel booking between the 1st of July 2015 and 31st of August 2017, including booking that effectively arrived and booking that were canceled.

# about data columns
## hotel:-
The datasets contains the booking information of two hotel. One of the hotels is a resort hotel and the other is a city hotel.

## is_canceled:-
Value indicating if the booking was canceled (1) or not (0).

## lead_time:-
Number of days that elapsed between the entering date of the booking into the PMS and the arrival date.

## arrival_date_year:-
Year of arrival date

## arrival_date_month :-
Month of arrival date with 12 categories: “January” to “December”

## arrival_date_week_number :-
Week number of the arrival date

## arrival_date_day_of_month :-
Day of the month of the arrival date

## adults:-
Number of adults

## adults
Number of adults

## children
Number of children

## babies
Number of babies

## country
Country of origin.

## reserved_room_type
Code of room type reserved. Code is presented instead of designation for anonymity reasons.

## assigned_room_type
Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved.

## reservation_status
Check-Out – customer has checked in but already departed; No-Show – customer did not check-in and did inform the hotel of the reason why

## reservation_status_date
Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the booking canceled or when did the customer checked-out of the hotel.


# Project Overview
This project involves analyzing and visualizing hotel booking data to uncover trends, patterns, and insights that can aid in decision-making. The analysis was performed using Microsoft Power Bi, and various visualizations were created to present the data in an accessible manner.

# Objectives
- Analyze hotel booking data to identify trends and patterns.
- Visualize the data to facilitate better understanding and decision-making.
- Provide actionable insights into booking behaviors, seasonality, and customer demographics.

# Data Source
- The raw dataset (`hotel_bookings_raw_data.csv`) contains detailed information on hotel bookings, including booking status, stay duration, guest details, room preferences, and more.

# Analysis Performed
1. **Descriptive Statistics**: Summarized key metrics such as average cancellation rates, and average daily rate (ADR).
2. **Trend Analysis**: Analyzed booking trends over time, including monthly and yearly trends.
3. **Customer Segmentation**: Segmented customers based on booking behaviors and demographics.
4. **Cancellation Analysis**: Examined patterns and reasons behind booking cancellations.
5. **Revenue Analysis**: Assessed revenue generation based on different factor such as room type(Desired , Un-desired).

# Visualizations
- **Time Series Charts**: Show trends in bookings, cancellations, and ADR over time.
- **Bar Charts**: Compare different customer segments, room types, and guest types(family, single, couple ).
- **Donut Charts**: To extract the total number of hotel Bookings and Cancellations .
- **Dashboards**: Interactive dashboards to filter and explore data dynamically.

# Key Findings
- **Seasonal Trends**: Identified peak booking periods and off-seasons.
- **Customer Preferences**: Determined popular room types.
- **Booking Behaviors**: Noted average lead times and factors influencing cancellations.
  
# Files in Repository
- `hotel booking and cancellation.pbxi`: Contains the analysis and visualizations created in Power Bi.
- `hotel_bookings_raw_data.csv`: The raw dataset used for analysis.

# How to Use
1. Download the `hotel booking and cancellation.pbxi` file.
2. Open the file using Microsoft Power Bi.
3. Explore the various sheets to view the analysis and visualizations.

# Conclusion
This project provides valuable insights into hotel booking data, helping to understand customer behavior and optimize booking strategies for better revenue management.

