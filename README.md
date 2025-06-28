# call_centre_dashboard
A comprehensive and interactive Excel dashboard designed to analyze call center performance metrics — including call volumes, durations, customer satisfaction, and representative efficiency. Built for quick insights and decision-making using pivot tables and Excel formulas.


## Purpose

The Call Center Performance Dashboard is built to visualize and interpret daily operations and customer interaction data from a service center. It provides summarized insights into call volume trends, agent performance, customer satisfaction ratings, and more. This tool helps operations managers, quality analysts, and business stakeholders monitor performance and identify improvement areas.


## Tech Stack

The dashboard was built using the following tools and technologies:

- 📊 **Microsoft Excel 2016** – Core platform for dashboard design and data analysis
- 🧮 **Pivot Tables** – Used to summarize and aggregate call and customer data
- 📎 **COUNTIFS, IF, VLOOKUP** – Excel formulas used for filtering, categorization, and logic-based data handling
- 🎨 **Conditional Formatting** – To visually highlight performance metrics and outliers
- 📄 **.xlsx File Format** – Excel workbook format for data and dashboard layout

## Data Source

- **Source**: Internal Call Center Operations Dataset (Sample)
- **Structure**: 
  - Over 1000 call records
  - Fields include: Call ID, Customer ID, Duration, Representative, Call Date, Purchase Amount, Satisfaction Rating, Fiscal Year, and Customer Demographics
  - Additional computed fields like Duration Buckets and Rating Rounding for enhanced analysis

---

### 🔍 Business Problem
Operations teams need a reliable and visually intuitive tool to monitor call center performance, identify trends, and evaluate agent efficiency and customer experience.

### 🎯 Goal of the Dashboard
To create a self-service, easy-to-read dashboard in Excel that:
- Tracks key call metrics (count, duration, ratings)
- Highlights top-performing representatives
- Flags low-satisfaction calls and spikes in duration
- Supports data-driven decisions and performance reviews

### 👁️ Walkthrough of Key Visuals

- **Top Metrics Panel (Pivot Table)**  
  Displays total calls, total duration, total amount, average satisfaction rating, and number of 5-star ratings.

- **Representative Summary**  
  Agent-wise breakdown of performance including average rating and call durations.

- **Customer Insights**  
  Demographic data such as age, gender, and city, helping understand caller profiles.

- **Duration Buckets**  
  Categorization of calls into time ranges (e.g., 0–1 hour, 1–2 hours) to track handling efficiency.

- **Satisfaction Distribution**  
  Rounded ratings and frequency to highlight overall customer sentiment.

### 💡 Business Impact & Insights

- **Performance Monitoring**: Supervisors can quickly identify top and bottom performers.
- **Customer Experience Optimization**: Highlights customers who had long call durations or poor satisfaction for follow-up.
- **Data-Driven Coaching**: Supports targeted coaching sessions based on real-time metrics.
- **Resource Planning**: Helps predict agent requirements based on peak call hours and volume patterns.


## 📁 File Details

- **Filename**: `Call_Center_Dashboard.xlsx`
- **Sheets Included**:
  - `Data`: Raw call logs and customer info
  - `pivots`: Pivot tables summarizing performance metrics
  - `Customer Sender Report`: Printable call summary format
  - `Assets`: Mapping of representative IDs (future use)
 
## Screenshot: https://github.com/GunjanSaini07/call_centre_dashboard/blob/main/Snapshot%20of%20dashboard.png


