#🧠 Twitter_Sentiment_Analysis

## 📖 Introduction
This project is an end-to-end Machine Learning and Natural Language Processing (NLP) application designed to analyze and classify the sentiment of tweets. The model predicts whether a given text is **Positive**, **Negative**, or **Neutral**. 

The project covers the full NLP lifecycle: 
1. **Data Extraction:** Automatically downloading data via Kagglehub.
2. **Text Preprocessing:** Cleaning URLs, HTML tags, mentions, and stopwords using NLTK and Regex.
3. **Feature Extraction:** Converting text to numerical data using **TF-IDF**.
4. **Model Training:** Training and tuning `LinearSVC` and `Logistic Regression` models to achieve high accuracy.
5. **Deployment:** Building an interactive web interface where users can type a sentence and instantly see the predicted sentiment.

## 🛠️ Technologies
The following technologies and frameworks were used to build this project:
* **Programming Language:** Python 3.x
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Natural Language Processing (NLP):** NLTK (Natural Language Toolkit), Regular Expressions (Regex)
* **Machine Learning:** Scikit-Learn (LinearSVC, Logistic Regression, TfidfVectorizer, GridSearchCV)
* **Data Visualization:** Matplotlib, Seaborn
* **Web Framework & Deployment:** Streamlit, Pyngrok
* **Data Sourcing:** Kagglehub

## 📦 Requirements
To run this project on your local machine, you need to have Python installed along with the following libraries. 

You can install all required dependencies by running the following command in your terminal:

!pip install pandas numpy scikit-learn nltk streamlit pyngrok matplotlib seaborn kagglehub
(Note: The application also requires downloading the NLTK stopwords corpus, which the script handles automatically)

##🚀 How to Run the Project Locally
1. **Clone the repository:**

git clone [https://github.com/ibrahimadel-g/Twitter_Sentiment_Analysis-.git](https://github.com/ibrahimadel-g/Twitter_Sentiment_Analysis-.git)
cd Twitter_Sentiment_Analysis-

2. **Run the Streamlit app:**
   
   streamlit run app.py
3. **Access the Web App:**
Open your browser and go to http://localhost:8501 to interact with the sentiment analyzer.
