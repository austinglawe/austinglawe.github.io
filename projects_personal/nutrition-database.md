# USDA Nutrition Database Pipeline

## Overview
This project demonstrates how to build a structured nutrition database using official USDA FoodData Central datasets.

## Objectives
- Source reliable, real-world nutrition data
- Transform raw datasets into a structured SQL database
- Establish relationships between foods and nutrients

## Tools & Technologies
- SQL Server
- CSV

## Step 1: Download the Dataset
Go to:
https://fdc.nal.usda.gov/download-datasets

- Select Foundation Foods
- Download latest CSV

## Step 2: Extract the Files
After downloading:
- Extract the ZIP file
- You should see:
food.csv
nutrient.csv
food_nutrient.csv
food_category.csv


## Data Structure Overview

| File | Description |
|------|------------|
| food.csv | Contains all food items |
| nutrient.csv | Defines nutrients |
| food_nutrient.csv | Links foods to nutrients |
| food_category.csv | Food group categories |

## Next Steps
- Build SQL tables
- Import data
- Create relationships
