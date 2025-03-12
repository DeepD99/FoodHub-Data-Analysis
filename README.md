# FoodHub Order Analysis

## Context
The number of restaurants in New York is increasing rapidly. Many students and busy professionals rely on these restaurants due to their hectic lifestyles. **Online food delivery services** provide a convenient way for them to enjoy meals from their favorite restaurants.  

**FoodHub**, a food aggregator company, offers access to multiple restaurants through a single smartphone app. The app enables customers to place orders directly with restaurants, and a **delivery person** from the company picks up and delivers the food.  

### How It Works:
1. Customers place orders via the app.  
2. The restaurant receives and confirms the order.  
3. A delivery person is assigned to pick up the order.  
4. The delivery person collects the food and confirms pickup.  
5. The food is delivered to the customer's location.  
6. The customer rates the order.  

FoodHub earns revenue by collecting a fixed margin from each delivery order placed through the platform.  

---

## Objective
FoodHub has been storing data on various orders placed by customers. The company aims to analyze this data to gain insights into:  
- **Restaurant demand patterns**  
- **Customer preferences**  
- **Delivery performance**  
- **Customer ratings and feedback**  

As a **Data Scientist**, your task is to analyze the dataset and answer key business questions that will help improve FoodHub’s operations and customer experience.

---

## Data Description
The dataset contains information about food orders placed through the FoodHub platform. Below is a detailed data dictionary:

### **Data Dictionary**
| Column Name           | Description |
|----------------------|-------------|
| `order_id`          | Unique ID of the order |
| `customer_id`       | ID of the customer who placed the order |
| `restaurant_name`   | Name of the restaurant |
| `cuisine_type`      | Type of cuisine ordered |
| `cost_of_the_order` | Cost of the order (in USD) |
| `day_of_the_week`   | Indicates whether the order was placed on a weekday or weekend *(Weekday: Monday to Friday, Weekend: Saturday & Sunday)* |
| `rating`           | Rating given by the customer (out of 5) |
| `food_preparation_time` | Time (in minutes) taken by the restaurant to prepare the food *(Difference between order confirmation and pickup confirmation)* |
| `delivery_time`     | Time (in minutes) taken by the delivery person to deliver the food *(Difference between pickup and drop-off timestamps)* |

---

## Getting Started
To begin analyzing the dataset, you can follow these steps:

1. **Download the dataset** and store it in your working directory.
2. **Load the dataset** using Python libraries such as `pandas`.
3. **Perform exploratory data analysis (EDA)** to understand key trends.
4. **Answer business questions** related to restaurant demand, delivery performance, and customer satisfaction.

---

## Tools & Technologies
You can use the following tools for analysis:

- **Python**
- **Jupyter Notebook**
- **Pandas, NumPy, Matplotlib, Seaborn** for data analysis and visualization
- **Scikit-learn** for machine learning (if required)

---

## Contributing
If you have suggestions or improvements, feel free to submit a pull request!

---

## License
This project is licensed under the MIT License.
