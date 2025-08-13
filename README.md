"""
CodeAlpha Task 3 - Data Visualization
This project is completed as part of the CodeAlpha Data Analytics Internship for Task 3: Data Visualization.

## 📌 Project Objective
The objective of this project is to **analyze airline ticket prices and present them visually**. 
The project is developed using Python, Pandas, Matplotlib, and Seaborn. 
Based on the analysis, users and businesses can make informed decisions about flight prices.

---

## 📊 About the Dataset
- The dataset covers airlines, flight numbers, source and destination cities, departure time, stops, class, duration, days left to flight, and prices.
- Source: Simulated flight data (structured similarly to real flight data).

| Column            | Description                        |
|------------------|------------------------------------|
| airline          | Airline name                        |
| flight           | Flight number                       |
| source_city      | Source city of the flight           |
| departure_time   | Departure time (Morning, Evening, etc.) |
| stops            | Number of stops                     |
| arrival_time     | Arrival time                        |
| destination_city | Destination city                    |
| class            | Flight class (Economy, Business)   |
| duration         | Flight duration (hours)             |
| days_left        | Days left until the flight          |
| price            | Ticket price (INR)                  |

---

## 🛠️ Technologies Used
- **Python 3.x**
- **Pandas** – Data reading and cleaning
- **Matplotlib & Seaborn** – Visualization and plotting
- **Jupyter Notebook** – Writing code and presenting analysis

---

## 📈 Analysis and Visualization
- Price distribution and average prices by airline
- Price comparison by departure time
- Impact of stops on ticket price
- Correlation between flight duration and price

The graphs are interactive and user-friendly, with results useful for business decisions.

---

## 💾 Loading and Using the Dataset
The DataFrame used in the project is saved along with the `.ipynb` notebook in **CSV or Excel** format.

# To create an Excel file
df.to_excel('airline_data.xlsx', index=False)

# To create a CSV file
df.to_csv('airline_data.csv', index=False)
"""
