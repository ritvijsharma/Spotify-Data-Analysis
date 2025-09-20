# Spotify Quarterly Data Analysis using SQL

## 📖 Overview

This project provides a comprehensive analysis of Spotify's quarterly financial and user data. It serves as a practical demonstration of data analysis using **SQL** within a **Python** environment, leveraging libraries like Pandas and Matplotlib.

The analysis begins by loading raw data from a CSV file, cleaning it, and then ingesting it into a **SQLite** database. From there, a series of SQL queries are executed to explore key business metrics, including revenue trends, user growth, profitability, and cost structure. The project also demonstrates advanced SQL techniques such as window functions for calculating year-over-year growth and `UNION` clauses for segment analysis.

Finally, the insights derived from the SQL queries are visualized using Matplotlib to illustrate trends over time.

---

## 💾 Dataset

The data used for this analysis is from the `Spotify Quarterly.csv` file.

This dataset was sourced from Kaggle and is titled **[Spotify Revenue, Expenses, and its Premium Users](https://www.kaggle.com/datasets/mauryansshivam/spotify-revenue-expenses-and-its-premium-users?resource=download)**. It contains quarterly key performance indicators for Spotify, including:
* Revenue figures (Total, Premium, Ad-Supported)
* User metrics (MAUs, Premium vs. Ad-supported)
* Profitability metrics (Gross Profit, Premium ARPU)
* Operating costs (Sales & Marketing, R&D, etc.)

---

## 📊 Analysis Highlights

* **Data Loading and Preparation**: Cleans and prepares Spotify's quarterly data using Pandas, handling missing values and ensuring correct data types.
* **Database Creation**: Creates a SQLite database and ingests the cleaned data, making it accessible for SQL querying.
* **Revenue & User Growth Analysis**: Queries the database to track trends in total revenue, premium vs. ad-supported revenue, Monthly Active Users (MAUs), and premium subscriber growth.
* **Advanced Financial Metrics**: Utilizes SQL window functions (`LAG()`) to calculate year-over-year (YoY) growth rates for revenue and MAUs.
* **Business Segment Comparison**: Compares the performance of Spotify's Premium and Ad-Supported business segments, analyzing average revenue, profit, and ARPU for each.
* **Cost Structure Analysis**: Breaks down Spotify's cost of revenue, sales & marketing, R&D, and administrative costs as a percentage of total revenue.
* **Data Visualization**: Creates plots to visualize key trends in revenue, user growth, and profitability over time.

***Note on the Notebook Content***: The original notebook contains a section that briefly switches to analyzing a European soccer database. This appears to be a remnant from a different project. The SQL syntax in this section has been corrected for completeness, but the primary focus of this project remains the Spotify financial data.

---

## 🛠️ Technologies Used

* **Language**: Python 3
* **Libraries**:
    * Pandas
    * NumPy
    * Matplotlib
    * Seaborn
    * SQLite3
* **Environment**: Jupyter Notebook

---