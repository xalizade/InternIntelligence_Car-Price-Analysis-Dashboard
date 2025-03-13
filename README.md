# InternIntelligence_Car-Price-Analysis-Dashboard 🚗


## 📌 Overview  
This project is an **interactive Car Price Analysis Dashboard** built with **Power BI** to analyze car prices based on various factors like **mileage, brand, fuel type, and transmission**. The dashboard provides key insights into car pricing trends, resale value, and cost efficiency.  

## 🎯 Features  
✅ **Key Metrics & Insights**:  
- Average Car Price & Mileage  
- Most Expensive & Popular Car Brands  
- Price Distribution & Trends  

✅ **Interactive Visualizations**:  
- **Bar Charts** for brand-wise price comparison  
- **Scatter Plots** for mileage vs. price & age vs. price  
- **Tables & Matrices** for best/worst value cars  

✅ **User-Friendly Filters**:  
- Brand, Year, Fuel Type, Transmission, and Mileage filters  
- Dynamic slicers for easy data exploration  

## 🛠️ Tech Stack  
- **Power BI** – Data visualization & interactive dashboard  
- **DAX (Data Analysis Expressions)** – Custom calculations & measures  
- **Excel/CSV/SQL** – Data sources  

## 📌 Setup Instructions  
1. **Download the dataset** (CSV, Excel, or SQL database).  
2. **Open Power BI** and load the dataset.  
3. **Clean & prepare the data** (remove duplicates, handle missing values).  
4. **Import the `.pbix` file** (Power BI project) or create a new report.  
5. **Apply the DAX formulas & measures** as per the visualizations.  
6. **Publish the report** to Power BI Service for sharing.  

## 📊 Dashboard Structure  

### 🔷 **Page 1: Overview Dashboard**  
🔹 **Key Metrics** (KPI Cards)  
✅ Average Car Price → `AVERAGE(Price)`  
✅ Average Mileage → `AVERAGE(Mileage)`  
✅ Most Expensive Brand (by Avg. Price)  
✅ Most Popular Brand (by Count of Cars)  

📌 **Visuals**: KPI Cards, Histogram, Box Plot, Clustered Bar Chart, Scatter Chart  

### 🔷 **Page 2: Price Analysis**  
🔹 **Impact of Car Age on Price**  
✅ Scatter Plot → `X: Car Age (2025 - Year), Y: Price, Color: Transmission Type`  

🔹 **Impact of Fuel Type on Price**  
✅ Column Chart → `X: Fuel Type, Y: Avg. Price`  

📌 **Visuals**: Scatter Chart, Column Chart  

### 🔷 **Page 3: Mileage & Cost Efficiency**  
🔹 **Price per Mileage Analysis**  
✅ Table/Matrix → `Brand, Model, Price per KM %`  
✅ Conditional Formatting (Green = Efficient, Red = Expensive)  

🔹 **Best & Worst Value Cars**  
✅ Top 5 Cheapest & Most Expensive Cars per KM  

📌 **Visuals**: Matrix Table, Tables  

### 🔷 **Page 4: Filters & Custom Insights**  
✅ **Slicers**:  
- Brand (Dropdown)  
- Year (Slider)  
- Fuel Type (Multi-Select)  
- Transmission Type (Dropdown)  
- Mileage Range (Slider)  

📌 **Visuals**: Dynamic slicers, interactive bar charts, filtered tables  

## 📈 Insights & Recommendations  
🔹 **Findings from the Data**  
- 🚀 Which brands have the highest resale value?  
- 🔋 Do electric/hybrid cars have higher prices than petrol/diesel?  
- ⛽ How does mileage impact car price?  

🔹 **Automated Reports**  
- Monthly or yearly car price trends  
- Best car models for resale value  

## 🚀 Next Steps  
- ✅ **Enhance DAX calculations** for more insights  
- ✅ **Integrate machine learning** for price prediction  
- ✅ **Deploy Power BI Report** to a web app  

---

## 🤝 Contributing  
Feel free to **fork** this repository, **raise issues**, or **submit pull requests** if you’d like to enhance the dashboard.  


