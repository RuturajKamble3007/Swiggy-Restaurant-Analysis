# Swiggy Restaurant Analysis Using SQL
Swiggy restaurant data analysis using MySQL and SQL

## Project Overview

This project analyzes Swiggy restaurant data using MySQL to identify restaurant distribution, cuisine popularity, restaurant chains, rating patterns, and pricing trends across Indian cities.

The project demonstrates practical SQL skills including data cleaning, filtering, aggregation, GROUP BY, HAVING, CASE statements, and business-oriented analysis.

---

## Objectives

The main objectives of this project are:

- Identify cities with the highest number of restaurants
- Find the most popular cuisine combinations
- Identify restaurant chains with the maximum number of branches
- Analyze city-wise restaurant ratings
- Identify the most and least expensive cities
- Analyze restaurants based on different price categories
- Generate meaningful business insights from restaurant data

---

## Dataset

**Dataset:** Swiggy Restaurants Dataset

**Source:** Kaggle

The dataset contains restaurant information including:

- Restaurant ID
- Name
- City
- Rating
- Rating Count
- Cost
- Cuisine
- License Number
- Swiggy Restaurant Link
- Address

The dataset contains more than 100,000 restaurant records across Indian cities.

---

## Tools & Technologies

- MySQL
- MySQL Workbench
- SQL
- CSV
- GitHub

---

## SQL Concepts Used

This project uses the following SQL concepts:

- SELECT
- WHERE
- GROUP BY
- HAVING
- ORDER BY
- LIMIT
- COUNT()
- AVG()
- ROUND()
- CAST()
- REPLACE()
- CASE
- Aggregate Functions
- Data Cleaning
- Filtering
- Conditional Logic

---

# Business Questions

The analysis answers the following business questions:

1. Which city has the most restaurants on Swiggy?
2. What is the most common cuisine combination?
3. Which restaurant chain has the maximum branches?
4. Which city has the best average rating with more than 50 restaurants?
5. Which city has the highest average restaurant cost?
6. Which city has the lowest average restaurant cost?
7. How are restaurants distributed across budget, mid-range, and premium price categories?

---

# Key Findings

## 1. City with Most Restaurants

**Bikaner** has the highest number of restaurants in the dataset.

- **Restaurants:** 756

---

## 2. Most Popular Cuisine Combination

The most common cuisine combination is:

**North Indian,Chinese**

- **Restaurants:** 2,676

---

## 3. Restaurant Chain with Maximum Branches

**Domino's Pizza** has the highest number of branches in the dataset.

- **Branches:** 405

---

## 4. Best-Rated City with 50+ Restaurants

**South Kolkata,Kolkata** has the highest average rating among cities with more than 50 restaurants.

- **Average Rating:** 4.23
- **Restaurants:** 241

---

## 5. Most Expensive City

**Khan Market,Delhi** has the highest average restaurant cost.

- **Average Cost:** ₹632

---

## 6. Cheapest City

**Hindaun** has the lowest average restaurant cost.

- **Average Cost:** ₹125

---

# Price Category Analysis

Restaurants were classified into three price categories using SQL CASE statements:

| Price Category | Cost Range |
|---|---|
| Budget | Below ₹300 |
| Mid-Range | ₹300 – ₹599 |
| Premium | ₹600 and above |

This analysis helps understand the distribution of restaurants across different pricing segments and compare their average ratings.

---

# Project Structure

```text
Swiggy-Restaurant-Analysis/
│
├── data/
│   └── swiggy_clean.csv
│
├── results/
│   ├── top_cities.png
│   ├── top_cuisines.png
│   ├── top_restaurant_chains.png
│   ├── best_rated_cities.png
│   ├── expensive_cities.png
│   └── price_categories.png
│
├── sql/
│   ├── 01_data_cleaning.sql
│   ├── 02_city_analysis.sql
│   ├── 03_cuisine_analysis.sql
│   ├── 04_restaurant_analysis.sql
│   ├── 05_rating_analysis.sql
│   └── 06_pricing_analysis.sql
│
└── README.md
