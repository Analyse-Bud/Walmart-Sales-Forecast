# Walmart-Sales-Forecast
This project presents a comprehensive sales revenue forecasting solution using historical Walmart data. Built entirely in Excel, it includes time series forecasting logic, interactive calendar visualization, trend dashboards, and sales performance analysis by state and customer group.
| Sheet Name              | Description |
|-------------------------|-------------|
| **Raw Sales Data**      | Original transaction-level data for all states |
| **Monthly Forecast**    | Clean daily forecast with calendar-compatible structure |
| **Excel forecast sheet**| ARIMA-style forecast using lag logic, LINEST regression, and error tracking |
| **Sales overview**      | Dashboard with visual summaries of top states, customer types, and sales channels |
| **Trend analysis**      | Graphs showing revenue growth over time, top-performing segments, and sales distribution |
| **Pivots**              | Support table for dynamic calendar lookup and summaries |
| **2018 Forecast Summary** | High-level forecast overview for the year |
| **State details**       | Drill-down sales performance by U.S. state |
| **State distribution**  | Visual comparison of state-wise sales revenue and contribution |
| **Data**                | Supporting calculations or transformed input |
| **Sheet6**              | Reserved/temporary worksheet (not used)

---

## 🧠 Forecasting Approach

### ✅ Step 1: Data Aggregation
- Daily sales data transformed into weekly totals
- Cleaned for time series use and aligned with date dimensions

### ✅ Step 2: Manual ARIMA-style Modeling
- Applied **lag regression** (AR(1)) to simulate an autoregressive model
- Used Excel’s `LINEST()` to derive slope (β) and intercept (α)
- Included first differencing and error analysis for time series stability

### ✅ Step 3: Calendar Forecast Visualization
- Dynamic Excel calendar auto-generates based on selected month/year
- Forecasted daily revenue values appear in calendar grid via `XLOOKUP`
- Includes conditional formatting and flexible input logic

---

## 📊 Sales & Trend Analysis (Dashboards)

### 🔹 Sales Overview
- Summary dashboard of total revenue, segment performance, and comparison by:
  - **Customer type**
  - **Sales channel**
  - **Region**

### 🔹 Trend Analysis
- Time-based graphs of revenue growth
- Highest revenue periods identified
- Seasonality and performance trends highlighted - USA holidays also collected to identify any impact they might have

---

## ⚙️ Excel Features Used

- `DATE`, `EOMONTH`, `WEEKDAY`, `INT`, `IF`, `XLOOKUP`, `TEXT`
- `LINEST`, `SLOPE`, `INTERCEPT`, `FORECAST.LINEAR`
- PivotTables, named ranges, dynamic formula referencing
- Conditional formatting and dropdown inputs

---

## 📈 Skills Demonstrated

- Time series forecasting in Excel
- ARIMA-style modeling using regression
- Holt Winter's forecasting method
- Automated model creation
- Calendar logic and date computation
- Dashboard design and executive reporting
- Data aggregation, transformation and visualization

---

## 🎯 Use Cases

- Retail demand planning
- Calendar-based business performance tracking
- Operational alignment for promotions and staffing
- Executive reporting and scenario planning

---

## 🚀 Future Enhancements

- Holt-Winters smoothing (α, β, γ tuning)
- Python or Power BI integration for dynamic dashboards
- KPI-based alerts for threshold sales or revenue dips

---

## 👨‍💼 About Me

I’m a workforce and data analyst with a passion for turning raw business data into insights. This Excel project showcases my ability to apply analytical thinking, forecast business performance, and design intuitive dashboards with real-world applications.

📫 Connect with me on [LinkedIn]www.linkedin.com/in/budlelwane-ntloko-43b08ab3

---

## 🔒 License

MIT License — free to use with attribution.
