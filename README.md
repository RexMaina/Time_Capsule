# 📦 Time Capsule

> **AI-Powered Memory Keeper** — Capture moments, generate stories, predict your future, and preserve memories in your own digital time capsule.

---

## ✨ Features

### 🧠 AI Storytelling
Upload a photo and let our AI model craft a meaningful story based on the image — with different emotional tones like `happy`, `sad`, or `mysterious`.

### 🎭 Mood-Based Text Prediction
Input any sentence or phrase and let the AI predict the underlying mood: `joy`, `anger`, `fear`, `surprise`, etc.

### 🤖 Avatar Generation
Generate a personalized AI avatar based on your name and mood. Great for profile personalization.

### 🔮 Future Self Prediction
Fun AI-based prediction for where you might be in 5, 10, or 20 years.

### 👥 Friend Memories
Collaborative memory sharing. Save and view memories shared between friends.

---

## 🧰 Tech Stack

## 🛠 Built With
## 🛠 Built With

### Frontend
- ![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
- ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

### Backend
- ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
- ![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)
- ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
- ![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)

### AI & Machine Learning
- ![HuggingFace](https://img.shields.io/badge/🤗_HuggingFace_Transformers-FFD21F?logo=huggingface&logoColor=black) (BLIP model for story generation)
- ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) (Age progression model)
- ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white) (Mood prediction)
- ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white) (Image processing)
- Custom AI Models:
  - Age Progression Model (CNN-based)
  - Mood Prediction Classifier (LSTM-based)
  - Story Generation (BLIP fine-tuned)

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/RexMaina/Time_Capsule.git
cd Time_Capsule
```

### 2. Install frontend dependencies
```bash
cd frontend
npm install
npm start
```

### 3. Setup backend (Python & Flask)
```bash
cd backend
python -m venv venv
venv\Scripts\activate  # Windows
pip install -r requirements.txt
python story_generator.py  # Or mood_predictor.py
```

---

## 🧪 Sample Routes (Backend)

### `/generate_story`
- **Method**: POST
- **Payload**: `FormData` with `image` and `mood`
- **Returns**: AI-generated story based on image & mood

### `/predict`
- **Method**: POST
- **Payload**: `{ text: "I feel good today" }`
- **Returns**: Predicted mood + confidence

---


## 🧠 AI Models Used

- **Custom TensorFlow model** trained on emotion-labeled text for mood classification

---

## 🗂 Folder Structure

```bash
Time_Capsule/
├── backend/              # Flask API with AI models
├── frontend/             # React frontend
│   ├── src/pages/        # All feature pages
│   ├── src/components/   # Shared components
│   └── ...
└── README.md
```

## ⭐️ Show your support

If you liked this project:
- ⭐️ Star it on GitHub
- 🐛 Submit issues or PRs
- 💬 Share with your friends


## 🧑‍💻 Author

<div align="center">
  <a href="mailto:rexwanyeki@gmail.com">📧 Email</a> | 
  <a href="https://linkedin.com/in/rex-maina-7b7474158">🌐 LinkedIn</a> | 
  <a href="tel:+254792615071">📞 +254 792 615 071</a>
</div>

<div align="center">
  <sub>Built with ♥ by Rex Maina Wanyeki</sub>
</div>


