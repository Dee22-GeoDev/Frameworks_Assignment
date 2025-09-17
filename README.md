📊 CORD-19 Data Explorer

An interactive project for exploring the CORD-19 metadata dataset, built with Python, pandas, matplotlib, and Streamlit.
The goal: practice real-world data analysis, visualization, and interactive app development while uncovering insights from COVID-19 research.

🔎 Project Highlights

This project takes you through the end-to-end workflow of working with real-world data:

1. Data Loading & Exploration

Load metadata.csv from the CORD-19 dataset

Inspect data structure, column types, and missing values

2. Data Cleaning & Preparation

Handle missing values

Convert publication dates to datetime

Create new features (e.g., publication year, abstract word count)

3. Data Analysis & Visualization

📈 Track publication trends over time

🏛️ Identify top publishing journals

📊 Visualize research contributions with bar charts

4. Interactive Streamlit App

🎚️ Year range slider to filter publications

📑 Table preview of selected research papers

📊 Dynamic charts showing publication activity

📂 Dataset

This project uses the CORD-19 metadata.csv file, which contains:

Titles, abstracts, authors, and journals

Publication dates

Source information

👉 Dataset available on Kaggle – CORD-19 Research Challenge
.

🛠️ Tools & Libraries

Python 3.7+

pandas – data manipulation

matplotlib – visualization

Streamlit – interactive web apps

(Optional) Jupyter Notebook – exploration & documentation

🚀 Quick Start

Clone or download this repository

Install dependencies:

pip install pandas matplotlib streamlit


Run the app:

streamlit run app.py


Open in your browser: http://localhost:8501

📊 Example Outputs

Publications Over Time – bar chart of research activity by year

Top Journals – ranking of leading publishers

Interactive Filtering – focus on specific year ranges with a slider

📝 Reflection

Through this project, I learned to:
✔️ Work with large, messy real-world datasets
✔️ Clean and transform data effectively
✔️ Build meaningful visualizations to uncover trends
✔️ Develop an interactive web app with Streamlit

Challenges faced:

Handling incomplete or inconsistent records

Processing large datasets efficiently

Running Streamlit within a Jupyter environment

✅ Evaluation Checklist

 Complete pipeline: load → clean → analyze → visualize → deploy

 Clear, well-commented code

 Insightful visualizations

 Functional and interactive Streamlit app

✨ Built with Python & Streamlit to explore the global COVID-19 research effort.