# Avocado Toast: A Supply Chain Analysis

## Overview

In the bustling city of London, the avocado toast has become a breakfast staple. With its rise in popularity, understanding the intricacies of its supply chain becomes crucial. This project delves into a supply chain analysis of three key ingredients: avocados, olive oil, and sourdough bread, sourced from the Open Food Facts database.

![Avocado Toast Wallpaper](avocado_wallpaper.jpeg)


## Objective

The primary goal is to determine the most common country(s) of origin for the three ingredients. This involves data manipulation, analysis, and filtering based on specific categories and tags.

## Data Files

The data is organized into three pairs of files:
- CSV files (e.g., `avocado.csv`) containing detailed food item data, including countries of origin.
- TXT files (e.g., `relevant_avocado_categories.txt`) that specify the relevant category tags for each ingredient.

### Data Preprocessing

1. **Filtering**: Rows with irrelevant data are filtered based on the `categories_tags` column. Only rows containing specific tags like fruits, vegetables, or fruit-based oils are retained.
2. **Subsetting**: The DataFrames are subsetted to include only relevant columns such as 'code', 'lc', 'product_name_en', 'quantity', 'serving_size', and more.

## Variables

Upon completion, the project will determine:
- `top_avocado_origin`: The most common country of origin for avocados.
- `top_olive_oil_origin`: The most common country of origin for olive oil.
- `top_sourdough_origin`: The most common country of origin for sourdough bread.

## Further Analysis

After obtaining the primary insights, the dataset remains available for further exploration. You can delve into additional questions or analyses based on the food data.

## Acknowledgments

This project is adapted from a DataCamp project, providing hands-on experience in supply chain analysis and data manipulation.

---

Feel free to use this README file in your project repository to provide a clear overview and guide for anyone interested in your supply chain analysis project.
