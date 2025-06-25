# 🍕 Pizza Sales Data Analysis

This project provides SQL queries to analyze pizza sales data using a relational database. The queries are grouped into three levels: **Basic**, **Intermediate**, and **Advanced**.

## 🗃️ Assumed Database Schema

- **orders**(`order_id`, `date`, `time`)
- **order_details**(`order_details_id`, `order_id`, `pizza_id`, `quantity`)
- **pizzas**(`pizza_id`, `pizza_type_id`, `size`, `price`)
- **pizza_types**(`pizza_type_id`, `name`, `category`, `ingredients`)

## ✅ Basic Queries

1. **Retrieve the total number of orders placed**
2. **Calculate the total revenue generated from pizza sales**
3. **Identify the highest-priced pizza**
4. **Identify the most common pizza size ordered**
5. **List the top 5 most ordered pizza types along with their quantities**

---

## 🔄 Intermediate Queries

1. **Join the necessary tables to find the total quantity of each pizza category ordered**
2. **Determine the distribution of orders by hour of the day**
3. **Join relevant tables to find the category-wise distribution of pizzas**
4. **Group the orders by date and calculate the average number of pizzas ordered per day**
5. **Determine the top 3 most ordered pizza types based on revenue**

---

## 📈 Advanced Queries

1. **Calculate the percentage contribution of each pizza type to total revenue**
2. **Analyze the cumulative revenue generated over time**
3. **Determine the top 3 most ordered pizza types based on revenue for each pizza category**

---
