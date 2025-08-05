# Data-wrangling-in-pandas-
Showing my data cleaning ability 
# HR Data Cleaner & Analyzer (Pandas + RapidFuzz)

This project demonstrates my **data cleaning and analysis skills** using pandas, numpy, and rapidfuzz. It transforms a messy HR dataset into a clean format, calculates insights, and visualizes salary trends.

---

## What It Does

- Cleans up inconsistent "Status" labels (e.g. " Active ", "inactve", etc.) using fuzzy matching.
- Filters out rows with illogical salary-status relationships.
- Strips non-numeric characters from the "Salary" column and fills missing values with the average.
- Fills missing ages with the mean.
- Converts join dates to datetime and calculates years of experience.
- Compares average salary between active and inactive staff.
- Removes duplicate employee names, keeping the most recent entry.
- **Plots Salary vs Experience** to observe salary trends with respect to years of experience.

---

##  Why I Built This

I built this project to **demonstrate my ceiling ability** in:
- Data wrangling with real-world messiness
- Logical thinking when handling missing or inconsistent data
- Creating new insights from raw features
- Making visual observations through simple plots

---

## Tech Stack

- Python 3
- pandas
- numpy
- rapidfuzz
- matplotlib (used implicitly by pandas for plotting)


## Visualization

The project ends with a line plot showing **Salary vs Experience** to reveal patterns between employee experience and income:

```python
df.plot(x='Experience', y='Salary', kind='line')
