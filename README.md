📊 CORD-19 Data Exploration & Streamlit App
📘 Assignment Overview

This assignment demonstrates a basic data analysis workflow using the CORD-19 research dataset
.
It covers loading, cleaning, analyzing, and visualizing research paper metadata, and concludes with building a simple Streamlit application to display the findings.

The goal is to practice fundamental data analysis and presentation skills appropriate for beginners.

🎯 Learning Objectives

By completing this assignment, you will:

✅ Load and explore a real-world dataset

✅ Apply basic data cleaning techniques

✅ Create meaningful visualizations

✅ Build a simple interactive web application

✅ Present insights clearly and effectively

📂 Dataset Information

We use the metadata.csv file from the CORD-19 dataset, which contains information on COVID-19 research papers, including:

📝 Paper titles and abstracts

📅 Publication dates

👨‍🔬 Authors and journals

🌐 Source information


Dataset link: CORD-19 Research Challenge (Kaggle)

🛠️ Required Tools

Make sure you have the following installed:

Python 3.7+

pandas
 → Data manipulation

matplotlib
 / seaborn
 → Visualization

Streamlit
 → Web application framework

Jupyter Notebook
 (optional) → Interactive exploration

Installation
pip install pandas matplotlib seaborn streamlit

🚀 Project Structure
Frameworks_Assignment/
│
├── notebooks/
│   └── analysis.ipynb       # Data loading, cleaning, exploration, visualization
│
├── app.py                   # Streamlit application
├── metadata.csv             # Dataset (or sample metadata file)
├── README.md                # Project documentation
└── requirements.txt         # Python dependencies

📊 Features Implemented

Load and explore dataset using Pandas

Handle missing data and prepare new features

Generate visualizations:

Publications by year

Top publishing journals

Word frequency in titles

Word cloud of paper titles

Interactive Streamlit app:

Year range filter

Publication trend plot

Top journals bar chart

Sample data preview

▶️ Running the Project
1. Jupyter Notebook

Open and run the notebook:

jupyter notebook notebooks/analysis.ipynb

2. Streamlit Application

Run the app from the project root:

streamlit run app.py


Then open the link provided (default: http://localhost:8501
) in your browser.