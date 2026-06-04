# -🏠 California Housing Data Analysis
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the California Housing Dataset to understand housing trends, income distribution, population patterns, and factors influencing house values in California.

The project includes data cleaning, statistical analysis, and data visualization using Python libraries such as Pandas and Matplotlib.

📂 Dataset Source

This project uses the California Housing Dataset.

Kaggle Dataset Link:

California Housing Prices Dataset (Kaggle)

Dataset Details
Number of Records: 20,640
Features: 10
Target Variable: median_house_value
Dataset Type: Housing and Real Estate
Source: California Census Data
🎯 Objectives
Load and explore housing data
Identify and handle missing values
Remove duplicate records
Generate descriptive statistics
Analyze housing characteristics
Visualize geographic housing patterns
Study income and population distributions
Understand relationships between housing features
🛠️ Technologies Used
Python
Pandas
Matplotlib
NumPy
Google Colab
📊 Dataset Features
Feature	Description
longitude	Geographic longitude
latitude	Geographic latitude
housing_median_age	Median age of houses
total_rooms	Total number of rooms
total_bedrooms	Total number of bedrooms
population	Population in the area
households	Number of households
median_income	Median income of residents
median_house_value	Median house value
ocean_proximity*	Distance from ocean (available in full dataset)
⚙️ Project Workflow
1. Data Loading
Imported California Housing Dataset using Pandas.
Displayed sample records for inspection.
2. Data Cleaning
Checked for missing values.
Removed duplicate records.
Filled missing numerical values using mean values.
Filled missing categorical values using mode values.
3. Exploratory Data Analysis (EDA)

Performed:

Dataset preview
Dataset information analysis
Statistical summary generation
Average income analysis
Average house value analysis
Population analysis
Housing age analysis
4. Housing Age Analysis

Grouped data by:

Housing Median Age

Calculated average values for:

Median Income
House Value
Population
Total Rooms
Total Bedrooms
📈 Visualizations
1. California Housing Map

A scatter plot showing:

Longitude vs Latitude
Color indicates Median House Value
Point size represents Population
2. Median Income Distribution

Histogram displaying:

Income distribution across California regions
3. Total Rooms vs Total Bedrooms

Scatter plot showing:

Relationship between rooms and bedrooms
4. Housing Median Age Distribution

Pie chart showing:

Distribution of houses based on median age
📊 Key Findings
Areas with higher median incomes generally have higher house values.
Population density varies significantly across locations.
Total bedrooms increase proportionally with total rooms.
Housing age impacts property value and housing characteristics.
Geographic location strongly influences house prices.
🚀 How to Run the Project
Clone the Repository
git clone https://github.com/your-username/california-housing-analysis.git

cd california-housing-analysis
Install Dependencies
pip install pandas numpy matplotlib
Run the Script
python california_housing_analysis.py

Or open the notebook in Google Colab and run all cells.

📁 Project Structure
📦 California-Housing-Analysis
│
├── california_housing_analysis.ipynb
├── california_housing_analysis.py
├── README.md
│
└── visualizations/
    ├── housing_map.png
    ├── income_distribution.png
    ├── rooms_vs_bedrooms.png
    └── housing_age_distribution.png
    
ouput preview:

<img width="880" height="436" alt="image" src="https://github.com/user-attachments/assets/d2346e4a-9585-47ba-8b87-e61f6709a63b" />
<img width="568" height="437" alt="image" src="https://github.com/user-attachments/assets/9d97db4f-0355-4dc3-8787-b469fe5258aa" />
<img width="563" height="439" alt="image" src="https://github.com/user-attachments/assets/a1a2e239-9abb-466b-a257-67239679860a" />
<img width="572" height="518" alt="image" src="https://github.com/user-attachments/assets/2f0f2539-ec4f-45d4-9399-f8c2f9e351ce" />


📋 Output Generated:

Cleaned dataset
Statistical summaries
Housing age analysis
Income distribution analysis
Geographic housing visualization
Population insights
Housing value trends

# -Author

Veeramanikandan.S

Student Project – California Housing Data Analysis using Python, Data Cleaning, Exploratory Data Analysis (EDA), and Data Visualization.
