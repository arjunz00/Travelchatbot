# 🌍 Travel Planner Agent

An AI-powered assistant built using IBM Cloud Lite and IBM Granite that helps users plan trips efficiently and intelligently.


## 🚀 Project Overview

The Travel Planner Agent is a smart assistant that simplifies the process of travel planning. It uses real-time data, user preferences, and intelligent automation to:

- Suggest travel destinations
- Build customized itineraries
- Recommend transportation and accommodation
- Integrate with maps and weather
- Manage bookings and provide real-time alerts

---

## 🧠 Features

- ✅ Personalized travel suggestions
- 🌦️ Weather updates and travel advisories
- 🗺️ Local guide and map integration
- 🏨 Accommodation and transport recommendations
- 📆 Schedule optimization
- 📲 Booking management and alerts
- 🛡️ Profanity/danger word detection and fallback handling

---

## 🛠️ Technologies Used

- IBM Cloud Lite Services
- IBM Watson Assistant
- IBM Granite
- Node.js / JSON configuration
- Dialog Actions, Intents, Entities


## 🧩 Architecture

- Intents (5) — User goals (e.g., plan trip, suggest hotels)
- Entities (9) — Extracted data like destination, budget, date
- Actions (8) — Smart responses and booking steps
- Global Variables (8) — For storing context (e.g., name, destination)


## ⚙️ How to Use

1. Clone this repository.
2. Import workspace.json into IBM Watson Assistant.
3. Set up your IBM Cloud Lite environment.
4. Deploy the skill using Watson Assistant GUI or APIs.
5. Interact via the integrated chat or build a frontend.


## 🧪 Sample Flow

User: I want to plan a trip
Bot: Great! What is your name?
User: Arjun
Bot: Arjun, I can help you plan your trip. Let’s get started.


## 📞 Fallback & Escalation

The assistant detects fallback reasons such as:
- No matching action
- Danger words
- Profanity
And gracefully escalates to a human agent when required.


## 🔒 Safety Features

- Detects profanity/danger keywords
- Warns users appropriately
- Limits repeated misuse via max_hits

---

## 🧑‍💻 Author

Arjun  
Built as part of the AICTE-IBM SkillsBuild Internship Challenge  
Using IBM Cloud Lite & Watson Assistant
