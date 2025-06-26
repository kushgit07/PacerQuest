# PACER Ques

PACER Quest is an AI-powered interactive learning game that converts text into gamified flashcards using the **PACER (Procedural, Analogous, Conceptual, Evidence, Reference) enrichment** method. It enhances retention and understanding by structuring learning content into engaging flashcards and quizzes.

## 🚀 Features

### 🏗 Core Features
- **AI-Powered Text Processing:** Converts input text into PACER-enriched flashcards.
- **Flashcard Generation:** Creates interactive flashcards based on AI responses.
- **Flip Animation & Tab Switching:** 3D card flips and tab-based navigation for P/A/C/E/R content.
- **Adaptive Quizzes:** AI-generated MCQs.
- **Retention-Boosting Games:** Interactive quizzes and memory card games for better learning.

### 🌍 Website Sections
- **Home Page:** Introduction to PACER Quest.
- **Features Page:** Detailed explanation of the functionalities.
- **Newsletter Section:** Educational articles related to learning and memory techniques.
- **About Section:** Information about the project and its creators.

## 🛠 Tech Stack

- **Frontend:** React (Vite) + TypeScript + Tailwind CSS
- **Backend:** Not implemented yet (can be integrated with Firebase or NextAuth.js for authentication)
- **Database:** MongoDB (Compass for local testing)
- **AI Processing:** Hugging Face (for text chunking, summarization, and quiz generation)
- **Authentication:** Firebase (for social logins) & NextAuth.js (for email-based logins)
- **Deployment:** To be decided (Vercel or Firebase Hosting suggested)

## 📂 Folder Structure
```
PACER-Quest/
│── src/
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── Footer.jsx
│   │   ├── Flashcard.jsx
│   │   ├── Quiz.jsx
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── BlogPage.jsx
│   │   ├── FlashcardPage.jsx
│   │   ├── QuizPage.jsx
│   ├── styles/
│   │   ├── App.css
│   │   ├── Header.css
│   │   ├── Footer.css
│   │   ├── FlashcardPage.css
│   ├── services/
│   │   ├── aiService.js
│   │   ├── quizService.js
│   ├── App.jsx
│   ├── main.jsx
│── public/
│── README.md
│── package.json
│── .gitignore
```

## 🛠 Setup & Installation

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- MongoDB Compass (if using MongoDB locally)

### 🔧 Installation Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/PACER-Quest.git
   cd PACER-Quest
   ```
2. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   ```
3. **Start the development server:**
   ```bash
   npm run dev
   ```
4. **Open in browser:**
   ```

## 🔥 Roadmap

### ✅ Phase 1: Core Development
- [x] Build PACER-based flashcard system
- [x] Implement AI-powered text chunking
- [x] Add flipping animations & progress tracking

### 🚀 Phase 2: Enhancements
- [ ] User authentication (Firebase + NextAuth.js)
- [ ] Cloud storage for user data (MongoDB or Firebase Firestore)
- [ ] Mobile-friendly UI improvements

### 🌟 Phase 3: Advanced Features
- [ ] AI-based adaptive learning engine
- [ ] Leaderboards & gamification
- [ ] Multi-language support

## 🤝 Contributing
1. Fork the repo and create a new branch.
2. Make your changes and commit with a descriptive message.
3. Push to your fork and submit a pull request.

## 📜 License
MIT License. See `LICENSE` for more details.

## 📬 Contact
For any issues, reach out to [your email or GitHub profile link].

"# PacerQuest" 
