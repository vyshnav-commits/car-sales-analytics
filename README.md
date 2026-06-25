# Automotive Sales Analytics & Market Insights System

A comprehensive Exploratory Data Analysis (EDA) project focused on analyzing automotive market data to extract patterns regarding vehicle sales, pricing structures, engine configurations, and fuel efficiency.

## 🚀 Key Features & Analysis
- **Data Preprocessing & Cleansing:** Handled missing values and structured inconsistent records into a normalized format using Python and Pandas.
- **Advanced Data Aggregation:** Implemented complex `groupby` multi-key aggregations to evaluate automotive manufacturer performance metrics (total volume, average pricing, power metrics).
- **Statistical Relationships:** Explored patterns between production pricing strategies, resale value, and raw engineering specifications like horsepower and engine displacement.
- **Data Visualization:** Built distribution and comparative charts using Matplotlib and Seaborn to clearly convey analytical findings.

## 🛠️ Tech Stack & Tools Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook / Anaconda

## 📊 Sample Insights Generated
- Grouped vehicle lines by manufacturing brand using `.groupby('Manufacturer')` to calculate the aggregate performance footprint across global models.
- Highlighted distinct thresholds mapping a vehicle's curb weight and horsepower relative to its final fuel efficiency rating.

## 📂 Project Structure
- `Car_sales.csv`: The underlying vehicle sales and specifications dataset.
- `car_sales_analysis.ipynb`: Core data science exploration pipeline containing the code and visualizations.
- `README.md`: Project documentation.
