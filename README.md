# Rubik’s Cube Solve Time Analytics – Data Engineering Project

This project was built as part of my hands-on learning journey into Data Engineering and Analytics.

After completing the Python for Everybody course and strengthening my basics in Statistics through Khan Academy, I wanted to apply these concepts in a practical cloud environment. Instead of only working on small scripts or notebooks, I decided to build a mini end-to-end data pipeline using Azure Databricks and PySpark.

The idea of the project is simple — analyze Rubik’s cube solve times and understand performance patterns such as daily trends, fastest solves, user rankings, and improvement over time. However, the main goal was not the dataset itself, but to understand how real-world data engineering workflows are designed and executed.

## What I worked on in this project

- Ingested raw CSV data into Azure Databricks using PySpark
- Performed data cleaning such as removing duplicates and filtering invalid records
- Applied basic statistical analysis including mean, median, standard deviation, and correlation
- Built leaderboard analytics using window functions
- Generated daily performance trend analysis and visualizations
- Stored processed data using Delta tables
- Structured the pipeline following the Medallion Architecture approach (Bronze → Silver → Gold)

## Technologies Used

- Python
- PySpark
- Azure Databricks
- Delta Lake
- SQL Analytics concepts

## Key Learnings

Through this project, I gained a better understanding of:

- How distributed data processing works using Spark
- How cloud-based data pipelines are organized
- The importance of structured data storage layers
- Applying statistics concepts to real datasets
- Designing analytics logic that can be automated and scaled

This project is one of my early steps toward building stronger skills in Data Engineering and Analytics. I plan to continue working on more advanced topics such as streaming pipelines, job automation, and performance optimization.
