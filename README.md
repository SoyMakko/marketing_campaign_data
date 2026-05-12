# marketing campaign data
This project demonstrates a complete data cleaning and preprocessing workflow using Python, Pandas, and NumPy on a messy marketing campaign dataset.  

# Marketing Campaign Data Cleaning Project

## Overview

This project demonstrates a complete real-world data cleaning workflow using Python for a messy marketing campaign dataset. The objective is to transform inconsistent, duplicated, and error-prone raw data into a clean and analysis-ready dataset suitable for reporting, dashboarding, and business analysis.

The project focuses on practical preprocessing techniques commonly used by data analysts and business intelligence professionals when working with marketing or operational datasets.

---

## Project Objectives

* Clean inconsistent column headers
* Standardize categorical values
* Convert incorrect data types
* Handle mixed boolean values
* Parse inconsistent date formats
* Detect logical inconsistencies in campaign metrics
* Fix temporal data issues
* Identify and cap outliers
* Extract useful features from text columns

---

## Dataset Challenges

The dataset intentionally contains several common real-world data quality issues, including:

* Messy column names
* Currency symbols inside numeric fields
* Typographical errors in categorical variables
* Mixed representations of boolean values
* Inconsistent date formats
* Duplicate columns
* Impossible metric relationships
* Invalid campaign durations
* Extreme outlier values
* Embedded information inside text fields

---

## Data Cleaning Workflow

### Header Standardization

Column names were cleaned by removing spaces, converting text to lowercase, and replacing spaces with underscores to improve consistency and usability.

### Currency and Numeric Cleaning

The spend column contained symbols and formatting inconsistencies that were removed before converting the values into numeric format for analysis.

### Categorical Value Standardization

Misspelled marketing channels and inconsistent category labels were corrected to ensure accurate grouping and reporting.

### Boolean Normalization

Multiple representations of true and false values were mapped into consistent boolean values.

### Date Parsing

Mixed date formats were converted into proper datetime objects to enable time-based analysis and validation.

### Logical Integrity Checks

The workflow identified impossible situations such as:

* Clicks greater than impressions
* Campaign end dates occurring before start dates

Invalid campaign durations were corrected using a business rule assumption.

### Outlier Treatment

Extreme spending values were capped using the Interquartile Range (IQR) method to reduce distortion in future analysis.

### Feature Engineering

Additional features were extracted from campaign names to create more useful analytical dimensions such as seasonal categorization.

---

## Skills Demonstrated

This project highlights practical data analysis and preprocessing skills including:

* Data cleaning
* Data validation
* Data transformation
* Regular expressions
* Feature engineering
* Outlier handling
* Business rule enforcement
* Exploratory preprocessing
* Data quality assessment

---

## Tools and Libraries

* Python
* Pandas
* NumPy

---

## Business Relevance

Clean and reliable data is essential for:

* Marketing performance analysis
* KPI reporting
* Campaign optimization
* Dashboard accuracy
* Decision-making processes

This project simulates the preprocessing tasks analysts perform before generating insights or building visualizations.

---

## Future Improvements

Potential extensions for this project include:

* Automated validation reports
* Interactive dashboards
* ETL pipeline integration
* SQL database connectivity
* Advanced anomaly detection
* Automated preprocessing scripts
* Unit testing for validation rules

---

## Conclusion

This project showcases an end-to-end data cleaning workflow designed to prepare messy marketing campaign data for reliable analysis. It demonstrates both technical preprocessing skills and the importance of data quality in business analytics environments.

