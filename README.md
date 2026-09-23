# YuvaIntern-Week-2
This report explores data visualization using R and ggplot2. The Iris dataset is analyzed through charts to identify species differences, relationships, distributions, and variations in flower measurements.
# Data Visualization and Insight Communication using R

# Project Overview

This project is part of the **Yuva Intern – Week 2 Internship Task**. The project focuses on **Data Visualization and Insight Communication using R**. The main objective is to analyze data and communicate meaningful insights through clear and effective visualizations.

The **Iris dataset**, available in R's built-in `datasets` package, is used for analysis. It contains 150 observations from three iris species: **Setosa, Versicolor, and Virginica**. The dataset includes measurements such as sepal length, sepal width, petal length, and petal width.

# Objectives

* Understand and inspect the Iris dataset.
* Perform basic data quality checks.
* Create meaningful visualizations using R.
* Identify trends, relationships, distributions, and variations.
* Communicate analytical findings in a simple and understandable way.

# Technologies Used

* **R Programming**
* **ggplot2**
* **Iris Dataset**
* R `datasets` package

# Visualizations

The project includes five different visualizations:

1. **Bar Chart** – Compares average sepal length across species.
2. **Scatter Plot** – Shows the relationship between petal length and petal width.
3. **Histogram** – Displays the distribution of petal length.
4. **Box Plot** – Compares sepal width variation between species.
5. **Line Chart** – Shows petal length across observations in dataset order.

# Key Insights

The analysis shows that petal measurements provide clear differences between the three iris species. Setosa has considerably smaller petal measurements, while Virginica generally has larger petal dimensions. Petal length and petal width also show a strong positive relationship. Versicolor and Virginica show some overlap, indicating that one measurement alone may not always distinguish species.

# Project Structure

```text
Data-Visualization-R/
│
├── README.md
├── R/
│   └── visualization.R
├── Dataset/
│   └── iris.csv
├── Visualizations/
│   ├── bar_chart.png
│   ├── scatter_plot.png
│   ├── histogram.png
│   ├── box_plot.png
│   └── line_chart.png
└── Report/
    └── Week_2_Report.pdf
```

# How to Run

1. Install **R** and **RStudio**.
2. Install the `ggplot2` package if it is not already installed.
3. Open the R script.
4. Run the code to generate the visualizations.
5. View the generated charts and analyze the insights.

```r
install.packages("ggplot2")
library(ggplot2)

data(iris)
```

# Conclusion

This project demonstrates how R and ggplot2 can transform a structured dataset into meaningful visual insights. It also highlights the importance of selecting the appropriate visualization based on the analytical question and communicating results clearly.

# Internship Task

**Program:** Yuva Intern – Virtual Internship
**Task:** Week 2 – Data Visualization and Insight Communication using R
**Dataset:** Iris Dataset
**Visualization Library:** ggplot2
