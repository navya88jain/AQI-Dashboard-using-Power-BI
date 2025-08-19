# Power BI Dashboard - Global AQI Analysis
A sample dataset is taken containing AQI Values for over 100 countries over four years and a dashboard is created to extract information and visualize it more clearly using Microsoft Power BI.
---

## Dashboard Preview

! [Screenshot of Dashboard] (Sample%20Screenshots/Screenshot%201.png)

---

## Project Structure

| Path                  | Description                                            |
|-----------------------|--------------------------------------------------------|
| `aqi.pbix`            | Main Power BI dashboard file                           |
| `Sample Screenshots/` | Screenshots of the dashboard                           |
| `data_date.csv`       | Sample dataset used                                    |

---

## Key Insights

-  **Highest and lowest AQI levels** for specific countries during a specific time 
-  **Trend of AQI over time** across different countries  
-  Distribution of **Air Quality Status categories** (Good / Moderate / Unhealthy / etc.)  
-  Identification of **periods with severe air pollution** and which countries were affected  

---

## How to Use

1. **Clone or Download** this repository  
2. Open `aqi.pbix` using **Power BI Desktop**  
3. If prompted, update the file path for the sample data (via **Transform Data → Data Source Settings**)  

---

## Sample Dataset

The file data_date.csv contains a sample dataset used to build this dashboard.  
Each row contains:

| Column Name | Description                                  |
|-------------|----------------------------------------------|
| `Date`      | Date of the AQI measurement                  |
| `Country`   | Country where AQI was measured               |
| `Status`    | Status category (Good, Moderate, Unhealthy…) |
| `AQI Value` | Air Quality Index value                      |
