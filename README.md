📊 CORD-19 Data Explorer

An interactive data exploration project built with Python, pandas, and Streamlit, using the CORD-19 metadata dataset.
The goal is to practice fundamental data analysis, visualization, and web app development skills.

📌 Project Overview

This project walks through the full workflow of working with a real-world dataset:

Data Loading and Exploration

Load metadata.csv from the CORD-19 dataset

Explore data structure, missing values, and column types

Data Cleaning and Preparation

Handle missing values

Convert publication dates to datetime

Create new columns (e.g., year, abstract word count)

Data Analysis and Visualization

Count papers by year

Identify top publishing journals

Plot publication trends and journal contributions

Interactive Streamlit App

A slider to filter publications by year

A table preview of selected research papers

Bar chart showing number of publications per year

Documentation and Reflection

Code is fully commented for clarity

Includes a short reflection on challenges and learning outcomes

📂 Dataset Information

The project uses the CORD-19 metadata.csv file, which includes:

Research paper titles and abstracts

Publication dates

Authors and journals

Source information

📥 Dataset can be downloaded from Kaggle:
👉 CORD-19 Research Challenge

🛠️ Tools & Libraries

Python 3.7+

pandas
 – data manipulation

matplotlib
 – visualization

Streamlit
 – interactive web app

(Optional) Jupyter Notebook – exploration and documentation

🚀 Installation & Setup

Clone this repository or download the project files.

Install dependencies:

pip install pandas matplotlib streamlit


Run the Streamlit app:

streamlit run app.py


Open the app in your browser at http://localhost:8501
.

📊 Example Outputs

Publications Over Time – bar chart showing research activity by year

Top Journals – which journals published the most COVID-19 research

Interactive Filtering – explore specific year ranges with a slider

📝 Reflection

During this project I learned how to:

Work with a real-world dataset and handle missing values

Perform basic data cleaning and transformations

Generate insightful visualizations of publication trends

Build an interactive web app with Streamlit

Document and reflect on my workflow for clarity and reproducibility

Challenges included handling the large dataset size, cleaning incomplete data, and running Streamlit inside a Jupyter environment.

📌 Evaluation Criteria

✅ Complete implementation (data loading, cleaning, analysis, Streamlit app)

✅ Clear and well-commented code

✅ Appropriate visualizations

✅ Functional and interactive Streamlit application

✨ Built with Python & Streamlit to explore the global COVID-19 research effort.