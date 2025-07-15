# 🍽️ Task 2: Price Range Analysis - Restaurant Dataset

## 📌 Objective

This task focuses on analyzing the relationship between restaurant price ranges and their ratings. The goals are:

1. Determine the **most common price range** among all restaurants.
2. Calculate the **average rating** for each price range.
3. Visualize the results and **highlight** the price range with the highest average rating using a distinct color.

---

## 📊 Dataset Overview

The dataset includes information such as:
- Restaurant Name
- Has Table Booking
- Has Online Delivery
- Aggregate Rating
- Price Range
- Other attributes

The analysis uses the following key columns:
- `price_range`: Numerical value (typically from 1 to 4), representing cost category.
- `aggregate_rating`: Customer ratings on a scale of 0 to 5.

---

## 🧪 Technologies Used

- Python 3.x
- Pandas (data handling)
- Matplotlib & Seaborn (data visualization)
- Google Colab (notebook environment)

---

## ✅ Steps Performed

### 1. Data Preprocessing
- Removed whitespaces and standardized column names.
- Converted `price_range` and `aggregate_rating` to numeric types.

### 2. Most Common Price Range
- Identified using `mode()` on the `price_range` column.

### 3. Average Rating per Price Range
- Grouped data using `groupby()` and calculated the mean rating for each price category.

### 4. Visualization
- Created a **bar chart** using Seaborn.
- The price range with the **highest average rating** is shown in **green** for emphasis.

---

## 📈 Key Insights

- The most frequent price range reveals where the majority of restaurants are positioned in terms of affordability.
- Rating trends across price ranges may indicate if premium pricing correlates with better customer satisfaction.
- Visual highlighting helps quickly identify the best-performing category.

---

## 🖼️ Sample Visualization

Bar chart showing:
- X-axis: Price Ranges
- Y-axis: Average Ratings
- Green Bar: Highest Rated Price Range

---

## 📝 How to Run

1. Open the notebook in **Google Colab**.
2. Upload the dataset using:
   ```python
   from google.colab import files
   files.upload()
