# Drink Promoter Bot (酒促嬰仔) 🍻

**Drink Promoter Bot** is your personal Line Bot assistant designed specifically for drinking parties and social gatherings.
Whether you're struggling with decision paralysis on where to go for a drink, or you need something fun to hype up the atmosphere, **Drink Promoter Bot** has got you covered!

**酒促嬰仔** 是一個專為喝酒聚會設計的 Line Bot 貼身小幫手。
不管你是想喝酒但有選擇障礙，還是聚會氣氛不夠嗨想來點刺激的，找「酒促嬰仔」就對了！

## 📱 Line ID

ID: `@620kjouq`

## ✨ Features

### 1. 🍶 Drinking Spot Recommender

Perfect for when you can't decide where to go.

* **How it works**: The bot randomly selects a type of venue from its database (e.g., Bar, Izakaya, Bistro, Stir-fry).
* **Location-Based Search**: Once a type is chosen, it asks for your current location.
* **Smart Recommendations**: Utilizing the **Google Maps API**, it searches for highly-rated spots within a **1 km radius** and provides a list of up to **10 recommendations** (including ratings and map links).

### 2. 🎲 Drinking Game Roulette

The ultimate ice-breaker to ensure no dull moments at your party.

* **How it works**: The bot randomly selects a classic drinking game from its curated list (e.g., Number Bomb, Two Truths and a Lie, Truth or Dare).
* **Instant Play**: It provides simple rules or penalty instructions so you can start playing immediately.
* **Non-Stop Fun**: Finished a round? Just hit the button to spin the roulette again!

## 🛠️ Tech Stack

This project is an example of a Serverless application combining Webhook event-driven architecture with cloud deployment.

| Category | Technology |
| --- | --- |
| **Language & Framework** | Python, Flask |
| **Messaging Protocol** | Line Messaging API (SDK v3) |
| **External Services** | Google Maps API (Places API) |
| **Containerization** | Docker |
| **App Server** | Gunicorn (WSGI) |
| **Cloud Deployment (PaaS)** | Render |
| **Monitoring** | UptimeRobot (Keeps the service awake) |
| **Development Environment** | Python venv, ngrok (Local Webhook testing) |
| **AI Assistance** | AI-Assisted Coding |
| **Version Control** | Git |

## 🚀 Future Roadmap

* [ ] **Multi-language Support**: Add an English interface for international users.
* [ ] **More Games**: Expand the drinking game database with more varieties.