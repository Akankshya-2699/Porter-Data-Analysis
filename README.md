# Porter Delivery Time Analysis

This project aims to develop a model that accurately estimates delivery time for Porter orders by analyzing various factors like restaurant type, items ordered, and delivery partner availability.

## Project Overview
Delivery time is critical in customer satisfaction. By predicting delivery time accurately, Porter can optimize resource allocation, improve delivery times, and boost customer satisfaction.

## Dataset
The dataset consists of 197,415 entries with 14 columns, including:
- `market_id`
- `created_at` (Timestamp of order creation)
- `actual_delivery_time` (Timestamp when the order was delivered)
- `store_primary_category` (Type of restaurant)
- `order_protocol`, `total_items`, `subtotal`, `min_item_price`, etc.

Null values were handled, and features were engineered to improve model performance.

## Key Features Created
- `delivery_time_minutes`: Time taken for delivery in minutes.
- `hour_of_delivery`: The hour when the order was delivered.
- `day_of_week_name`: The name of the day when the order was delivered (e.g., Monday).
- `day_type`: Indicates whether the order was placed on a weekday or weekend.

## Exploratory Data Analysis (EDA)
- Visualized the number of orders per day, week, and month.
- Analyzed order volume differences between weekdays and weekends.
- Examined the distribution of order times throughout the day and identified peak hours.

## Key Insights
- Significant increase in orders during weekends and evening hours.
- Categories like American and Pizza dominate, while niche categories like Belgian and Chocolate have minimal demand.

## How to Use the Notebook
1. Download the dataset (not included for privacy reasons) and save it in the same directory as the notebook.
2. Install the required packages if necessary (see `requirements.txt`).
3. Run the notebook to explore the data, preprocess it, and build models.

## Colab Link
[Open the notebook in Colab](https://colab.research.google.com/drive/1CVbZ2f1BTSx6kGz3rzcwFksyMT8NzLTu)

## License
This project is licensed under the MIT License.
