# Movie Correlation Analysis Project
https://youtu.be/0Ehn3M-PZuw

An end-to-end Exploratory Data Analysis (EDA) project built with Python to investigate the relationships and correlations between various movie attributes (such as budget, gross revenue, company, rating, and genres).

# Tools & Libraries Used
* **Python** (Jupyter Notebook / VS Code)
* **Pandas & NumPy** (Data Cleaning & Manipulation)
* **Seaborn & Matplotlib** (Data Visualization & Correlation Analysis)

##
📊 Key Steps & Methodology
1. **Data Inspection & Cleaning**: 
   * Analyzed the dataset structure (comprising 6,820 rows)[span_0](start_span)[span_0](end_span).
   * Identified and documented missing values across critical financial columns (`budget`, `gross`) and categorical features[span_1](start_span)[span_1](end_span).
2. **Feature Engineering & Transformation**: 
   * Extracted release years from text dates for time-series and categorical grouping.
   * Converted object/categorical columns into numerical codes using `.cat.codes` to enable comprehensive correlation matrices.
3. **Exploratory Data Analysis (EDA) & Visualization**: 
   * Calculated financial metrics and grouped data by production companies to uncover top-grossing studios (e.g., Warner Bros., Universal Pictures).
   * Utilized advanced visualizations including Scatter Plots and Swarmplots to inspect distributions and relationships between budgets and gross earnings.
   * Handled complex exceptions such as `numeric_only=True` constraints during Pearson correlation computations.

# Key Insights
* Strong positive correlation observed between a movie's **budget** and its total **gross earnings**.
* Major production companies (such as Warner Bros. and Universal Pictures) dominate the top revenue tiers across the historical dataset.

---
*Created as part of a data analytics portfolio to demonstrate end-to-end Python data manipulation and visualization skills.*
