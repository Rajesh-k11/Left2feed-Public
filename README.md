# Left2Feed 🥗 - Food Sharing Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)]  
**Note on Source Code**
This project is currently under active development and contains proprietary logic. The source code is held in a private repository. Access can be granted to recruiters upon request.

**Turn Extra Meals into Extra Smiles** – A modern web application connecting food donors with NGOs and shelters to reduce food waste and fight hunger.

---

## 🌟 Features

- 🍽️ **Food Sharing**: List surplus food for pickup by verified NGOs  
- 🤝 **Community Network**: Connect with local shelters and food banks  
- 📱 **Mobile Optimized**: Fully responsive on all devices  
- 🌙 **Night Mode**: Dark/light theme support  
- 🌍 **Multi-language**: English, Hindi, Tamil, Telugu  
- 🔒 **Secure**: Google OAuth & email/password authentication  
- 📊 **Analytics**: Track your impact and community contributions  

---

## 🛠 Tech Stack

- **Frontend**: React 18 + TypeScript + Vite  
- **Styling**: Tailwind CSS  
- **Backend**: Supabase (PostgreSQL + Auth)  
- **Icons**: Lucide React  
- **Routing**: React Router DOM  

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18+  
- npm or yarn  
- Firebase account  

### Installation

```bash
git clone <your-repo-url>
cd left2feed
npm install
cp .env.example .env
Add your Firebase credentials to .env:

env
Copy code
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
Start the development server:

bash
Copy code
npm run dev
Open http://localhost:5173 in your browser.

📁 Project Structure
bash
Copy code
src/
├── components/      # Reusable UI components
├── contexts/        # React contexts (Auth, Theme, Language)
├── pages/           # Page components
├── lib/             # Utility functions
└── styles/          # Global styles

supabase/
├── migrations/      # Database migrations
└── config.toml      # Supabase configuration
🔧 Database Setup
Firebase (Firestore) setup:

bash
Copy code
npm install -g firebase-tools
firebase login
firebase init
firebase deploy --only firestore
🌐 Deployment
Configured for Netlify:

bash
Copy code
npm run build
🤝 Contributing
Fork the repo

Create a feature branch

Make your changes

Submit a pull request

📝 License
MIT License

💬 Support
Email: rajeshkanthasamy11@gmail.com
Join our Discord community

Optional: Add a screenshot
markdown
Copy code
![App Screenshot](./screenshots/homepage.png)
