📦 Innomatics Research Labs – Advanced GenAI Internship Hackathon
📌 Project Overview

This project is part of the Innomatics Research Labs – Advanced GenAI Internship Entrance Test.
The objective of this hackathon is to simulate a real-world data integration and analysis task by working with datasets in multiple formats (CSV, JSON, SQL) and deriving insights through data analysis.

📂 Datasets Used

The project uses the following datasets:

orders.csv

Contains transactional order-level data

Includes order ID, user ID, restaurant ID, order date, and total amount

users.json

Contains user master data

Includes user details such as city and membership type (Gold / Regular)

restaurants.sql

Contains restaurant master data

Includes restaurant name, cuisine type, and rating

🛠️ Tools & Technologies

Python

Pandas

SQLite

Google Colab

GitHub

🔗 Data Integration Process

Loaded CSV data using Pandas

Loaded JSON data using Pandas

Loaded SQL data using SQLite in-memory database

Merged datasets using LEFT JOIN to retain all order records

Created a final consolidated dataset for analysis

📁 Final Dataset

File name: final_food_delivery_dataset.csv

Contains:

Order details

User information

Restaurant information

This dataset was used as the single source of truth for all analysis and questions.

📊 Analysis Performed

The final dataset was analyzed to answer:

Revenue trends by city and membership type

Cuisine-wise performance

User spending behavior

Rating-based revenue distribution

Order trends across quarters

Both MCQs and numerical questions were answered based strictly on the final merged dataset.

📌 Key Concepts Applied

Data loading from multiple formats

Data cleaning and preprocessing

Dataset merging using primary and foreign keys

GroupBy aggregations

Descriptive statistics

Real-world data analysis logic

📄 Files in Repository

Innomatics_Hackathon.ipynb – Jupyter Notebook containing complete implementation

final_food_delivery_dataset.csv – Final merged dataset

README.md – Project documentation

✅ Conclusion

This hackathon provided hands-on experience in handling real-world datasets, combining data from different sources, and deriving meaningful insights using Python and Pandas. It strengthened practical data analysis and problem-solving skills.
