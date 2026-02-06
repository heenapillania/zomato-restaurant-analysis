# Zomato Restaurant Data Analysis: Market Insights & Business Strategy

## Project Overview
This project performs an exploratory data analysis (EDA) on Zomato restaurant data to understand global and Indian restaurant market trends. The analysis focuses on customer ratings, pricing, cuisines, online delivery availability, and regional patterns to derive actionable business insights.

The objective is to demonstrate how raw food-tech data can be transformed into meaningful insights that support strategic decision-making for platforms like Zomato or similar food delivery startups.

---

## Dataset Description
The project uses two datasets:
1. **Zomato restaurant dataset (CSV)** – contains restaurant-level details such as city, cuisines, ratings, cost for two, votes, and delivery options.
2. **Country code mapping file (Excel)** – maps country codes to country names.

These datasets were merged using a **left join on Country Code** to retain all restaurant records and enrich the data with country information.

- Rows: ~95,000+
- Columns (after cleaning): Restaurant Name, City, Country, Cuisines, Average Cost for Two, Currency, Ratings, Votes, Online Delivery, Table Booking, Price Range

---

## Data Cleaning & Preprocessing
Key preprocessing steps included:
- Merging CSV and Excel datasets using pandas
- Removing unnecessary columns (IDs, coordinates, addresses, UI-related fields)
- Handling missing values by dropping rows with null values in critical columns (e.g., cuisines)
- Removing duplicate restaurant entries based on restaurant name and city
- Filtering invalid rating values (aggregate rating = 0)
- Standardizing column names for consistency

These steps ensured the dataset was clean, relevant, and suitable for analysis.

---

## Key Analysis Performed

### Global-Level Analysis
- Countries with the highest number of restaurants listed on Zomato
- Average restaurant ratings across countries
- Online delivery availability by country
- Comparison of average cost for two across countries

### India-Specific Analysis
- Indian cities with the highest number of restaurants
- Most popular cuisines in India
- Distribution of restaurant ratings
- Relationship between cost for two and ratings
- Online delivery availability across Indian cities
- Relationship between votes and ratings

### Bonus Insights
- Do expensive restaurants always have higher ratings?
- Identification of outliers in pricing and ratings
- Effect of table booking on restaurant ratings

---

## Key Insights
- India has one of the highest numbers of Zomato-listed restaurants globally.
- Online delivery is not widely supported across many countries, while India shows strong adoption.
- Major cities like New Delhi and Bangalore dominate restaurant listings.
- Higher price does not necessarily imply better ratings.
- Restaurants offering table booking and online delivery generally receive higher customer ratings.

---

## Business Recommendations
Based on the analysis:
- New food-tech startups should prioritize expansion in high-density cities while exploring underserved cities.
- Online delivery should be a key focus area, especially in the Indian market.
- Mid-range pricing strategies tend to perform better than extreme low or high pricing.
- Cuisine selection should be aligned with regional popularity and demand.

---

## Limitations
- Customer ratings are subjective and may contain bias.
- Some countries have significantly fewer observations, which can affect average comparisons.
- The dataset does not include customer-level or revenue-level data, limiting deeper behavioral analysis.

---

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Use Cases
- Internship and entry-level data analyst roles
- Portfolio project showcasing EDA and business insight generation
- Practice dataset for data visualization and analytical storytelling

---

## Author
**Heena Pillania**  
M.Sc. Mathematics and Computing, IIT Hyderabad  
Aspiring Data Analyst  
📧 Email: heenapillania82@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/heenapillania

