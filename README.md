# Amazon-Products-Sales-Analysis

## Overview
This project analyzes a dataset of Amazon products with various attributes, such as ratings, price, and category. The goal is to provide insights into the product pricing and ratings, while also answering some specific questions related to product categories and prices.

The analysis includes the following:

- Price distributions

- Correlations between product ratings and price

- Price ranges per product subcategory

- Insights into products with the highest prices

## Dataset
The dataset consists of several product listings from Amazon, including the following columns:

- **name:** The product name

- **main_category:** The main category of the product (e.g., Appliances, Electronics)

- **sub_category:** The subcategory of the product (e.g., Air Conditioners, Washing Machines)

- **ratings:** Product rating (on a scale of 1 to 5)

- **no_of_ratings:** Number of ratings

- **discount_price:** Discounted price (if available)

- **actual_price:** Actual price (before any discounts)

- **image:** Link to the product image (removed for analysis)

- **link:** URL to the product on Amazon (removed for analysis)

## Data Cleaning and Preprocessing
- Removed unnecessary columns (e.g., image, link).

- Cleaned price columns (discount_price, actual_price) by removing currency symbols (₹) and commas.

- Handled missing values in ratings, no_of_ratings, discount_price, and actual_price.

## Analysis
**1. Average Price of Air Conditioners**
The average price of Air Conditioners, taking into account the discount price and the actual price when there is no discount, is ₹38,725.55.

**2. Product Categories with the Highest Prices**
The category with the highest prices is TV, Audio & Cameras with products reaching up to ₹1,249,990.

**3. Correlation between Price and Ratings**
There is a very weak positive correlation (0.0788) between price and ratings. Although the relationship suggests that higher-priced products tend to have slightly higher ratings, the correlation is not strong enough to draw definitive conclusions.

**4. Price Range by Subcategory**
The price range for products varies significantly by subcategory. For example:

- **Air Conditioners** have prices ranging from ₹199 to ₹128,800.

- **Washing Machines** range from ₹99 to ₹230,000.

This indicates considerable variation in product prices within each subcategory.
