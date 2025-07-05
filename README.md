<h1 align="center"> AI Quiz Generator with Google Classroom & Watsonx</h1>

<p align="center">
  🎓 Auto-generates MCQ quizzes using IBM Watsonx & Classroom topics  
  📊 Tracks student scores & levels (Beginner → Expert)  
  🔐 Built with Flask, secure via .env, deployable on Render
</p>

## 🔍 Key Features

- Google Classroom integration to fetch topics  
- IBM Watsonx to generate quizzes with answers  
- User score tracking and performance levels  
- Clean Flask + HTML frontend  
- Secure API handling via `.env`  
- Easy to deploy on Render

---

## 🧠 How It Works

1. Login with Google
2. Select a topic from your course
3. Get 5 AI-generated MCQs using Watsonx
4. Submit answers → Get score & level

---

## ⚙️ Tech Stack

| Tool        | Role                      |
|-------------|---------------------------|
| Flask       | Web backend               |
| Watsonx     | AI quiz generation        |
| Google API  | Classroom topic fetch     |
| JSON        | Store score history       |
| Render      | App deployment            |

---

## 🔐 Environment Setup

**.env file (Do not push to GitHub):**
```env
WATSONX_API_KEY=...
WATSONX_PROJECT_ID=...
WATSONX_MODEL_ID=...
GOOGLE_CLIENT_ID=...
GOOGLE_CLIENT_SECRET=...
FLASK_SECRET_KEY=...
