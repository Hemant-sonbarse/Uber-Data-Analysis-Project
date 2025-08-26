# 🚖 Uber Ride Data Analysis  

## 📌 Project Overview  
This project analyzes Uber ride-booking data to uncover operational inefficiencies, customer behavior patterns, and revenue opportunities. Using Python and data visualization, the goal is to provide actionable insights into **cancellations, turnaround times, service quality, and revenue efficiency**.  

---

## 📂 Dataset  

The dataset contains **150,000 Uber ride bookings** with the following attributes:  

1. **Date** – Ride booking date  
2. **Time** – Ride booking time  
3. **Booking ID** – Unique identifier for each ride  
4. **Booking Status** – Status of ride (Completed, Cancelled, Incomplete, No Driver Found)  
5. **Customer ID** – Unique identifier for each customer  
6. **Vehicle Type** – Type of vehicle (Bike, Auto, Sedan, XL, eBike, etc.)  
7. **Pickup Location** – Starting point of ride  
8. **Drop Location** – Ending point of ride  
9. **Avg VTAT (Vehicle Turnaround Time)** – Average time for driver to reach customer  
10. **Avg CTAT (Customer Turnaround Time)** – Average ride duration  
11. **Cancelled Rides by Customer** – Flag/count if customer cancelled  
12. **Reason for Cancelling by Customer** – Stated reason (e.g., long wait, change of plan)  
13. **Cancelled Rides by Driver** – Flag/count if driver cancelled  
14. **Driver Cancellation Reason** – Reason provided (e.g., long pickup distance, personal reason)  
15. **Incomplete Rides** – Flag/count if ride ended prematurely  
16. **Incomplete Rides Reason** – Reason (e.g., vehicle breakdown, traffic issues)  
17. **Booking Value** – Total fare charged for the ride  
18. **Ride Distance** – Distance of ride (in km)  
19. **Driver Ratings** – Rating given by customer to driver (out of 5)  
20. **Customer Rating** – Rating given by driver to customer (out of 5)  
21. **Payment Method** – Mode of payment (UPI, Card, Wallet, Cash, etc.)  

---

## 🛠 Tools & Libraries Used  
- **Python** – Core programming language  
- **Pandas** – Data manipulation & analysis  
- **NumPy** – Numerical operations  
- **Matplotlib / Seaborn** – Data visualization  

---

## 📊 Analysis Steps  
1. **Data Cleaning**  
   - Handled missing values and duplicates  
   - Converted date-time columns into proper format  
   - Created binary flags for cancellations & incompletions  

2. **Exploratory Data Analysis (EDA)**  
   - **Demand Patterns:** Hourly, daily, and location-based booking trends  
   - **Cancellations & Incomplete Rides:** Frequency, reasons, and revenue impact  
   - **Operational Efficiency:** VTAT & CTAT distributions across vehicle types  
   - **Service Quality:** Analysis of customer & driver ratings  
   - **Revenue Insights:** Revenue by vehicle type, payment method, and fare per km  

---

## 🔑 Key Insights  
- **Cancellations:** Driver cancellations (27k) were 2x higher than customer cancellations (10.5k), indicating supply-side reliability issues.  
- **Revenue Loss:** Incomplete rides caused **₹4.6M+ in lost revenue**, the biggest leakage point.  
- **Operational Efficiency:** Avg. VTAT = 8.5 mins, Avg. CTAT = 29 mins → optimization needed.  
- **Service Quality:** Drivers rated **4.23** on average vs. customers **4.40**, showing service consistency gaps.  
- **Demand Trends:** Peak rides during **rush hours & weekends**, with specific pickup/drop hotspots.  
- **Revenue Mix:** Sedans generated the most revenue; digital payments (UPI, cards, wallets) dominated transactions.  

---

## ✅ Conclusion  
The analysis highlights opportunities for Uber to:  
- Reduce cancellations by improving driver engagement & allocation  
- Shorten CTAT to boost customer satisfaction  
- Address incomplete rides to recover lost revenue  
- Leverage digital payments & demand hotspots for growth  

---

## 🚀 Future Work  
- Build **predictive models** for demand forecasting  
- Develop **customer segmentation** for targeted promotions  
- Assess the impact of ratings on **customer retention**  
- Explore **payment incentives** to improve ride completion rates  
