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

| Frontend | Backend | AI Models |
|----------|---------|-----------|
| React.js | Flask   | HuggingFace Transformers (BLIP) |
| CSS      | TensorFlow/Keras | Custom-trained mood prediction model |

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

---

## 🧑‍💻 Author

**Rex Maina**  
[GitHub](https://github.com/RexMaina) • [LinkedIn](https://www.linkedin.com/in/rex-maina-7b7474158/)  

---

## ⭐️ Show your support

If you liked this project:
- ⭐️ Star it on GitHub
- 🐛 Submit issues or PRs
- 💬 Share with your friends


