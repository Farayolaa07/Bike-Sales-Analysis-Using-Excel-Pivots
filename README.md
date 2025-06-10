# Bike-Sales-Analysis-Using-Excel-Pivots
# 🚲 Bike Sales Analytics Dataset

This repository contains a structured Excel dataset designed for business intelligence, pivot table analysis, and data visualization. The dataset includes customer demographics, product details, sales figures, and summarized financial metrics over multiple years.

## 📦 Dataset Contents

The Excel file contains **4 sheets**, each offering unique insights:

### 1. `Sales Data`
This is the core transactional dataset, with detailed records of bike product sales.

**Key Fields:**
- **Date, Day, Month, Year** – Temporal dimensions for each sale
- **Customer_Age, Age_Group, Customer_Gender** – Demographics
- **Country, State** – Geographic details
- **Product_Category, Sub_Category, Product** – Product hierarchy
- **Order_Quantity, Unit_Cost, Unit_Price** – Order metrics
- **Cost, Revenue, Profit** – Financial outcomes

Example:
Date	Age_Group	Country	Product	Revenue
2017-01-01	Youth (<25)	Canada	Road-250 Red, 44	4886
2017-01-01	Adults (35-64)	United States	Road-550-W Yellow,38	2240

yaml
Copy
Edit

---

### 2. `Revenue and Profit by Year`
A summary sheet displaying total **annual revenue** and **profit** over multiple years.

| Year | Annual Profit | Annual Revenue |
|------|---------------|----------------|
| 2017 | $4,065,680    | $10,289,670    |
| 2018 | $7,747,551    | $17,028,380    |
| 2019 | $7,417,353    | $15,705,990    |
![image](https://github.com/user-attachments/assets/2017655e-698e-41d9-806b-49587ffc9cc6)


---

### 3. `Product Revenue by Country`
A pivot table summarizing **revenue contribution** by **country** and **product category**:

| Country   | Accessories | Bikes     | Clothing | Grand Total |
|-----------|-------------|-----------|----------|-------------|
| Australia | $3,284,787  | $20,231,486 | $1,911,313 | $25,427,586 |
| Canada    | $2,305,298  | $4,317,696  | $1,391,542 | $8,014,536  |
![image](https://github.com/user-attachments/assets/a78a2c35-0070-4bf5-8e9d-f9f42a1b2b61)


---

### 4. `Revenue by Age Group`
Displays each **age group’s share of total revenue**:

| Age Group            | Revenue Share |
|----------------------|----------------|
| Adults (35-64)       | 49.7%          |
| Young Adults (25-34) | 36.0%          |
| Seniors (64+)        | 0.36%          |
![image](https://github.com/user-attachments/assets/b8b9476b-7071-47ec-ac38-5d4809c461c0)


---

## 🧰 Usage

This dataset is perfect for:
- Practicing pivot table creation and summarization in Excel
- Exploratory data analysis (EDA)
- Building dashboards with Power BI, Tableau, or Python
- Studying customer demographics and product performance trends

> The dataset was analyzed primarily using **Excel pivot tables**, allowing clear insights into revenue distribution, profit margins, and product demand by market and demographic.

---

## 📄 License

This dataset is shared for **educational and non-commercial** use. Please provide attribution if reused in public projects.

---

**Explore. Analyze. Visualize.**
