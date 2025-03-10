# Namma Yatri - Analytics Dashboard

## Introduction

**Namma Yatri** is an open-network mobility application designed to provide multi-modal services to commuters without involving any middlemen. Built on the **Beckn protocol** (open source) and following the **ONDC** network standards, this app ensures interoperability with any buyer app compliant with the network standards for offering rides.

🔗 **Website Link:** [Namma Yatri](https://www.nammayatri.in/open?cc=)

The platform provides **open data analytics** showcasing key insights such as completed trips, earnings, driver statistics, conversion rates, and more—categorized based on **location** and **duration**.

---

## Problem Statement

I aimed to explore and understand how **Namma Yatri** collects real-time data of customers, drivers, completed trips, and other essential metrics through their app. My objective was to analyze this data and recreate a **dynamic dashboard** similar to the one displayed on their website.

### Key Data Points Observed:
- Number of clicks for customers searching for trips.
- Location searches performed by customers.
- Clicks per customer evaluating their search results.
- Clicks per customer who viewed the ride fare.
- Clicks per customer who opted for a ride after seeing the fare.
- Clicks per customer who were allocated a ride.
- Distance data for each ride.
- Clicks per customer who successfully completed their ride.

---

## My Work

### **1. Data Collection & SQL Analysis**
- I examined the publicly available data from their website and mobile app.
- Using this information, I **created a sample dataset for a single day**.
- The dataset is available in my SQL report:
  
  📂 **SQL Report:** [Data_Entry.sql](https://github.com/SinghHarsh2003/Namma-Yatri-Analysis/blob/main/SQL%20Files/Data_Entry.sql)

### **2. Database Design & Schema Structure**
- Built a **MySQL database** to simulate how the company might collect and store real-time data for **each customer and driver**.

### **3. Data Analysis & KPI Extraction**
- Analyzed the collected data to extract **key performance indicators (KPIs)** and identify trends.
- The analysis is available in the SQL report:
  
  📂 **SQL Report:** [Data_Entry.sql](https://github.com/SinghHarsh2003/Namma-Yatri-Analysis/blob/main/SQL%20Files/Data_Entry.sql)

### **4. Interactive Tableau Dashboard**
- Created a **dynamic and interactive Tableau Dashboard** to visualize the analyzed data.
- The dashboard replicates **similar insights** shown on their official website.

---

## **Overall Analytics Report**

![Analytics Report](https://github.com/SinghHarsh2003/Namma-Yatri-Analysis/blob/main/Imp%20images/%231.png)

---

## **Trip Details Report**

![Trip Details](https://github.com/SinghHarsh2003/Namma-Yatri-Analysis/blob/main/Imp%20gifs/Part-1.gif)

---

## **Data Model**

![Data Model](https://github.com/SinghHarsh2003/Namma-Yatri-Analysis/blob/main/Imp%20gifs/Part-1.gif)

---

## Conclusion
This project provides an in-depth analysis of **how Namma Yatri collects and visualizes data** for ride bookings, driver activity, and customer interactions. The structured **SQL analysis** and **Tableau dashboard** offer a better understanding of their data-driven operations.

📌 **Next Steps:** Further refining the **Tableau dashboard** with real-time integration and exploring **predictive analytics** for customer behavior insights.

📩 *For any queries or collaborations, feel free to connect!* 🚀

