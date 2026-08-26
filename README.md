# Car Price Prediction & Seaborn Visualization

## 📌 Project Overview

This project performs **car price analysis and data visualization using Python, Pandas, Matplotlib, NumPy, and Seaborn**.

The notebook uses the `CarPrice_Assignment.csv` dataset to explore different characteristics of cars and understand how features such as horsepower, engine size, fuel type, body style, and drive wheel relate to car prices.

## 🎯 Objectives

- Load and inspect the car price dataset.
- Check for missing/null values.
- Analyze the highest, lowest, and average selling prices.
- Compare average prices by fuel type.
- Analyze car distribution by fuel type and body style.
- Categorize cars into **Budget, Premium, and Luxury** price ranges.
- Visualize car-price relationships using Seaborn.
- Analyze correlations between numerical car features.
- Identify the top 10 most expensive cars.
- Create a final car analytics dashboard summary.

## 📂 Dataset

The project uses:

`CarPrice_Assignment.csv`

The dataset contains information about car characteristics and prices, including:

- `car_ID`
- `symboling`
- `CarName`
- `fueltype`
- `aspiration`
- `doornumber`
- `carbody`
- `drivewheel`
- `enginelocation`
- `wheelbase`
- `carlength`
- `carwidth`
- `carheight`
- `curbweight`
- `enginetype`
- `cylindernumber`
- `enginesize`
- `fuelsystem`
- `boreratio`
- `stroke`
- `compressionratio`
- `horsepower`
- `peakrpm`
- `citympg`
- `highwaympg`
- `price`

## 🛠️ Technologies Used

- **Python**
- **Pandas** – data loading, manipulation, grouping, and analysis
- **NumPy** – numerical operations
- **Matplotlib** – basic plotting
- **Seaborn** – statistical data visualization
- **Jupyter Notebook / Google Colab**

## 🔍 Data Analysis

The notebook performs several basic analyses:

### Price Analysis

- Highest selling price
- Lowest selling price
- Average selling price
- Price distribution

### Fuel Type Analysis

- Number of cars by fuel type
- Average selling price by fuel type
- Identification of diesel cars

### Car Feature Analysis

- Most common drive-wheel type
- Price comparison by body style
- Price comparison by drive wheel
- Horsepower vs. price
- Engine size vs. price

### Price Categorization

A new `Price_Category` column is created using three categories:

- **Budget**
- **Premium**
- **Luxury**

The categories are generated using `pd.cut()` with three equal-width bins.

## 📊 Seaborn Visualizations

The notebook contains the following visualizations:

1. Distribution of car prices
2. Average selling price by fuel type
3. Car price distribution by body style
4. Car price distribution by drive wheel
5. Horsepower vs. car price
6. Engine size vs. car price
7. Number of cars by fuel type
8. Number of cars by body style
9. Number of cars in each price category
10. Correlation heatmap of numerical car features
11. Top 10 most expensive cars
12. Pairwise relationships among price, horsepower, engine size, and curb weight

## 📈 Dashboard Summary

The notebook generates a summary containing:

- Total number of cars
- Average selling price
- Highest selling price
- Lowest selling price
- Most common fuel type
- Top 5 most expensive cars

## 🚀 How to Run

### 1. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 2. Place the dataset in the expected location

The notebook currently loads the dataset using:

```python
pd.read_csv('/content/CarPrice_Assignment.csv')
```

If you are running the notebook locally, update the path to the location of `CarPrice_Assignment.csv`.

### 3. Open the notebook

Open:

```text
Car_prediction_seaborn_visualization(1).ipynb
```

using Jupyter Notebook, JupyterLab, or Google Colab.

### 4. Run the cells

Run the notebook cells from top to bottom to reproduce the data analysis and visualizations.

## 📁 Project Structure

```text
Car-Price-Analysis/
│
├── Car_prediction_seaborn_visualization(1).ipynb
├── CarPrice_Assignment.csv
└── README.md
```

## 💡 Key Learning Outcomes

This project demonstrates practical use of:

- Data loading with Pandas
- Data inspection and cleaning
- GroupBy analysis
- Sorting and filtering
- Creating derived categorical columns
- Statistical visualization
- Categorical plots
- Scatter plots
- Correlation analysis
- Heatmaps
- Pair plots
- Exploratory Data Analysis (EDA)

## 📌 Note

Despite the notebook filename containing **"Car prediction"**, the provided notebook primarily performs **exploratory data analysis and visualization**. It does not contain a trained machine-learning price prediction model; the main focus is car-price analysis using Pandas, Matplotlib, and Seaborn.

## Author

**Disha Dhingra**  
Data Analyst | Power BI | SQL | Python | Advanced Excel

- GitHub: [disha2093](https://github.com/disha2093)
- LinkedIn: [Disha Dhingra](https://www.linkedin.com/in/disha-dhingra2003/)

---
**Car Price Analysis Project**

Built for learning and practicing Python-based data analysis and visualization.
