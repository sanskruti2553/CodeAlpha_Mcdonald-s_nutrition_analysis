# 🍔 McDonald's Nutrition Data Visualization

## 📌 Project Overview

This project focuses on transforming McDonald's menu nutrition data into clear and meaningful visualizations. Using Python, Pandas, Matplotlib, and Seaborn, the project explores calories, protein, fat, carbohydrates, sugar, sodium, and other nutritional components to identify patterns and trends.

## 🎯 Objectives

- Transform raw nutritional data into meaningful visualizations.
- Compare nutritional values across McDonald's menu categories.
- Identify menu items with high calories, sugar, fat, protein, carbohydrates, and sodium.
- Explore relationships between different nutritional components.
- Create clear visualizations that communicate insights effectively.

## 📂 Dataset

The dataset contains **141 McDonald's menu items** with **14 columns** covering menu information and nutritional values.

### Main Features

- `item` – Menu item name
- `servesize` – Serving size
- `calories` – Calories
- `protein` – Protein content
- `totalfat` – Total fat
- `satfat` – Saturated fat
- `transfat` – Trans fat
- `cholesterol` – Cholesterol
- `carbs` – Carbohydrates
- `sugar` – Sugar
- `addedsugar` – Added sugar
- `sodium` – Sodium
- `menu` – Menu category

## 🛠️ Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 🔄 Project Workflow

1. Load the dataset
2. Inspect the dataset structure
3. Check and handle missing values
4. Clean column names and data types
5. Perform exploratory analysis
6. Create data visualizations
7. Analyze relationships between nutritional variables
8. Extract meaningful insights

## 📊 Visualizations Created

The project includes:

- Top 10 highest-calorie menu items
- Average calories by menu category
- Protein vs. calories
- Sugar vs. calories
- Sodium vs. calories
- Total fat vs. calories
- Top 10 items by sugar content
- Top 10 items by sodium content
- Number of items by menu category
- Top 10 items by total fat
- Top 10 items by protein
- Top 10 items by carbohydrates
- Nutritional correlation heatmap

## 🔍 Key Insights

- Menu categories differ considerably in their average calorie content.
- Some menu items contain substantially higher levels of sugar, fat, sodium, or calories than others.
- Nutritional variables such as protein, fat, carbohydrates, and calories show varying degrees of correlation.
- Scatter plots help identify relationships and unusual nutritional patterns across menu items.

## 📈 Data Story

The visualizations provide a nutritional overview of McDonald's menu items. By comparing calories and key nutrients across categories and individual products, the analysis makes it easier to understand differences in nutritional composition and identify items with particularly high nutritional values.

## 🚀 How to Run

1. Clone or download this repository.
2. Open the Jupyter Notebook in Google Colab.
3. Upload the McDonald's nutrition dataset.
4. Install/import the required Python libraries.
5. Run the notebook cells sequentially.
6. Explore the generated visualizations and insights.

## 📁 Project Structure

```text
McDonalds-Nutrition-Visualization/
│
├── mcdonaldata.csv
├── McDonalds_Nutrition_Visualization.ipynb
└── README.md
