Project: Exploring the Oldest Businesses in the World

## Introduction
Welcome to our project on the oldest businesses in the world! In this project, we delve into historical business data to discover and understand the characteristics that enable businesses to stand the test of time. We use datasets containing information on businesses, countries, and business categories to explore and analyze the longevity of businesses worldwide.

## Datasets
The project utilizes three main datasets, which are stored in the 'datasets' directory:

1. **businesses.csv:**
   - **Columns:**
     - `business` (varchar): Name of the business.
     - `year_founded` (int): Year the business was founded.
     - `category_code` (varchar): Code for the category of the business.
     - `country_code` (char): ISO 3166-1 3-letter country code.

2. **countries.csv:**
   - **Columns:**
     - `country_code` (varchar): ISO 3166-1 3-letter country code.
     - `country` (varchar): Name of the country.
     - `continent` (varchar): Name of the continent that the country exists in.

3. **categories.csv:**
   - **Columns:**
     - `category_code` (varchar): Code for the category of the business.
     - `category` (varchar): Description of the business category.

## Project Overview

### 1. Exploring the Oldest Businesses in the World
   - We start by loading and sorting the businesses dataset to identify the oldest businesses globally.

### 2. Oldest Businesses in North America
   - We explore the oldest businesses in North America and provide a list of businesses along with their founding years.

### 3. Oldest Business on Each Continent
   - We determine the oldest business on each continent and present the results in a DataFrame.

### 4. Unknown Oldest Businesses
   - We identify countries for which the oldest business information is unknown and provide a list of these countries.

### 5. Adding New Oldest Business Data
   - We supplement missing data by incorporating new oldest business information from "new_businesses.csv."

### 6. The Oldest Industries
   - We explore the oldest businesses in various industries by utilizing the "categories.csv" dataset.

### 7. Restaurant Representation
   - We focus on the category of cafés, restaurants, and bars to identify restaurants that have been around since before the year 1800.

### 8. Categories and Continents
   - We conclude the project by identifying the oldest business in each category for every continent.

For any questions or suggestions, please feel free to contact us. Enjoy exploring the fascinating world of the oldest businesses!
