# Fake-News-Detection

##Machine Learning Web Application

Overview

This project is a machine learning web application that utilizes a Logistic Regression model for predictions. The application is built using Python, with a user-friendly interface powered by Streamlit.

Installation & Setup:

1. Download the Dataset
This project uses the Fake and Real News Dataset, which can be downloaded from Kaggle:
[Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

After downloading, extract the dataset and place the following files in the project directory:

True.csv (Contains true news articles)
Fake.csv (Contains fake news articles)

2. Install Dependencies: 

Ensure you have Python installed, then run:
pip install -r requirements.txt

3. Run the Application;

To start the Streamlit web app, use:
streamlit run app.py

Project Structure:
app.ipynb - Jupyter Notebook for model testing
lr_model.jb - Pretrained logistic regression model
vectorizer.jb - Feature extraction tool
requirements.txt - List of dependencies

Tech Stack
	•	Programming Language: Python
	•	Libraries:
	•	Scikit-learn (Machine Learning)
	•	Streamlit (Web UI)
	•	Pandas (Data Handling)


