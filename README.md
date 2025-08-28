# 🎓 AI Learning Companion  

An **AI-powered inclusive learning platform** designed for children with learning disabilities (dyslexia, ADHD, autism, dyscalculia).  
Built for [Hackathon Name] 2025 under the **Education & Skilling + Accessibility & Inclusion** theme.  

---

## 🚩 Problem Statement  
Children with learning disabilities often struggle in traditional classrooms. Existing tools are limited—most focus on only one disability, skill, or language (mainly English). This creates a gap in **personalized, inclusive, and multilingual learning solutions**, especially in regions like India.  

---

## 💡 Our Solution  
The **AI Learning Companion** is a digital tutor that adapts to each child’s needs, making learning more accessible, fun, and inclusive.  

### Key Features  
- 🧠 **Multi-disability support** (dyslexia, ADHD, autism, dyscalculia)  
- 🎙️ **Speech-to-text & text-to-speech** using Azure Cognitive Services  
- 🎮 **Gamified, interactive lessons** for reading, writing, and math  
- 🌍 **Multilingual content** (support for Indian regional languages)  
- 😊 **Emotion-aware AI** that adjusts pace/content if frustration is detected  
- 📊 **Parent/Teacher dashboard** with progress insights and recommendations  

---

## 🛠️ Tech Stack  
- **Frontend:** React.js, Tailwind CSS  
- **Backend:** Node.js, Express  
- **Database:** Firebase Firestore / Azure Cosmos DB  
- **AI Services:**  
  - Azure Cognitive Services (Speech-to-Text, Text-to-Speech, Sentiment/Face)  
  - Azure OpenAI Service (text simplification, quiz generation)  
  - Hugging Face NLP models  
- **Deployment:** Vercel / Azure App Service  

---

## ☁️ How Azure is Used  
- **Azure Cognitive Services** → speech-to-text, text-to-speech, sentiment analysis  
- **Azure OpenAI Service** → adaptive learning content generation  
- **Azure Cosmos DB** → scalable learning data storage  
- **Azure App Service** → backend hosting and APIs  

---

## 📂 Repo Structure  
ai-learning-companion/
│── README.md
│── package.json
│── tsconfig.json
│── public/
│ └── index.html
│── src/
│ ├── App.tsx
│ ├── index.tsx
│ ├── components/
│ │ ├── Lesson.tsx
│ │ ├── SpeechInput.tsx
│ │ └── ProgressDashboard.tsx
│ ├── services/
│ │ ├── azureSpeech.ts
│ │ └── firebase.ts
│ └── styles/
│ └── global.css


---

## ▶️ Getting Started  

1. **Clone the repo**  
   ```bash
   git clone https://github.com/<your-team>/ai-learning-companion.git
   cd ai-learning-companion


Install dependencies

npm install


Add Firebase config → src/services/firebase.ts

Add Azure keys → src/services/azureSpeech.ts

Run locally

npm start

🧩 Demo (Prototype Scope for Hackathon)

Speech-to-text input from microphone

Text-to-speech lesson playback

Basic quiz module with progress tracking

Firebase backend for storing child progress

(Screenshots or demo link can be added here)

🔮 Future Roadmap
Phase 1 – Prototype (Hackathon)

✅ Speech-to-text and text-to-speech integration

✅ Basic reading/quiz modules with progress tracking

✅ Simple React frontend for accessibility

Phase 2 – Enhanced Features

🎮 Gamification: badges, rewards, and interactive exercises

🌍 Multilingual support for Indian regional languages

📊 Teacher/Parent dashboards with personalized insights

Phase 3 – AI Personalization

🤖 Adaptive AI tutor that adjusts difficulty dynamically

😊 Emotion detection via voice/facial sentiment

🧩 Multi-disability modes with custom learning paths

Phase 4 – Scaling & Impact

☁️ Offline support for low-internet regions

🏫 School + NGO partnerships for real-world deployment

📱 React Native mobile app

🌐 Community-driven content creation

👨‍👩‍👧 Team

Shravya N Bhat – [Role]

Trishal Hegde – [Role]

Vaishnavi Ghogre – [Role]

Vishruth HR – [Role]

📜 License

This project is open-sourced under the MIT License.

🚀 Our vision: To become the first truly inclusive, multilingual, multi-disability AI tutor that makes quality education accessible for every child.
