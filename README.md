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




## 🔎 Step 4: Lookup Analysis

In this step, **Lookup functions in Microsoft Excel** were used to retrieve specific laptop information and perform brand-wise analysis.

The main purpose of Lookup Analysis was to quickly search for a laptop model or brand and retrieve its related product details.

### Lookup Operations Performed

- Used **VLOOKUP** to retrieve the price of a selected laptop model.
- Used **XLOOKUP** to retrieve the rating of a selected laptop model.
- Used a **Search Brand** field to retrieve specific laptop details.
- Retrieved **RAM** information for the selected brand.
- Retrieved **Operating System (OS)** information.
- Retrieved **Screen Size** information.
- Retrieved **Hard Disk Size** information.
- Retrieved **CPU Model** information.
- Calculated **Average Price** for each brand.
- Calculated **Total Laptops** available for each brand.
- Calculated **Average Rating** for each brand.
- Analyzed **Total Ratings** for different brands.
- Created a **Brand Metrics** chart to visually compare brand performance.

### Excel Functions Used

The following Excel Lookup and calculation functions were used:

VLOOKUP()
XLOOKUP()
AVERAGE()
COUNT()

### Example Calculations

**VLOOKUP – Retrieve Price:**

=VLOOKUP(Model_Name,Table_Range,Column_Number,FALSE)

**XLOOKUP – Retrieve Rating:**

=XLOOKUP(Model_Name,Model_Range,Rating_Range)

**Average Price by Brand:**

=AVERAGE(Price_Range)

**Total Laptops by Brand:**

=COUNTIF(Brand_Range,Brand_Name)

### Brand-wise Analysis

The Lookup Analysis also provided brand-wise metrics such as:

- Average Price
- Total Number of Laptops
- Average Rating
- Total Ratings

This helped to compare different laptop brands based on their pricing, availability, and customer ratings.

### Product Information Retrieved

For the selected brand/model, the following product information was retrieved:

- Price
- Rating
- RAM
- Operating System
- Screen Size
- Hard Disk Size
- CPU Model

### Objective

The objective of Lookup Analysis was to make it easier to **search, retrieve, compare, and analyze laptop information based on model and brand**.

### Result

The Lookup Analysis successfully provided quick access to important laptop details and helped in performing **brand-wise comparison and analysis**. It made the dataset easier to explore and supported better understanding of **price, rating, RAM, operating system, screen size, storage, and CPU information**



<img width="1656" height="746" alt="Screenshot 2026-08-20 071054" src="https://github.com/user-attachments/assets/c06a0f17-4fd3-4081-8b70-225e399bc5eb" />




## ⚠️ Step 5: Data Validation & Error Log

In this step, a **Data Validation & Cleaning Summary** was created in Microsoft Excel to check and track the quality of the cleaned Amazon laptop dataset.

The Error Log was used to document the data quality checks, target columns, actions taken, and current status of each validation process.

### Data Quality Checks Performed

1. **Missing Price Validation**
   - Target Column: `price`
   - Action Taken: Automated tracking via Error_Log tab.
   - Current Status: **No errors found (100% complete).**

2. **Missing Rating Validation**
   - Target Column: `rating`
   - Action Taken: Automated tracking via Error_Log tab.
   - Current Status: **No errors found (100% complete).**

3. **Blank Value Removal**
   - Target Column: `next_month_bought`
   - Action Taken: Filtered and removed rows with missing data.
   - Current Status: **Cleaned.**

4. **Duplicate Row Removal**
   - Target Column: All Columns
   - Action Taken: Scanned and removed duplicate entries.
   - Current Status: **Cleaned.**

5. **Text Standardization**
   - Target Columns: `brand`, `model_name`
   - Action Taken: Removed extra spaces and standardized case.
   - Current Status: **Cleaned.**

6. **Data Type Formatting**
   - Target Columns: `price`, `mrp`
   - Action Taken: Converted to numeric currency formats.
   - Current Status: **Cleaned.**

### Error Log Purpose

The Error Log was created to:

- Track data quality issues.
- Identify missing values.
- Monitor the cleaning process.
- Record the actions taken for each issue.
- Verify the current status of data quality checks.

### Objective

The objective of the Error Log was to **systematically track data validation and cleaning activities** and ensure that the dataset was accurate, consistent, and ready for further analysis.

### Result

The Data Validation and Error Log process confirmed that the required data-quality checks were completed successfully. Missing price and rating validations showed **100% completeness**, while blank values, duplicate records, text formatting, and data type formatting were successfully cleaned.


<img width="1754" height="316" alt="Screenshot 2026-08-20 071653" src="https://github.com/user-attachments/assets/75bffdbe-cf43-42e9-b217-89056d159ef5" />




### 🎯 Project Result

The **Amazon Laptop Data Cleaning and Analysis Project** was successfully completed using **Microsoft Excel**.

The messy Amazon laptop dataset was cleaned, validated, analyzed, and transformed into a structured and analysis-ready dataset.

* **61 laptop products** were analyzed.
* **Average laptop price:** ₹46,849
* **Average customer rating:** 3.92
* Missing price and rating validations showed **100% completeness**.
* Blank values were identified and cleaned.
* Duplicate records were checked and removed.
* Brand and model names were standardized.
* Price and MRP were converted into proper numeric currency formats.
* Brand-wise price, laptop count, and rating analysis was performed.
* RAM-wise laptop distribution was analyzed.
* Lookup Analysis was performed using **VLOOKUP and XLOOKUP**.
* An interactive **Laptop Sales Dashboard** was created.
* Price Distribution, Average Price by Brand, and RAM-wise analysis were visualized using Excel charts.
* An **Error Log** was created to track data validation and cleaning activities.

**Final Outcome:**
The project successfully converted messy Amazon laptop data into a **clean, validated, structured, and analysis-ready dataset**, along with an interactive Excel dashboard that provides useful insights for laptop price, brand, rating, and specification analysis.




##🔚 Conclusion

The Amazon Laptop Data Cleaning and Analysis Project was successfully completed using Microsoft Excel. The raw and messy dataset was cleaned, validated, standardized, and transformed into a structured format suitable for analysis.

Various Excel techniques such as data cleaning, calculations, Lookup functions, data validation, error tracking, Pivot Tables, and charts were used throughout the project. An interactive Laptop Sales Dashboard was also created to present important insights related to laptop prices, ratings, brands, and RAM configurations.

Overall, this project provided practical experience in Excel-based data cleaning, data analysis, data visualization, and dashboard creation, and demonstrated how raw data can be transformed into meaningful and useful business insights.
