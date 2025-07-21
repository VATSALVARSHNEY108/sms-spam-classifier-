# 📩 SMS Spam Classifier using Naive Bayes

A simple machine learning project to detect whether an SMS message is **spam** or **ham (not spam)** using a **Multinomial Naive Bayes classifier**.

---

## 🚀 Features
- Classifies text messages as **spam** or **ham**
- Uses **TF-IDF vectorization** for text processing
- Trained using the **Multinomial Naive Bayes** algorithm
- Includes a simple **Streamlit app** for demo
- Model and vectorizer saved using **Pickle**

---

## 🧠 Model Used
- **Multinomial Naive Bayes**  
  Best suited for text classification problems.
- **TF-IDF Vectorizer**  
  Converts SMS text into a numerical form that the model can understand.

---

## 📁 Project Structure

├── project/ # (Optional folder for future use)
├── app.py # Streamlit app for UI
├── main.py # Backend logic and integration
├── sms-spam-classifier.ipynb # Jupyter notebook for training and EDA
├── spam_model.pkl # Trained Naive Bayes model
├── train_and_save_model.py # Script to train and save the model
├── vectorizer.pkl # Saved TF-IDF vectorizer
├── README.md # This file

yaml
Copy
Edit

---

## 🧪 Installation & Usage

### 1. Clone the repo
```bash
git clone https://github.com/your-username/sms-spam-classifier.git
cd sms-spam-classifier
2. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run the app
bash
Copy
Edit
streamlit run app.py
📊 Sample Dataset Used
Dataset: SMS Spam Collection Dataset

Format: Each line has a label (ham or spam) and a message.

🛠 Tech Stack
Python

Scikit-learn

Pandas, NumPy

Streamlit (for UI)

Pickle (for model saving)

✨ Screenshots
(Insert screenshots of your app UI here, like message input/output)

🧠 Future Improvements
Add more NLP preprocessing steps

Use more advanced models like SVM or BERT

Deploy as a web service (Flask/FastAPI)

👨‍💻 Author
Your Name
