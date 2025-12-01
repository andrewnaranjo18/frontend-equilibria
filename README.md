📱 Equilibria Frontend (React Native + Expo)

This is the full frontend for our Equilibria mobile app.
All screens, navigation, offline storage, and API connections are fully implemented.

🔥 Status

✅ Frontend COMPLETED

🔌 All backend API endpoints connected

❌ Backend currently failing (500/401 errors when tested)

Frontend works, but backend must be fixed before real data can sync.

📲 How to Run the App (Expo)
1. Install Node.js
Mac (with Homebrew):
brew install node          <--- run in terminal

Windows (with Chocolatey):
choco install nodejs           <--- run in terminal


If you don’t have Homebrew/Chocolatey, download Node.js here:
👉 https://nodejs.org

Check installation:

node -v      <--- run in terminal
npm -v        <--- run in terminal

2. Clone the Repo
git clone <https://github.com/andrewnaranjo18/frontend-equilibria.git>              <--- run in terminal
cd frontend-equilibria-app            <--- run in terminal

3. Install Dependencies
npm install               <--- run in terminal

4. Start the App
npx expo start            <--- run in terminal

5. Run on Your Phone

Install Expo Go from the App Store / Google Play

Scan the QR code shown in your terminal

You can now interact with EVERY screen (login, dashboard, workout builder, session logging, history, etc.)

🔌 Connected API Endpoints

The frontend already calls all required routes:

/api/v1/auth/register

/api/v1/auth/login

/api/v1/auth/me

/api/v1/recovery/log

/api/v1/recovery/latest

/api/v1/wearables/sync

/api/v1/workouts/

/api/v1/workouts/sessions

(Backend is returning errors, but the frontend integration is fully completed.)

🛠️ Backend Needs Fixing (Team Note for Dwain + Fenthon)

Swagger testing shows multiple backend endpoints failing.
Frontend is fully wired up — backend fixes required before integration.
