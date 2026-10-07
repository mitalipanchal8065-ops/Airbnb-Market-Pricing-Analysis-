# Airbnb-Market-Pricing-Analysis-

# Airbnb Market & Pricing Analysis

## 📌 Project Overview

This project is an end-to-end data analytics project focused on understanding Airbnb listing patterns, pricing, guest activity, availability and host competition.

The project follows a complete analytics workflow from data cleaning and exploratory analysis to business insights and Power BI dashboard development.

---

## 🎯 Business Problem

How can Airbnb hosts and property managers use listing, pricing, location and review data to make better pricing and property-management decisions?

The analysis focuses on understanding:

- Which room types dominate the market?
- How does pricing vary by room type?
- Which areas have higher listing concentration?
- How does pricing relate to guest activity?
- What patterns can help hosts make better business decisions?

---

## 📊 Dataset

The dataset contains Airbnb listing-level information including:

- Listing ID
- Host ID
- Neighbourhood
- Room Type
- Price
- Minimum Nights
- Number of Reviews
- Reviews per Month
- Availability
- Host Listing Count

The dataset contains 490 listing records after preparation.

---

## 🧹 Data Cleaning

Python and Pandas were used for data preparation.

The cleaning process included:

- Removing completely empty columns
- Checking missing values
- Handling missing review activity
- Converting review dates into datetime format
- Handling missing minimum-night values
- Filling missing prices using room-type median values
- Checking duplicate records
- Reviewing numerical outliers

Extreme values were reviewed rather than automatically removed because they may represent genuine market behaviour.

---

## 🔎 Exploratory Data Analysis

The following areas were analysed:

- Room type distribution
- Average and median pricing
- Neighbourhood listing concentration
- Neighbourhood pricing
- Reviews and guest activity
- Availability
- Price versus guest activity
- Host competition
- Premium listings
- Minimum-night patterns

---

## 📈 Power BI Dashboard

An interactive Power BI dashboard was created to present the major findings from the analysis.

The dashboard includes:

- Total Listings
- Average Price
- Review metrics
- Average Availability
- Listings by Room Type
- Average Price by Room Type
- Area-level listing comparison
- Area-level pricing comparison
- Price versus review activity
- Interactive filters

---

## 💡 Key Business Insights

The analysis indicates that:

1. Entire-home/apartment listings represent the dominant accommodation segment.
2. Pricing varies considerably between accommodation types.
3. The difference between average and median price indicates the presence of higher-priced listings.
4. Listing concentration varies across neighbourhood/ward areas.
5. Price alone does not strongly explain guest review activity.
6. A small group of hosts manages multiple listings, creating additional competitive pressure.
7. Availability should be analysed together with review activity rather than being interpreted on its own.

---

## 💼 Business Recommendations

Based on the analysis:

- Use room-type-specific pricing benchmarks.
- Compare prices with similar listings in the same area.
- Monitor median pricing in addition to average pricing.
- Track availability together with guest activity.
- Monitor multi-listing hosts to understand local competition.
- Investigate unusual values before removing them from analysis.

---

## 🛠️ Tools Used

- Python
- Pandas
- Matplotlib
- Power BI
- CSV
- GitHub

---

## 🔄 Project Workflow

Data Collection  
↓  
Data Cleaning  
↓  
Exploratory Data Analysis  
↓  
Business Analysis  
↓  
Business Insights  
↓  
Power BI Dashboard  
↓  
Business Report  
↓  
Portfolio Documentation

---

## 📁 Project Structure

```text
Airbnb-Market-Pricing-Analysis/
│
├── data/
├── python/
├── powerbi/
├── report/
└── README.md
