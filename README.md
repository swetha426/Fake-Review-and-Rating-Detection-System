# Fake-Review-and-Rating-Detection-System
The project effectively combines machine learning, natural language processing, and web development to deliver a robust and extensible fake review detection solution suitable for academic and industrial applications.


🧠 Technologies Used
.>Programming Language: Python
.>Web Framework: Flask
.>Machine Learning: Multinomial Naive Bayes
.>NLP Techniques: TF-IDF Vectorization
..Libraries:
  .>pandas
  .>scikit-learn
  .>flask
  .>pickle
.>Frontend: HTML (Jinja Templates)
.>Dataset Format: CSV

📂 Project Structure
fake review project/
│
├── app.py               # Flask web application
├── model.py             # Model training and saving
├── reviews.csv          # Dataset for training
├── model.pkl            # Trained ML model
├── vectorizer.pkl       # TF-IDF vectorizer
└── templates/
    └── index.html       # Web UI

## How to Run
1. Install required libraries
2. Run model.py
3. Run app.py
4. Open browser and go to http://127.0.0.1:5000
