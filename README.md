# Chatbot Application 🤖

A machine learning–based chatbot built using Python and TensorFlow.  
The chatbot is trained on custom intents data and can respond intelligently to user queries.

---

## 📌 Features
- Intent-based chatbot using deep learning
- Custom training data (JSON format)
- Pre-trained model included
- Easy deployment using Docker
- Ready for cloud platforms (Heroku-compatible)

---

## 🗂 Project Structure
```bash
chatbot-project/
│
├── app/
│   └── app.py                 # Main application entry point                               
│
├── model/
│   ├── chatbot_model.keras    # Trained model
│   ├── classes.pkl            # Label encoder / classes
│   └── words.pkl              # Tokenized vocabulary
│
├── data/
│   └── intents.json           # Training intents and responses
│
├── training/
│   └── training.py            # Model training script
│
├── docker/
│   └── Dockerfile             # Docker configuration
│
├── .gitignore
├── Procfile                   # For deployment 
├── requirements.txt
└── README.md
```
