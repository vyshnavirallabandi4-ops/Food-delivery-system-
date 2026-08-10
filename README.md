# 🍔 Food Delivery SQL Database

A **MySQL-based Food Delivery Database Management System** designed to manage customers, restaurants, menu items, orders, delivery partners, payments, and reviews.

This project demonstrates practical **SQL database design, relationships, data management, and business analysis queries**.

## 🚀 Features

* 👤 Customer Management
* 🍴 Restaurant Management
* 📋 Menu Item Management
* 🛒 Order Management
* 📦 Order Item Tracking
* 🛵 Delivery Partner Management
* 💳 Payment Tracking
* ⭐ Customer Reviews & Ratings
* 📊 Revenue Analysis
* 📈 Customer Spending Analysis
* 🔥 Popular Food Item Analysis

## 🗄️ Database Tables

The project contains the following tables:

| Table               | Description                         |
| ------------------- | ----------------------------------- |
| `customers`         | Stores customer information         |
| `restaurants`       | Stores restaurant details           |
| `delivery_partners` | Stores delivery partner information |
| `menu_items`        | Stores restaurant menu items        |
| `orders`            | Stores customer orders              |
| `order_items`       | Stores items included in each order |
| `payments`          | Stores payment information          |
| `reviews`           | Stores customer reviews and ratings |

## 🔗 Database Relationships

* A customer can place multiple orders.
* A restaurant can have multiple menu items.
* A restaurant can receive multiple orders.
* An order can contain multiple food items.
* A delivery partner can deliver multiple orders.
* An order can have a payment record.
* Customers can submit reviews for restaurants.

## 🛠️ Technologies Used

* **MySQL**
* **SQL**
* **GitHub**

## ▶️ How to Run

1. Clone or download this repository.
2. Open **MySQL Workbench** or another MySQL-compatible database tool.
3. Open `food_delivery.sql`.
4. Execute the SQL script.
5. The `food_delivery` database will be created automatically.
6. Sample data will be inserted into the database.
7. Run the included queries to analyze the food delivery data.

## 📊 SQL Analysis

The project includes SQL queries for:

* Viewing customers
* Viewing restaurants
* Displaying restaurant menus
* Viewing complete order details
* Finding highly rated restaurants
* Finding expensive menu items
* Calculating total revenue
* Calculating average order value
* Calculating restaurant-wise revenue
* Finding the most popular food items
* Viewing customer order history
* Finding top customers by spending
* Analyzing delivery partner performance
* Finding pending orders
* Analyzing customer reviews
* Checking payment status

## 💡 Business Questions

This database can be used to answer questions such as:

* Which restaurant generates the highest revenue?
* Which food item is ordered the most?
* Which customers spend the most?
* What is the average order value?
* Which restaurant has the highest rating?
* How many orders are currently pending?
* Which payment method is most commonly used?

## 📁 Project Structure

```text
Food-Delivery-SQL/
│
├── food_delivery.sql
└── README.md
```

## 🔮 Future Improvements

Possible future enhancements include:

* Restaurant login and authentication
* Customer authentication
* Coupon and discount management
* Real-time food delivery tracking
* Order cancellation and refunds
* Multiple customer addresses
* Restaurant operating hours
* Advanced sales dashboards
* Stored procedures
* Triggers
* SQL views
* Database indexing and optimization

## 👩‍💻 Author

**Vyshanavi Sri Swathi**

## 📌 Project Purpose

This project was developed for **learning and practicing SQL, relational database design, joins, foreign keys, aggregation, and business data analysis**.

---

⭐ **If you find this project useful, feel free to star the repository!**
