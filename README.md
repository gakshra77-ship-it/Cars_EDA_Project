**# Cars_EDA_Project**# Used Cars Data Analysis – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on a Used Cars dataset obtained from Kaggle. The main objective is to understand the dataset, clean the data, identify patterns, analyze relationships between different features, and discover useful insights about used car prices.

## 🎯 Objectives
- Understand the structure and features of the dataset.
- Identify and handle missing values and duplicate records.
- Clean and preprocess the data for analysis.
- Perform descriptive statistical analysis.
- Explore relationships between car features and their prices.
- Visualize data using different charts and graphs.
- Identify trends, patterns, and important insights.

## 📂 Dataset Information
- **Dataset:** Used Cars Dataset
- **Source:** Kaggle
- **Initial Rows:** 7,253
- **Initial Columns:** 14

### Key Features
- Name – Name of the car
- Location – City where the car is listed
- Year – Manufacturing year
- Kilometers_Driven – Distance driven by the car
- Fuel_Type – Type of fuel used
- Transmission – Manual or Automatic
- Owner_Type – Number of previous owners
- Mileage – Fuel efficiency
- Engine – Engine capacity
- Power – Engine power
- Seats – Seating capacity
- Price – Listed price of the used car

## 🛠️ Tools and Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 🧹 Data Cleaning
The following data-cleaning steps were performed:
- Removed unnecessary columns.
- Checked and removed duplicate records.
- Handled missing values.
- Converted Mileage, Engine, and Power columns into numerical formats.
- Removed the New_Price column due to a high percentage of missing values.
- Handled invalid seating values.
- Filled missing numerical and categorical values using suitable methods.
- Identified unusually high kilometer readings for further investigation.

## 📊 Exploratory Data Analysis
The project includes different visualizations:
- Price distribution using a histogram.
- Number of cars by fuel type using a count plot.
- Average car price by transmission type.
- Price comparison across fuel types using a box plot.
- Relationship between manufacturing year and price.
- Relationship between kilometers driven and price.
- Correlation heatmap of numerical features.

## 💡 Key Insights
The analysis helps understand:
- Which fuel types are most common in the dataset.
- How transmission type relates to average car prices.
- How manufacturing year affects used car prices.
- How kilometers driven relates to car prices.
- The distribution and variation of used car prices.
- Relationships between numerical car features.

## 📁 Project Files
- `used_cars_data.csv` – Original dataset.
- `Used_Cars_EDA.ipynb` – Python notebook containing data cleaning, analysis, and visualizations.
- `Used_Cars_EDA_Report.pdf` – Final project report.

## ▶️ How to Run the Project
1. Clone or download this repository.
2. Open Google Colab or Jupyter Notebook.
3. Upload the dataset.
4. Open the `.ipynb` file.
5. Run all cells to reproduce the analysis and visualizations.

## 🏁 Conclusion
This project demonstrates how Python can be used for data cleaning, exploration, statistical analysis, and visualization. It provides a better understanding of the factors associated with used car prices and helps develop practical skills in data analysis.

---
**Developed by:** G. Akshra  
**College:** NIST  
**Department:** CSE (AI & ML)  
**Project:** Exploratory Data Analysis (EDA) on Used Cars Dataset
