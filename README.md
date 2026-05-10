# Airline Data Management and Analysis Using Power BI

## Overview

This project focuses on analyzing airline data using Microsoft Power BI. The main goal is to clean and organize flight, passenger, and ticket information and convert it into an interactive dashboard that provides meaningful insights.

The project demonstrates the complete Power BI workflow, including data preparation, data modeling, DAX calculations, and dashboard creation.

---

## Project Objectives

* Clean and transform raw airline data using Power Query.
* Create relationships between multiple datasets.
* Generate additional insights using calculated columns.
* Build DAX measures for key metrics.
* Design an interactive dashboard with charts and slicers.
* Implement Row-Level Security (RLS).

---

## Datasets Used

### Flight Information

Contains details about each flight:

* FlightID
* FlightNumber
* Airline
* Destination
* Status

### Passenger Information

Contains passenger-related details:

* PassengerID
* FlightID
* SeatNumber

### Ticket Information

Contains ticket booking details:

* TicketID
* FlightID
* BookingStatus

---

## Key Tasks Performed

### Data Cleaning

The datasets were imported into Power BI and cleaned using Power Query. Duplicate rows, blank values, and unnecessary columns were removed, and correct data types were assigned.

### Data Modeling

Relationships were created using the `FlightID` column to connect flight, passenger, and ticket data.

### Enhanced Data Insights

A `Performance` column was added to classify flights as **Best** or **To Be Improved** based on their status. The numeric part of the flight number was also extracted.

### DAX Calculations

Measures were created to calculate:

* Total Passengers
* Total Tickets Booked
* Total Flights

A filtered table named **Best Flights** was also created.

### Dashboard Creation

An interactive dashboard was designed with:

* Passenger Count by Airline
* Ticket Booking Status Distribution
* Flights by Airline and Destination
* Airline and Destination slicers

### Security

Row-Level Security was configured to restrict data access for a specific airline.

---

## Key Insights

* The dashboard identifies the airline with the highest number of passengers.
* Booking status analysis helps understand ticket trends.
* Destination analysis shows the operational reach of each airline.
* Flight performance classification highlights on-time flights.

---

## Tools and Technologies

* Microsoft Power BI Desktop
* Power Query
* DAX
* Microsoft Excel

---

## Project Files

* `Airline_Data_Analysis.pbix`
* `Airline_Data_Analysis_Report.pdf`
* `datasets/`
* `screenshots/`
* `README.md`

---

## How to Run the Project

1. Download or clone this repository.
2. Open the `.pbix` file in Power BI Desktop.
3. Refresh the data if needed.
4. Explore the interactive dashboard.

---

## Limitations

The report was not published to Power BI Service due to account access issues. However, all project tasks were completed successfully in Power BI Desktop.

---

## Conclusion

This project demonstrates how Power BI can be used to transform raw airline data into a structured and interactive analytical dashboard. The final solution provides valuable insights into airline operations and supports data-driven decision-making.

---

## Author

B.Varshitha
