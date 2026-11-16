# house-rent-data-analysis
Exploratory Data Analysis (EDA) of residential rental prices across major Indian cities using Python, Pandas, and Seaborn.
## 📊 Dataset Overview
The dataset (`house.csv`) contains **4,746 records** and **12 features** describing rental listings across 6 major Indian cities (Kolkata, Mumbai, Bangalore, Delhi, Chennai, and Hyderabad):
* **Rent:** Monthly rental price in INR (Target variable)
* **BHK:** Number of Bedrooms, Hall, and Kitchen
* **Size:** Property area in square feet
* **Bathroom:** Number of bathrooms
* **City:** City where the property is located
* **Other features:** Area Type, Area Locality, Furnishing Status, Tenant Preferred, Floor, Posted On, and Point of Contact

## 🔍 Key Insights & Findings
* **Data Quality:** The dataset is clean with **0 missing values** across all 12 columns.
* **Price Distribution:** The average monthly rent is ~34,993 INR, while the median is 16,000 INR, indicating a strongly right-skewed distribution driven by luxury properties (reaching up to 3,500,000 INR in Bangalore).
* **Primary Price Drivers:** Property `Size` and the number of `Bathrooms` show the strongest positive correlation with `Rent`.
* **Market Composition:** **2 BHK** apartments represent the most common rental configuration on the market.

## 📁 Project Structure

    ├── data/
    │   └── house.csv               # Raw dataset
    ├── notebooks/
    │   └── house_rent_eda.ipynb    # Jupyter Notebook with data cleaning, analysis, and visualizations
    ├── .gitignore                  # Ignored temporary and system files           
    └── README.md                   # Project documentation

## 🛠️ Technologies Used
* **Python 3**
* **Pandas & NumPy** — Data manipulation and statistical analysis
* **Matplotlib & Seaborn** — Data visualization
* **Jupyter Notebook**
