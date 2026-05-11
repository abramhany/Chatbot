# Iteru - AI-Powered Travel Recommendation Chatbot

An NLP chatbot that understands user travel preferences and recommends personalized destinations.

---

## What It Does
- Understands natural language travel queries
- Classifies user intent (destination search, activity recommendations)
- Provides personalized responses using a custom bag-of-words + deep learning pipeline

## Tech Stack
- **NLP:** Custom tokenization, lemmatization (NLTK), bag-of-words encoding
- **ML:** TensorFlow/Keras intent classifier + KNN recommendation engine
- **Backend:** Flask API
- **Deployment:** Docker + Railway (serverless)
- **Team:** Built as graduation project (Team Leader, AI Engineer)
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
│   ├── classes.pkl            # Label encoder/classes
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
## What I Learned
- Production deployment patterns (Docker, Flask, Railway)
- Managing ML model lifecycle (training → serialization → serving)
- Building conversational AI with limited training data

## Future Improvements
- Add conversation memory/context
- Integrate with real travel APIs
- Migrate to FastAPI for async support
