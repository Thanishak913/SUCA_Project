# 🚍 SUCA — Smart Urban Commute Assistant
### Real-time Public Transport + Shared Mobility + AI Predictions

SUCA (Smart Urban Commute Assistant) is a unified smart mobility platform designed to reduce travel uncertainty in cities by combining:

Real-time bus & metro tracking

Nearby sharable autos / cabs / bikes

Hybrid route planning

AI-powered crowd & delay prediction

Fare + ETA optimization

Heatmap-based congestion visualization

Built using React, Node.js, Express, and OpenStreetMap, SUCA delivers an intuitive and intelligent travel planning experience.

### ⭐ Features
🚍 1. Real-Time Public Transport Tracking
Live bus movement simulation

ETA updates every 5 seconds

Delay status indicators

BMTC bus simulation

Namma Metro (Green + Purple line) movement

🛺 2. Nearby Shared Vehicles
Autos, cabs, bikes, e-scooters

Distance, base fare, ratings

Heatmap showing density & traffic hotspots

🧠 3. AI-Based Crowd & Delay Prediction
Estimates crowd based on time-of-day patterns

Predicts delay risk

Suggests ideal departure time

AI Fare + ETA Optimizer:

💰 Cheapest route

⚡ Fastest route

🧠 Balanced smart route

🗺 4. Interactive Smart Map
OpenStreetMap tiles (free, no API keys)

Start & destination pins

Live buses + metro + BMTC markers

Heatmap overlay using leaflet.heat

### 🏗 Tech Stack
#### Frontend
React.js

React-Leaflet

Leaflet.js

Leaflet Heatmap Extension

#### Backend
Node.js

Express.js

Simulated live bus/metro models

RESTful APIs

### 📁 Project Structure
SUCA_Project/
│
├── frontend/
│   ├── src/
│   │   ├── App.js
│   │   ├── MapView.js
│   │   └── components/
│   └── public/
│
└── backend/
    ├── index.js
    ├── package.json
### 🚀 How to Run the Project
1️⃣ Start Backend
cd backend
npm install
node index.js
Backend runs at → 

2️⃣ Start Frontend
cd frontend
npm install
npm start
Frontend runs at → 

### 🔥 Backend API Endpoints
Endpoint	Description
/stops	Fetch all stops
/route?from=X&to=Y	Best routes
/nearby?lat=&lng=	Nearby shared vehicles
/hybrid	Smart hybrid routing
/ai	AI crowd + delay prediction
/optimize?type=	Smart fare/ETA recommendation
/live-buses	City bus live tracking
/bmtc-live	BMTC bus live tracking
/metro-live	Metro train live simulation
### 🎯 One-Line Summary
SUCA unifies public transport, shared mobility, and AI to deliver the fastest, smartest, and most predictable urban travel experience.

### 🏆 Why This Project Stands Out
Combines multiple smart-city features into one system

Real-time interactive visuals

AI-enhanced predictions

Completely scalable architecture

Looks impressive in demos & hackathons

### 📜 License
This project is for educational and demo/hackathon use.
