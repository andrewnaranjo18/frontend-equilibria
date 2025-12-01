📱 Equilibria — Frontend (React Native + Expo)

<<<<<<< HEAD
This is the fully completed frontend for the Equilibria mobile app. All screens, navigation, offline storage, and API connections are finished.
=======
This is the fully completed frontend for the Equilibria mobile app.
All screens, navigation, offline storage, and API connections are finished.
>>>>>>> fb62e246ed07eefdf0fbb5dc5f8d2ad298208ad3

Backend currently returns errors, so the app runs in Developer Skip Login Mode until backend is fixed.

🚀 How to Run the App (Expo)
<<<<<<< HEAD

Verify Node.js is installed
Run this in your terminal:

node -v <--- run in terminal npm -v <--- run in terminal

If both show a version number → you're good.

If NOT installed, install using your package manager:

Mac (Homebrew):

brew install node <--- run in terminal

Windows (Chocolatey):

choco install nodejs <--- run in terminal

Install Expo CLI npm install -g expo-cli <--- run in terminal

Clone the Project

git clone https://github.com/andrewnaranjo18/equilibria-frontend.git <--- run in terminal cd equilibria-frontend <--- run in terminal

Install Dependencies npm install <--- run in terminal

Start the App expo start <--- run in terminal

This will show a QR code.

Open on Your Phone
Install Expo Go → scan the QR code → app loads immediately.

🎨 Frontend Features Completed ✔ Full Mobile UI
=======
1. Verify Node.js is installed

Run this in your terminal:

node -v                    <--- run in terminal
npm -v                        <--- run in terminal


If both show a version number → you're good.

If NOT installed, install using your package manager:

Mac (Homebrew):

brew install node            <--- run in terminal


Windows (Chocolatey):

choco install nodejs              <--- run in terminal

2. Install Expo CLI
npm install -g expo-cli              <--- run in terminal

3. Clone the Project

git clone https://github.com/andrewnaranjo18/equilibria-frontend.git          <--- run in terminal
cd equilibria-frontend           <--- run in terminal
           

4. Install Dependencies
npm install                            <--- run in terminal

5. Start the App
expo start                      <--- run in terminal


This will show a QR code.

6. Open on Your Phone

Install Expo Go → scan the QR code → app loads immediately.

🎨 Frontend Features Completed
✔ Full Mobile UI
>>>>>>> fb62e246ed07eefdf0fbb5dc5f8d2ad298208ad3

Login

Register

Dashboard

Daily Check-In

Workout Builder (drag & drop)

Weekly Insights

Workout History

Workout Session Logger

Workout Session Detail Viewer

✔ Drag-and-Drop Workout Builder

react-native-gesture-handler

react-native-reanimated animations

Reorder exercises smoothly

✔ Offline Support

Uses AsyncStorage to save check-ins + workouts

Automatically syncs once backend is fixed

✔ API Ready

All API calls are wired using Axios.

🔌 Connected API Endpoints

The frontend already sends requests to these backend routes:

<<<<<<< HEAD
/api/v1/auth/register /api/v1/auth/login /api/v1/auth/me /api/v1/recovery/log /api/v1/recovery/latest /api/v1/wearables/sync /api/v1/workouts/ /api/v1/workouts/sessions

🛠 Backend Needs Fixing (Important)

Swagger testing shows 500 errors on backend routes. Because of this, login and data sync return 401/500 responses.

➡ Frontend is finished. Backend must be fixed before integration works.

Developer Skip Login is included so the app can still be tested.
=======
/api/v1/auth/register
/api/v1/auth/login
/api/v1/auth/me
/api/v1/recovery/log
/api/v1/recovery/latest
/api/v1/wearables/sync
/api/v1/workouts/
/api/v1/workouts/sessions

🛠 Backend Needs Fixing (Important)

Swagger testing shows 500 errors on backend routes.
Because of this, login and data sync return 401/500 responses.

➡ Frontend is finished. Backend must be fixed before integration works.

Developer Skip Login is included so the app can still be tested.
>>>>>>> fb62e246ed07eefdf0fbb5dc5f8d2ad298208ad3
