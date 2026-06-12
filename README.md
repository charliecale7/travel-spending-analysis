# Travel Spending Analysis

This project analyses personal travel spending across a multi-city trip in China. The goal is to understand how money was spent across categories, how spending changed over time, and how costs varied between locations.

The analysis was completed using Python (Pandas, Matplotlib) in a Jupyter Notebook.

The dataset is based on personal travel spending records. Personal information has been removed and some fields have been anonymised for privacy while preserving the structure required for analysis.

---

## Project Objectives

The key questions explored in this project were:

1. How much was spent during the trip?
2. Which categories accounted for the most spending?
3. How did spending change over time?
4. Which locations were the most expensive?
5. What spending patterns can be observed across locations?

---

## Data Cleaning & Preparation

Key preprocessing steps included:

- Converting date columns to datetime format
- Cleaning numeric values with inconsistent formatting
- Removing non-relevant characters from currency fields
- Handling missing values and duplicates
- Mapping transactions to locations based on travel dates
- Excluding inter-city transport (e.g. flights and long-distance travel) for location-based comparisons

---

## Key Insights

- Total trip expenditure was **£3,488.82**, with an average daily spend of **£105.72**.
- Flights were the largest spending category, driven by a small number of high-cost bookings.
- Food & Drink and Accommodation formed the core of day-to-day spending.
- Spending over time was relatively consistent, with sharp spikes caused by flight bookings.
- Average daily spend varied significantly across locations, with some cities costing more than twice as much per day as others.
- Discretionary spending such as Shopping and Miscellaneous was inconsistent and relatively minor.

---

## Location-Based Analysis

Spending was mapped to destinations using travel dates, allowing comparison of costs across cities.

Key findings include:
- Some cities (e.g. Shanghai) were significantly more expensive on a per-day basis than others (e.g. Pingyao)
- Accommodation costs were a major driver of differences between locations
- Longer stays influenced total spend but not always daily spend intensity

---

## Visualisations

The project includes visual analysis of:

- Total and average daily spend
- Category breakdown (pie chart)
- Daily spending over time (line chart)
- Spending by category across locations (stacked bar chart)
- Average daily spend per location (bar chart)

---

## Tools & Libraries

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Project Structure

/data → raw datasets
/notebooks → analysis notebook
/outputs → charts and exported visuals
README.md → project overview

---

## Key Takeaway

This project demonstrates how personal spending data can be structured, cleaned, and analysed to extract meaningful behavioural insights across time and geography. It highlights how travel costs are driven primarily by essential categories, with variation largely influenced by location and duration.

---

## Future Improvements

- Build an interactive dashboard (e.g. Plotly / Power BI)
- Automate location tagging further
- Add inflation or currency conversion adjustments
- Compare multiple trips over time

---
