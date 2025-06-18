📉 Customer Churn Prediction with NLP & Deep Learning
This project predicts customer churn using traditional machine learning and deep learning techniques. It integrates text processing techniques (like stemming, lemmatization, NER, POS tagging) and encodes structured customer data to train a predictive model.


📊 Dataset
Name: Churn_Modelling.csv

Source: (e.g., Kaggle Telco Dataset)

Features: Demographic info, credit score, balance, tenure, etc.

Target: Exited (1 = Churned, 0 = Retained)

🧠 Model Info
Type: ANN (Artificial Neural Network)

Framework: TensorFlow / Keras

Preprocessing:

Encoding: One-Hot + Label Encoding (pkl files)

Scaling: StandardScaler (scalar.pkl)

Saved Model: model2.h5

⚙️ How to Run
🔧 1. Install Requirements
bash
Copy
Edit
pip install -r requirements.txt

🚀 2. Run the App
bash
Copy
Edit
streamlit run app.py

📈 3. Make Predictions
Use the UI to input customer info and see the predicted churn status.

🧪 Example Use Case
A business analyst wants to assess if a customer is likely to leave based on account details.

Uploads structured data → app predicts probability of churn using trained neural network.


📦 Dependencies
See requirements.txt. Major ones include:

pandas

numpy

scikit-learn

tensorflow

streamlit

nltk


🧑‍💻 Author
Lavya Goel

GitHub: lavya30

Email: lavayagoel2006@gmail.com
