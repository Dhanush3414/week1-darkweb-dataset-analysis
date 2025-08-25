# Week 1 Dark Web Dataset Analysis

Project Overview
This project analyzes a dark web dataset to explore cybercrime activities such as credential leaks and illicit service advertisements.
The notebook applies exploratory data analysis (EDA) techniques using Python in Google Colab to uncover insights and visualize patterns in the dataset.

Dataset
File: agora.csv
Description: Contains scraped data from a dark web marketplace/forum.
Key Columns:
Category → type of product/service (e.g., credentials, drugs, services)
Vendor → seller/advertiser information
Item → description of the listed item/service
Price → listed price (if available)
The dataset provides a foundation for studying cybersecurity threats and underground marketplace activity.

Features / Analysis
Data cleaning and preprocessing
Frequency analysis of credential leaks and service advertisements
Visualization of patterns (bar charts, distributions, word clouds)
Insights into the dark web ecosystem and risks in cybersecurity

Technologies Used
Python
Google Colab / Jupyter Notebook
Libraries:
pandas
numpy
matplotlib
seaborn
(optional) wordcloud, nltk, scikit-learn

Installation / Setup
Clone the repository:
git clone https://github.com/your-username/darkweb-dataset-analysis.git
cd darkweb-dataset-analysis

Install dependencies:
pip install -r requirements.txt

Open the notebook:
jupyter notebook week1_project.ipynb

Results / Insights
Identified most frequent categories in dark web listings.
Found high frequency of credential leaks compared to service advertisements.
Visualized vendor activity and item distribution trends.

Disclaimer
This project is for educational and research purposes only.
The dataset has been used solely for data analysis practice and does not endorse or promote illegal activities.
