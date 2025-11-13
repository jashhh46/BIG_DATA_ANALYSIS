📘 Social Media Addiction Analysis using PySpark

This project performs Big Data Analytics on a dataset of student social media usage.
Using PySpark, the project explores relationships between screen time, academic performance, mental health, sleep patterns, and overall addiction scores.

The goal is to derive actionable insights from real-world behavioral data using scalable data-processing techniques.

📂 Project Overview

This project covers:

🔹 Data ingestion using PySpark

🔹 Data cleaning & preprocessing

🔹 Exploratory Data Analysis (EDA)

🔹 Transformations & feature engineering

🔹 Statistical insights from aggregated metrics

🔹 Visualizations (Matplotlib)

🔹 Data-driven conclusions

It is designed as a beginner to intermediate PySpark project suitable for:

Academic submissions

Big Data Analytics coursework

Portfolio display for internships & jobs

🧠 Objective

To analyze how social media usage influences:

Academic performance

Sleep duration

Mental health

Interpersonal conflicts

Addiction levels

Using PySpark to handle data at scale and extract meaningful patterns.

🛠️ Technologies Used
Tool / Library	Purpose
PySpark	Data processing, transformations, aggregations
Python	General scripting
Pandas	Visualizations & summary tables
Matplotlib	Graph plots
Jupyter Notebook	Experimentation & reporting

📁 Folder Structure (Recommended)
/project-root
│── data/
│   └── Students Social Media Addiction.csv
│
│── notebooks/
│   └── social_media_addiction_analysis.ipynb
│
│── scripts/
│   └── pyspark_analysis.py
│
│── visuals/
│   └── plots.png (and other charts)
│
│── README.md
│── requirements.txt

📊 Key Analyses Performed
✔️ 1. Daily Usage Pattern Analysis

Grouped by academic level, gender, and country.

✔️ 2. Sleep vs Social Media Usage Correlation

Identifies impact on sleep duration.

✔️ 3. Mental Health vs Screen Time

Finds patterns between usage and well-being.

✔️ 4. Platform Popularity Analysis

Instagram, TikTok, Twitter, YouTube, Facebook trends.

✔️ 5. Academic Performance Impact

Distribution of “Yes/No” responses.

✔️ 6. Addicted Score Distribution

Binning into Low, Medium, High addiction groups.

✔️ 7. Conflicts Due to Social Media

Analyzed using aggregated conflict indicators.

✔️ 8. Country-level Behavioral Insights

Comparing usage and addiction across regions.

📈 Visualizations Included

Daily usage scatter plots

Platform usage bar charts

Addicted Score histogram

Mental health trend plot

Sleep hour comparison

All visualizations are generated using matplotlib after converting PySpark DataFrames → Pandas.

🚀 How to Run
1. Install requirements
pip install pyspark pandas matplotlib

2. Start your notebook
jupyter notebook

3. Load dataset

Ensure the CSV is placed in the data/ folder and update the path in your notebook if needed.

🧾 Dataset Description
Column	Meaning
Age	Student’s age
Gender	Male/Female
Academic_Level	High School / UG / PG
Avg_Daily_Usage_Hours	Screen time per day
Most_Used_Platform	Instagram/TikTok/etc
Affects_Academic_Performance	Yes/No
Sleep_Hours_Per_Night	Average sleep
Mental_Health_Score	1–10 rating
Relationship_Status	Single / In Relationship
Conflicts_Over_Social_Media	Count
Addicted_Score	Behavioral addiction score
🧩 Insights Discovered (Examples)

Higher daily usage correlates with lower sleep hours.

TikTok & Instagram users show higher addiction scores.

Students who use social media >5 hours/day show higher conflict rates.

Academic performance dips significantly for high-usage groups.

Mental health scores drop as addiction score increases.

(Actual insights depend on your dataset’s output.)

🏁 Conclusion

This project demonstrates how PySpark can be used to handle and analyze behavioral datasets at scale.
The findings highlight the significant influence of social media usage on sleep, mental health, and academic performance.

This repository serves as a strong Big Data portfolio project for students, developers, and data enthusiasts.
