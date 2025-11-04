# 🎵 Pulse App

**Pulse** is a real-time entertainment and social connection platform — where users can go live, post, chat, and experience creativity freely.  
Built with **React Native + Expo + Firebase**, the app is designed to give users satisfaction, connection, and expression in one place.


## 🚀 Features (Phase 1–4 Roadmap)

### Phase 1 — Authentication & Base App
- Firebase integration  
- Email/password login & register  
- Navigation between screens  

### Phase 2 — Core Experience
- Home feed with posts  
- Entertainment & Live sections  
- User profiles and avatars  

### Phase 3 — Social System
- Like, comment, and message  
- Real-time Firestore chat  
- Post upload (text/image)  

### Phase 4 — Monetization
- Subscriptions & premium features  
- Security & settings  



## 📁 Folder Structure

PulseApp/ ├── App.js ├── firebase.js ├── app.json ├── package.json ├── /screens │   ├── LoginScreen.js │   ├── RegisterScreen.js │   ├── HomeScreen.js │   ├── LiveScreen.js │   ├── EntertainmentScreen.js │   ├── ProfileScreen.js │   ├── MessageScreen.js │   ├── SecurityScreen.js │   ├── PostScreen.js │   ├── CommentScreen.js │   ├── SubscriptionScreen.js │   └── SettingsScreen.js ├── /components │   ├── PostCard.js │   ├── CommentItem.js │   └── UserAvatar.js


## 🔧 Tech Stack
- **Expo (React Native)** — cross-platform development  
- **Firebase** — backend, authentication, Firestore  
- **EAS Build** — for deploying to Android & iOS  
- **React Navigation** — screen routing  
- **React Native Paper / Tailwind** *(optional UI styling)*  

## ⚙️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/<your-username>/pulse-app.git
   cd pulse-app

2. Install Dependencies

npm install


3. Set Up Firebase

Go to https://console.firebase.google.com

Create a project → “pulse-f5547”

Add your web app, then copy the config into firebase.js


4. Run in Expo

npx expo start

Then scan the QR code in Expo Go on your phone.




---

🧠 Future Add-ons

Realtime Live Streams (via Agora or RTMP)

In-app Wallet & Tipping System

Creator Ranking System

Dark Mode UI


✨ Author

Mathias Simiyu
Founder — Pulse Entertainment Vision
📧 Email: mathiassimiyu52@gmail.com

🕊️ Vision Quote

> “Pulse is where silence meets sound, and creation meets connection.”
