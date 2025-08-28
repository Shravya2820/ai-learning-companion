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

## 🔮 Future Roadmap

Our hackathon prototype focuses on speech-to-text, text-to-speech, and basic lesson modules.  
We envision growing this into a **comprehensive inclusive learning platform** with the following milestones:

### Phase 1 – Prototype (Hackathon)
- ✅ Speech-to-text and text-to-speech integration (Azure Cognitive Services)  
- ✅ Basic reading/quiz modules with progress tracking (Firebase)  
- ✅ Simple React frontend for accessibility  

### Phase 2 – Enhanced Learning Features
- 🎮 Gamification: badges, rewards, and interactive exercises  
- 🌍 Multilingual support for Indian regional languages  
- 📊 Teacher/Parent dashboards with personalized insights  

### Phase 3 – AI Personalization
- 🤖 Adaptive AI tutor that adjusts difficulty and lesson flow dynamically  
- 😊 Emotion detection (using voice/facial sentiment) to sense frustration/boredom  
- 🧩 Multi-disability modes (custom settings for dyslexia, ADHD, autism, dyscalculia)  

### Phase 4 – Scaling & Impact
- ☁️ Offline support for rural/low-internet areas  
- 🏫 Partnerships with schools and NGOs for deployment  
- 📱 Mobile app (React Native) for wider accessibility  
- 🌐 Community-driven content expansion with teacher contributions
---

### 👨‍👩‍👧 Team
- Shravya N Bhat – [Role]
- Trishal Hegde – [Role]
- Vaishnavi Ghogre – [Role]
- Vishruth HR – [Role]
---
### 📜 License
This project is open-sourced under the MIT License.

---

### 🚀 Our vision: To become the first truly inclusive, multilingual, multi-disability AI tutor that makes quality education accessible for every child.
---
