# Fake News Detector 🗞️

An ML-powered web application that classifies news articles as Real or Fake using TF-IDF Vectorization and Logistic Regression.

## 🚀 Features
- Paste any news article and instantly get a Real or Fake verdict
- Confidence score shown with every prediction (e.g. 94% Fake)
- Trained on 44,898 articles from the Kaggle Fake and Real News Dataset
- ~98% test accuracy

## 🛠️ Tech Stack
| Layer | Technology |
|---|---|
| Backend | Flask (Python) |
| ML Model | Logistic Regression + TF-IDF |
| Frontend | HTML, CSS, JavaScript |
| Libraries | scikit-learn, pandas, numpy |

## 📊 How It Works
1. User pastes a news article into the text box
2. Flask backend receives the text
3. TF-IDF Vectorizer converts text to numerical features
4. Logistic Regression model predicts Real or Fake
5. Confidence score returned and displayed on screen


## 📁 Project Structure
```
fake-news-detector/
├── app.py              # Flask backend
├── model/
│   ├── train.py        # Model training script
│   └── model.pkl       # Saved trained model
├── templates/
│   └── index.html      # Frontend UI
├── static/
│   └── style.css       # Styling
└── requirements.txt
```

## 📌 Status
🔨 Currently under active development
