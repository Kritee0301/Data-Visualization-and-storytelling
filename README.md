#  Task 2: Data Visualization and Storytelling  

## Task Overview  
This task focuses on **data visualization and storytelling** using the *Superstore Sales Dataset*.  
The dataset contains customer order records, including order and ship details, customer segments, product categories, regions, and sales amounts.  

The objective is to explore sales performance and shipping efficiency through visual insights, demonstrating skills in **data cleaning, analysis, and visualization** using Python (Pandas, Matplotlib, Seaborn).  

##  Dataset Description  
The dataset represents customer order records of a retail superstore.  
It includes:  
- **Order Information** → Order ID, Order Date, Ship Date, Ship Mode  
- **Customer Information** → Customer ID, Segment, Region, City, State  
- **Product Information** → Category, Sub-Category, Product Name  
- **Transaction Information** → Sales  

Each row corresponds to a single product order.  

## Tools & Libraries Used  
- **Python 3.13.2**  
- **Pandas** → Data cleaning & preparation  
- **Matplotlib** → Basic charts  
- **Seaborn** → Advanced visualizations  

## Data Cleaning & Preparation  
Steps performed before visualization:  
- Removed null values (Postal Code)  
- Checked and confirmed no duplicate rows  
- Converted `Order Date` and `Ship Date` to datetime format  
- Derived new columns for analysis:  
  - **Order Year** (to study trends)  
  - **Shipping Delay** (Ship Date – Order Date)  

## Visualizations & Insights  

### [1] Sales by Region (Pie + Bar Chart)  
- **Insight:** West region has the highest sales, South contributes the least.  

### [2] Category vs Sales (Bar Chart)  
- **Insight:** Technology leads in sales, followed by Furniture, while Office Supplies lags behind.  

### [3] Sales Trend Over Years (Line Chart)  
- **Insight:** Sales dipped around 2015–2016 but showed strong growth after 2017.  

### [4] Top 10 Sub-Categories by Sales (Horizontal Bar Chart)  
- **Insight:** Phones and Chairs dominate the top-selling sub-categories.  

### [5] Shipping Delay Analysis (Bar + Line)  
- **Insight:** Same Day shipping has the lowest delay, while Standard Class is slowest.  
- **Insight:** South region experiences the longest delays.  

## Conclusion & Recommendations  
- **Technology and Phones** are the strongest revenue drivers.  
- **Office Supplies** needs better marketing and promotions.  
- **South region logistics** should be improved to reduce delays.  
- Encourage **faster shipping modes** to enhance customer satisfaction.  


## 📎 Project Deliverables  
- **Jupyter Notebook** → Data cleaning, analysis, and visualizations  
- **PowerPoint Presentation** → Dashboard of results and insights  
- **README Documentation** 

## 🙌 Acknowledgement  
Dataset Source: *Kaggle – Superstore Sales Dataset*  
Prepared by: Kritee 
