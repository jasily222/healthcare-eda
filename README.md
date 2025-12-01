# healthcare-eda
EDA — Medical Cost Personal Dataset

Exploratory Data Analysis on Medical Insurance Charges

Project Overview:

This project analyzes a dataset of 1,338 patients to understand the factors that influence medical insurance charges. Using Python (Pandas, NumPy, Seaborn, Matplotlib), I explored demographic, lifestyle, and health-related variables such as age, BMI, smoking status, and region to identify key cost drivers. The goal was to uncover insights that help insurance providers, healthcare analysts, or actuaries better understand patterns in healthcare spending.

Tools Used:

- Python (Pandas, NumPy)

- Seaborn / Matplotlib

- Jupyter Notebook

- GitHub

- Notion (for portfolio presentation)

Skills Demonstrated:

- Data cleaning

- Exploratory data analysis

- Visualization

- Feature evaluation

- Insights & storytelling

- Business interpretation

Findings:

1. Smoking is the strongest cost driver

Smokers had drastically higher charges than non-smokers, often more than 4x. This was visible in both the bar plots and correlation heatmap (where smoker status had the highest positive correlation with charges).
Business meaning: Smoking dramatically increases medical risk, which leads to much higher insurance payouts.

2. Age is positively correlated with charges

As individuals age, their medical insurance charges steadily increase. The relationship is almost linear, especially after age 30.
Business meaning: Healthcare costs grow as people age, so insurers must account for age-related risk trends.

3. BMI contributes to higher charges, especially for very high BMI

A scatterplot of BMI vs. charges showed that individuals with higher BMI tend to incur more costs, with a cluster of extremely high charges at BMIs above 30 (classified as obese).
Business meaning: Obesity is a known risk factor for chronic diseases, driving up long-term care costs.

4. Region does not significantly impact charges

Although costs vary slightly by region, the differences were relatively small compared to age and smoking.
Business meaning: Regional pricing differences exist, but lifestyle and health risk factors matter more.
