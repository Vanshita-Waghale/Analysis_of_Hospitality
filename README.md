---

# Hospitality Data Analysis Project using Python

## Overview

This project was developed as part of the CodeBasics Data Analyst Bootcamp. The goal was to leverage data analytics techniques to analyze the performance and trends of AtliQ Grands, a prestigious 5-star hotel chain in India. The project utilizes exploratory data analysis (EDA) to extract insights that could assist AtliQ Grands in making data-driven decisions to enhance business operations and improve profitability.

AtliQ Grands operates across four major cities with a network of seven properties, offering guests different room categories such as Elite, Premium, Presidential, and Standard. The hotel chain also utilizes multiple booking platforms to increase accessibility and attract diverse clientele. Through this project, various aspects of hotel data such as booking trends, room occupancy, and revenue generation were analyzed.

## Project Scope

The project focused on the following key objectives:

* Analyzing booking trends over time using date-related data.
* Understanding property-specific performance and trends through various metrics.
* Examining the popularity of different room categories.
* Exploring the correlation between booking platform and room occupancy.

### Key Datasets:

* **dim\_date**: Date-related information such as week numbers and day types (weekend and weekday).
* **dim\_hotels**: Information about the hotels, such as property ID, name, category, and cities.
* **dim\_rooms**: Information about room categories and IDs.
* **fact\_aggregated\_bookings**: Contains data about property ID, check-in dates, room categories, and bookings, which helped in calculating key metrics related to bookings and occupancy.

## Tools and Technologies Used:

* **Python**: For data analysis and visualization.
* **Pandas & NumPy**: For data manipulation and numerical operations.
* **Matplotlib & Seaborn**: For creating visualizations and insights.
* **Jupyter Notebooks**: For interactive analysis and documentation.

## Steps Taken in the Project:

1. **Data Preprocessing**: Cleaning and formatting the raw data to make it suitable for analysis.
2. **Exploratory Data Analysis (EDA)**:

   * Statistical analysis of key variables such as booking frequency, revenue, and occupancy rate.
   * Visualizations to identify trends, correlations, and patterns.
3. **Data Insights**: Deriving actionable insights for the hotel chain’s business strategies and performance improvement.

## Installation

To run this project locally, follow the steps below:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Analysis_of_Hospitality.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Analysis_of_Hospitality
   ```

3. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv env
   ```

4. Activate the virtual environment:

   * On Windows:

     ```bash
     .\env\Scripts\activate
     ```
   * On MacOS/Linux:

     ```bash
     source env/bin/activate
     ```

5. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

6. Open the project in a Jupyter notebook:

   ```bash
   jupyter notebook
   ```

## Conclusion

This project provides valuable insights into the performance of AtliQ Grands, enabling data-driven decisions that can improve the hotel chain's revenue, customer satisfaction, and overall business performance.

## Acknowledgments

* CodeBasics Data Analyst Bootcamp for providing the opportunity to work on this project.
* The AtliQ Grands team for the dataset, which was pivotal for this analysis.

---
