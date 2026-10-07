
# Python Data Analysis – Airbnb Market & Pricing Analysis

## Project Overview

This project uses Python and Pandas to clean, explore and analyse Airbnb listing data.

The analysis focuses on understanding listing distribution, pricing patterns, guest activity, availability and host competition.

## Business Problem

How can Airbnb hosts and property managers use listing, pricing, location and review data to make better pricing and property-management decisions?

## Data Preparation

The dataset was analysed and cleaned using Python and Pandas.

The cleaning process included:


- Checking dataset structure and data types
- Identifying missing values
- Checking duplicate records
- Removing completely empty columns
- Handling missing review activity
- Converting review dates into datetime format
- Handling missing minimum-night values
- Filling missing prices using room-type median values
- Validating numerical values
- Reviewing potential outliers

Outliers were reviewed rather than automatically removed because extreme values may represent genuine market behaviour.

## Exploratory Data Analysis

The following analyses were performed:

- Airbnb listings by room type
- Average and median price by room type
- Listing concentration by neighbourhood
- Average neighbourhood pricing
- Room type and neighbourhood distribution
- Review and guest activity analysis
- Availability analysis
- Price versus guest activity
- Host competition analysis
- Top-reviewed listings
- Premium/high-priced listings
- Price and review correlation
- Minimum-night analysis

## Key Insights

The analysis was used to identify:

- Differences in listing distribution across room types
- Pricing differences between accommodation types
- Areas with higher listing concentration
- Areas with higher average prices
- Patterns in guest review activity
- Relationship between price and guest activity
- Host-level competition through multiple listings
- Listings with unusually high prices or review activity

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter / Google Colab

## Output

The complete Python analysis and visualisations are available in:

`NYC_Airbnb_Python_Analysis.pdf`

The cleaned dataset is available in the project's `data` folder.

## Project Workflow

Data Loading  
↓  
Data Inspection  
↓  
Data Cleaning  
↓  
Data Validation  
↓  
Exploratory Data Analysis  
↓  
Business Analysis  
↓  
Insights

## Conclusion

This Python analysis demonstrates an end-to-end data preparation and exploratory analysis workflow using Pandas and Matplotlib.

The analysis provides a foundation for understanding Airbnb listing patterns, pricing, guest activity, availability and host competition.
