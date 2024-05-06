# Project Summary

The project aims to build an interactive Microsoft Excel dashboard to enable users to quickly identify trends in coffee bean sales and compare these sales across bean types and countries.

# Project Environment

The entire project is carried out using Microsoft Excel.

# Scope & Project Steps

## Scope

This project involves end-to-end data analysis in Excel, from data gathering to data cleaning and transformation, all the way to creating meaningful visualizations in the form of a dynamic, interactive dashboard.

## Project Steps

1. Data Gathering
2. Data Preparation Using Advanced Formulas and Functions
3. Exploratory Data Analysis
4. Data Visualizations And Dashboard Build Using Pivot Tables, Pivot Charts, Timeline, and Slicers

# Data Sources & Data Gathering

## Data Sources

1. Coffee Bean Sales CSV 

## Data Gathering

The data contains three separate tables — `orders`, `customers`, and `products`, with the `orders` table being the fact table, and the `customers` and `products` tables the dimension tables.

# Data Preparation

- Use `XLOOKUP` to look up the full customer name from the `customers` table to the `orders` table

- Use `IF` and `XLOOKUP` to look up the email address from the `customers` table to the `orders` table

- Use `XLOOKUP` to look up the country of the customer from the `customers` table to the `orders` table

- Use only one dynamic `INDEX` `MATCH` formula to look up the coffee type, roast type, size, and unit price values from the `products` table to the `orders` table

- Calculate the sales as the product of price*quantity

- Use multiple `IF` functions to map the full coffee type and roast type names

- Use `XLOOKUP` to look up the loyalty card status from the `customers` table to the `orders` table

# Dashboard Build

## Total Sales Over Time — Line Chart

See Portfolio - Detailed Report

**Make sure to connect the slicers to all of the Pivot Tables/Charts to ensure that you filter everything when you click them.**

# The Final Dashboard
