# single_amazon_laptop_messy_dataset

## 🎯 Objective

The main objective of this project is to **clean, preprocess, and analyze a messy Amazon laptop dataset** to convert raw and inconsistent product data into a structured and analysis-ready dataset.

The project aims to:

* Identify and handle **missing values**.
* Remove **unnecessary columns and duplicate records**.
* Clean inconsistent data such as **price, MRP, offers, RAM, storage, and screen size**.
* Convert columns into appropriate **data types**.
* Standardize product specifications for accurate analysis.
* Perform **Exploratory Data Analysis (EDA)** to understand laptop prices, ratings, brands, specifications, and offers.
* Generate meaningful **business insights** from the cleaned dataset.
* Prepare the dataset for further **data visualization and dashboard development**.



  ## 🛠️ Requirements

This project was completed using **Microsoft Excel** for data cleaning, preprocessing, analysis, and visualization.

### Software Requirements

* Microsoft Excel 2016 or above
* Microsoft Excel 365 recommended

### Excel Features Used

* Data Cleaning
* Remove Duplicates
* Remove Blank Rows
* Find & Replace
* Text to Columns
* Data Formatting
* Data Validation
* Sorting & Filtering
* Excel Formulas
* Pivot Tables
* Pivot Charts
* Conditional Formatting
* Data Visualization
* Dashboard Creation

### Dataset Requirement

The project uses the following dataset:

```text
single_amazon_laptop_messy_dataset_1-10 (1).csv
```

The dataset contains Amazon laptop information such as:

* Product Name
* Brand
* Rating
* Price
* MRP
* Offers
* RAM
* Storage
* Processor
* Operating System
* Graphics Card
* Screen Size
* Product Details
## 🧹 Step 1: Data Cleaning

The first step of the project was to clean the raw Amazon laptop dataset in **Microsoft Excel**.

The original dataset contained messy, inconsistent, and incomplete data. Data cleaning was performed to make the dataset accurate, consistent, and ready for further analysis.

### Cleaning Operations Performed

1. **Removed unnecessary columns**

   * Removed columns that were not required for analysis.

2. **Removed blank rows**

   * Identified and removed completely blank rows from the dataset.

3. **Handled missing values**

   * Checked the dataset for blank/missing values.
   * Handled missing data where required.

4. **Removed duplicate records**

   * Used Excel's **Remove Duplicates** feature.
   * Ensured that duplicate laptop records were removed.

5. **Cleaned Price and MRP**

   * Removed unnecessary symbols and formatting.
   * Converted price-related values into a consistent format.

6. **Cleaned Offer/Discount**

   * Standardized discount values.
   * Removed unnecessary `%` symbols where required.

7. **Standardized Product Information**

   * Cleaned and standardized fields such as:

     * Brand
     * Model Name
     * RAM
     * Storage
     * Processor
     * Operating System
     * Screen Size

8. **Corrected Data Formatting**

   * Applied consistent formatting to columns.
   * Ensured that numerical and text values were stored correctly.

### Tools Used

* Microsoft Excel
* Filter
* Sort
* Find & Replace
* Remove Duplicates
* Text to Columns
* Excel Formatting

### Result

After completing the cleaning process, the dataset became **more structured, consistent, and suitable for analysis and dashboard creation**.
<img width="1905" height="650" alt="Screenshot 2026-08-20 065328" src="https://github.com/user-attachments/assets/4dfeae11-a5c3-4bb5-af96-8b72b9d8f07a" />




## 🧮 Step 2: Data Calculation

After cleaning the dataset, the next step was to perform **calculations on the cleaned data using Microsoft Excel**.

The calculations were performed to generate useful numerical information and prepare the dataset for further analysis.

### Calculations Performed

1. **Total Number of Products**
   - Calculated the total number of laptop products available in the dataset.
   - **Total Laptops: 61**

2. **Average Price**
   - Calculated the average selling price of laptops.
   - **Average Price: ₹46,849**

3. **Average Rating**
   - Calculated the average customer rating of laptops.
   - **Average Rating: 3.92**

4. **Brand-wise Average Price and Count**
   - Calculated the average price for each laptop brand.
   - Calculated the number of laptops available for each brand.

5. **RAM Analysis**
   - Calculated the number of laptops available for different RAM configurations.
   - Analyzed RAM categories such as 4 GB, 6 GB, 8 GB, 12 GB, 16 GB, and 24 GB.

6. **Price Statistical Analysis**
   - Calculated important statistical values for laptop prices:
   - **Minimum Price: ₹14,990**
   - **Q1 (First Quartile): ₹32,870**
   - **Q3 (Third Quartile): ₹56,501**
   - **Maximum Price: ₹1,03,990**

### Excel Functions Used

The following Excel functions were used for calculations:

```text
COUNT()
AVERAGE()
MIN()
MAX()
QUARTILE()
COUNTIF()

<img width="1541" height="222" alt="Screenshot 2026-08-20 065845" src="https://github.com/user-attachments/assets/442e6503-4f16-41ef-92cd-5ee76d43e39e" />



## 📊 Step 3: Dashboard Creation

After completing the data cleaning and calculation process, an interactive **Laptop Sales Dashboard** was created using **Microsoft Excel**.

The dashboard was designed to present the key information and analysis of the Amazon laptop dataset in a simple and visual format.

### Dashboard Components

The dashboard contains the following key performance indicators (KPIs):

- **Total Laptops:** 61
- **Average Price:** ₹46,849
- **Average Rating:** 3.92

### Dashboard Visualizations

The following charts were created in the dashboard:

- **Price Distribution**
  - Used a scatter chart to show the distribution of laptop prices across different products.

- **Average Price by Brand**
  - Used a column chart to compare the average laptop price across different brands.

- **Laptops by RAM Size**
  - Used a bar chart to show the number of laptops available for different RAM configurations.

### Excel Features Used

- Excel Charts
- Scatter Chart
- Column Chart
- Bar Chart
- KPI Cards
- Data Formatting
- Pivot Table Data
- Dashboard Layout

### Dashboard Objective

The main objective of the dashboard was to provide a **clear visual overview of laptop sales data** and make it easier to understand:

- Total number of laptops
- Average laptop price
- Average customer rating
- Price distribution
- Brand-wise average price
- RAM-wise laptop distribution

### Result

The final **Laptop Sales Dashboard** provides a simple and effective visual representation of the Amazon laptop dataset. It helps users quickly understand the **pricing, ratings, brand performance, and RAM distribution** of laptops.
<img width="1121" height="687" alt="Screenshot 2026-08-20 070357" src="https://github.com/user-attachments/assets/f8c9f103-73cd-42c7-86a8-011405d63a12" />
