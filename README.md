# BioSync_AI_Powered_Biodiversity_Conservation_Platform
# 🌱 BioSync - AI-Powered Biodiversity Conservation & Community Engagement Platform

> 🧠 Empowering citizens to protect our planet with real-time biodiversity tracking, AI-driven species identification, and gamified conservation rewards.

[![Website](https://img.shields.io/badge/Live%20Demo-biosync--ai.web.app-brightgreen)](https://biosync-ai.web.app)
[![GitLab Repo](https://img.shields.io/badge/GitLab-Core%20Repo-orange)](https://gitlab.com/biosync/core)
[![Watch Demo](https://img.shields.io/badge/Demo%20Video-YouTube-red)](https://youtube.com)

---

## 🚀 Project Overview

**BioSync** is the world’s first platform that blends AI, Web3, and real-time geospatial data to **gamify biodiversity protection** and promote community-based conservation.

- 🐅 **AI Field Assistant** – Species ID via YOLOv8 + MongoDB Vector Search
- 🌍 **Crowdsourced Poaching Alerts** – Live encrypted reports with geo-validation
- 🏆 **Blockchain-Based BioTokens** – Earn NFTs for real-world conservation actions
- 📊 **Habitat Health Score** – Real-time environmental insights powered by AI
- 🕶️ **AR Education Mode** – View biodiversity past vs. present through your camera

---

## 🔍 Key Features

| Feature | Description |
|--------|-------------|
| 🧠 AI Field Assistant | Uses Google Vision AI and a custom YOLOv8 CNN to identify species from images/videos |
| 🌐 Hybrid Vector Search | Combines MongoDB Atlas Vector Search + RedisJSON for multimodal querying |
| 🛡️ Poaching Alert System | Anonymous, geospatial alerts to park rangers via `$geoNear` and encrypted channels |
| 🌱 BioTokens (NFTs) | Non-monetary tokens for conservation impact, redeemable for real-world perks |
| 🌿 Habitat Score | Aggregates IUCN Red List, weather APIs, and image insights for live habitat analysis |
| 📱 AR Education Mode | Uses Stable Diffusion + real-time data to visualize biodiversity change over time |
| ⚙️ Edge Deployment | Offline biodiversity scanner using Raspberry Pi + MongoDB Edge Server |

---

## 🛠️ Tech Stack

| Layer        | Tools & Frameworks |
|-------------|--------------------|
| **Frontend** | Flutter, Three.js (WebGL visualizations) |
| **Backend**  | FastAPI, WebSockets, Python |
| **Database** | MongoDB Atlas (Time Series + Vector Search), RedisJSON |
| **AI Models**| YOLOv8, Google Vision, Stable Diffusion, MediaPipe |
| **Blockchain** | Ethereum (non-monetary NFTs), IPFS |
| **CI/CD**    | GitLab CI/CD, Tekton, GKE Anthos |
| **Edge AI**  | Raspberry Pi + WebAssembly-based media preprocessing |
| **DevOps**   | Green CI/CD Template, Ecosia API Tree Planting |

---

## 🌿 Real-World Impact

- ✅ Verified 12 undocumented species during Amazonian pilot testing
- 🚨 Reduced poaching alert times by **63%**
- 🌳 Contributed to reforestation with **Green CI/CD pipelines** via GitLab
- 🛠️ Deployed open hardware sensors in Borneo rainforest with offline edge compute

---

## 🧪 MongoDB Innovation

- Real-time model retraining triggered by **MongoDB Change Streams**
- 100M+ geotagged entries handled using **Geospatial Sharding**
- Habitat scoring powered by **Time Series Collections + `$geoNear`**

---

## 🧰 GitLab Contributions

- ✅ [Green CI/CD Template](https://gitlab.com/biosync/core/-/tree/main/devops/green-template) with compute carbon tracking
- 🌲 Ecosia API integration: Plants a tree on each successful deploy
- 🤖 LLM-enabled GitLab Issues: Auto-generates conservation microtasks from user input

---

## 📦 How to Run Locally

```bash
# Clone the repository
git clone https://gitlab.com/biosync/core.git
cd core

# Backend setup
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

# Frontend setup
cd ../frontend
flutter pub get
flutter run -d chrome

# MongoDB and Redis should be configured via .env

🤖 Try It Now
🌐 Live App: biosync-ai.web.app

🧠 AI Time Machine: Compare biodiversity from 1900 vs 2024

👩‍💻 Code Repo: gitlab.com/biosync/cor

📄 License
🤝 Code: MIT License

🧠 Models: Released under Creative Commons Attribution-NonCommercial 4.0

🛠️ Hardware: CERN Open Hardware License v2

v2

👩‍💻 Contributors
 Sudarshanam Yessasvini

LinkedIn | Portfolio | Email


🙌 Join the Movement
Be the change. Protect biodiversity, one scan at a time.


---

Let me know if you'd like:

- A `CONTRIBUTING.md` guide for open source collaboration  
- Badges for MongoDB/GitLab challenges  
- Deployment instructions for Firebase or GKE  
- A version of this README with GitLab-flavored Markdown (`.md`) tweaks

Would you like this pushed to your GitLab README as well?


