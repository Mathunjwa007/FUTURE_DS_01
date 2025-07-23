# 📊 E-commerce Sales Dashboard – Power BI Project

This project showcases an interactive sales dashboard built using Power BI and Excel, analyzing real-world e-commerce data from a UK-based retailer. It was completed as part of an internship with **Future Interns**, to extract meaningful insights from over 500,000 transaction records.

---

## 🔍 Project Objectives

- Identify **best-selling products** based on sales and quantity.
- Analyze **monthly and seasonal sales trends**.
- Determine which **countries generate the most revenue**.
- Create an **interactive dashboard** to support business decision-making.

---

## 🛠 Tools & Technologies

- **Power BI Desktop** – Dashboard creation & DAX calculations  
- **Microsoft Excel** – Initial data cleaning and formatting  
- **DAX** – For KPIs and calculated columns  
- *(Optional)* SQL – For advanced data querying  

---

## 📁 Dataset

- Source: [Kaggle – UK E-commerce Data](https://www.kaggle.com/datasets/carrie1/ecommerce-data)
- Description: Includes over 500K online retail transactions between 2010–2011 from a UK-based store. Fields include `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`, and `Country`.

---

## ⚙️ Data Cleaning Process

- Removed rows with missing or null values (especially `CustomerID`)
- Filtered out canceled orders (Invoice numbers starting with “C”)
- Removed records with negative quantities or prices
- Created new fields for `Year`, `Month`, `Sales = Quantity × UnitPrice`

---

## 📈 Dashboard Features

- **KPI Cards**: Total Sales, Total Orders, Average Order Value  
- **Bar Charts**: Top-selling products by sales and quantity  
- **Line Chart**: Monthly sales trend over time  
- **Donut Chart**: Country-wise revenue breakdown  
- **Slicers**: Filter by year, country, or product  

---

## 💡 Key Insights

- Sales peak during **November and December**, aligning with the holiday season  
- **UK** contributes the highest revenue among all countries  
- Most popular product: *“White Hanging Heart T-Light Holder”*

---

## 📷 Screenshots

*(<img width="1920" height="1079" alt="Future_DS_01" src="https://github.com/user-attachments/assets/d3d2c2fb-b2ba-4f84-b5b5-d03af3d0ed2e" />)*

---

## 🧠 Skills Practiced

- Data wrangling and transformation  
- Time series and trend analysis  
- DAX for KPI creation  
- Data storytelling with interactive visuals  

---

## ✅ Status

✔️ Completed – Ready to showcase  
📄 Report & visuals available in this repo

---

## 📬 Contact

**Mzwakhe Mathunjwa**  
[LinkedIn](https://www.linkedin.com/in/your-profile) | [Portfolio](https://sites.google.com/view/datascienceentrylevel/home)

---

## 📌 Acknowledgments

- **Future Interns** – for the opportunity and mentorship  
- Kaggle – for providing the dataset  
- YouTube: [Power BI Dashboard Tutorial](https://www.youtube.com/watch?v=AGrl-H87pRU) – for learning resources





