# predi-king-ai-app
PrediKing 👑
Smart Sports Betting Prediction App Powered by AI & Real-Time Stats
Welcome to PrediKing — the intelligent sports betting assistant that leverages powerful AI models and real-time match data to deliver premium predictions with up to 88% confidence.
🏗️
Project Structure
prediking-ai-app/
├── backend/ # Node.js + Express API (User Auth, Admin, Payments)
│ ├── index.js
│ ├── payments/ # Uploaded payment proofs
│ ├── routes/ # Optional: separate routes
│ └── utils/ # Optional: helper functions
│
├── ai-engine/ # Python Flask + ML Model
│ ├── app.py # Prediction API
│ ├── matches.csv # Real dataset
│ └── model.pkl # Trained ML model (optional)
│
├── mobile-app/ # Flutter App (Android & iOS)
│ ├── lib/
│ │ ├── main.dart
│ │ └── screens/ # Login, Home, Predict, UploadProof, Admin
│ └── assets/ # Logo, fonts, icons
│
├── assets/ # Logos, brand files, PDFs
│ └── prediking-logo.png
│
├── README.md # This file
└── .gitignore # Node, Python, Flutter ignores
🚀 Features
● ⚽ Predict outcomes based on team/player stats
● 🔐 User authentication with secure login/register
● 🤖 Auto prediction using trained ML model
● 📝 Manual prediction input for free users
● 💸 Premium unlock with Namibian bank payment support (FNB, Standard Bank)
● 📤 Upload proof of payment to access premium AI tickets
● 🛡️ Admin dashboard to approve or reject payments
● 📱 Cross-platform mobile app (Flutter)
🧠 AI Prediction Engine
● Python Flask microservice
● Uses scikit-learn and RandomForestClassifier
● Dataset: matches.csv (custom sports data)
● Returns predicted outcome + confidence level
⚙️
How to Run (Dev Mode)
Backend (Node.js)
cd backend
npm install
node index.js
AI Engine (Python)
cd ai-engine
pip install flask pandas scikit-learn joblib
python app.py
Flutter Mobile App
cd mobile-app
flutter pub get
flutter run
💳 Payments (Namibia)
● Manual payment via eWallet / Bank Transfer
● Upload proof via mobile or web UI
● Admin verifies and unlocks AI predictions
Bank Accounts:
● FNB – Romeo R., Acc: 12345678901
● Standard Bank – Romeo R., Acc: 98765432109
🧪 Sample Prediction
{
"prediction": "Team A wins",
"confidence": "88%"
}
✨ Tech Stack
Layer
Tech
Frontend
Flutter
Backend
Node.js + Express
AI Engine
Python + Flask + scikit-learn
Auth
JWT + bcrypt
Payments
Manual (Proof Upload + Admin)
👑 Author
Romeo – Developer, Dreamer, and Digital King of Predictive Realms.
📄 License
MIT (or specify your preferred license)
Once this structure is up on your GitHub, you’re all set for version control, team collaboration, and investor-ready presentation.
Next: Want me to zip and send you the backend + AI upload-ready folders? Or create a GitHub push script to upload automatically?
Let's launch this legend into the sky! 🚀

