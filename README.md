# SavrCart

SavrCart is a smart grocery budgeting app that helps users build cost-effective shopping lists using real-time store data and AI-powered suggestions. Built with SwiftUI and Firebase, SavrCart integrates Gemini AI and the Kroger API to provide a seamless and optimized grocery planning experience.

## 🧱 Core Features (MVP)
- User sign-up/login (Firebase Authentication)
- Create and manage grocery lists
- Set a total budget and track spending
- Add items manually or via API (Kroger)
- Real-time budget updates
- AI suggestions using Gemini (e.g. cheaper alternatives)
- Visual budget overview (charts/indicators)

## 🔌 Tech Stack
- SwiftUI (iOS/iPadOS)
- Firebase (Auth, Firestore, Functions)
- Gemini AI via Vertex AI (Google Cloud)
- Kroger API
- GitHub for version control

## 📦 Folder Structure
```
savrcart/
├── ios/
├── functions/
├── assets/
├── docs/
├── .env (not committed)
└── README.md
```

## 🛠 Setup Instructions
1. Clone this repository:
```bash
git clone https://github.com/your-username/savrcart.git
cd savrcart
```

2. Set up your environment:
```bash
cp .env.example .env
# Then fill in the correct keys in the .env file
```

3. Install dependencies and run the app in Xcode.

## 🔐 Environment Variables
See `.env.example` for required keys and structure.

## 📄 License
MIT License (or specify your own).

---
Created by Cameron Letroy Pearson
