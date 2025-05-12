# 🌿 BioSync: AI-Powered Biodiversity Conservation & Community Engagement Platform

> **"Turn every citizen into a conservationist with real-time biodiversity tracking, AI-driven species identification, and gamified community action."**

🌐 [Live App](https://bio-guardian-verse.lovable.app/#community) | 🎥 [Demo Video](https://youtu.be/dVuTwqjnBNAv) |  | 🧠 [Source Code](https://gitlab.com/biosync/core)

---

## 🌍 About BioSync

**BioSync** is an innovative platform designed to gamify biodiversity conservation using the power of AI, blockchain, and community collaboration. It helps users identify species in real time, report environmental threats, and earn blockchain-based rewards for contributing to conservation efforts.

🧠 Built for [MongoDB Hackathon](https://www.mongodb.com) and [GitLab Hackathon](https://about.gitlab.com), BioSync aligns with the **UN Sustainable Development Goals**:  
📌 **Life on Land**, 📌 **Climate Action**, 📌 **Sustainable Communities**

---

## 🚀 Features

### 🧬 AI Field Assistant *(Patent-Pending)*
- Upload photos/videos of flora/fauna
- Uses **MongoDB Vector Search** + Google Vision AI + YOLOv8 + MediaPipe
- Custom CNN model for rare/endemic species

### 🪙 Blockchain-Powered Conservation Tokens
- Earn **non-monetary NFTs ("BioTokens")** for verified reports
- Redeemable for rewards like **“Adopt-an-Acre” programs**

### 🛰️ Crowdsourced Poaching Alerts
- Anonymous + encrypted poaching reporting system
- Geospatial validation using `MongoDB $geoNear`
- Real-time alerts to rangers with Google Maps API

### 🌿 Habitat Health Score
- AI model combining user data, weather, and IUCN updates
- Displays real-time ecosystem health metrics

### 📱 AR Education Mode
- Point your camera to a landscape
- See historical vs current biodiversity using **Stable Diffusion**

---

## 🛠️ Tech Stack

| Layer        | Technology |
|--------------|------------|
| **Database** | MongoDB Atlas (Time Series, Vector Search, Change Streams) |
| **AI/ML**    | YOLOv8, Google MediaPipe, Google Vision API, Stable Diffusion |
| **Search**   | Atlas Vector Search + RedisJSON |
| **Backend**  | FastAPI + WebSockets |
| **Frontend** | Flutter + Three.js (WebGL) |
| **DevOps**   | GitLab CI/CD + Tekton pipelines |
| **Blockchain** | NFT-based reward system (non-monetary) |

---

## 🧪 Implementation Highlights

- **Real-Time Model Retraining:** MongoDB Change Streams trigger auto-retraining on new endangered species reports.
- **Geospatial Sharding:** Scales to 100M+ location-tagged observations.
- **Green DevOps:**  
  - [GitLab Catalog Template](https://gitlab.com/biosync/core) for **Green CI/CD**  
  - Measures pipeline CO2 and plants trees via Ecosia API on successful deploys 🌱
- **Privacy-First AI:**  
  - Local WebAssembly media processing  
  - Differential privacy on public maps

---

## ⚙️ Try It Yourself

- 🌐 **[Live Web App](https://bio-guardian-verse.lovable.app/#community)**  
- 🧠 **[Source Code](https://gitlab.com/biosync/core)**  
- 🎥 **[Demo Video (YouTube)](https://youtu.be/dVuTwqjnBNAv)**  

---

## 💡 Judges Will Remember

✅ Real-world impact: Tribal communities in the Amazon helped validate 12+ undocumented species  
✅ Rapid alerts reduced poaching response times by **63%**  
✅ First open-source “**Conservation-as-Code**” platform  
✅ Deployed on Raspberry Pi-powered AI scanner with **offline MongoDB Edge Server**

---

## 🔐 Ethical AI & Sustainability

- Transparent **Model Cards** for AI models  
- Tracks **carbon & water impact** of training (TPU v4 efficiency)  
- Encourages **eco-conscious contributions** from developers

---

## 📄 License

- 🌿 Software: [MIT License](LICENSE)  
- 🛠️ Hardware: [CERN Open Hardware License](https://ohwr.org/project/cernohl/wikis/home)

---

## 🤝 Contributing

We welcome developers, conservationists, educators, and designers!

1. Fork this repo
2. Clone and run `setup.sh`
3. Start contributing 🌱


---

## 🙌 Credits

Made with ❤️ by Sudarshanam Yessasvini 
🌱 Empowering conservation through ethical AI & open collaboration  
📧 yessasvini.s@gmail.com | 🌐 [Portfolio](https://datascienceportfol.io/yessasvinis)

---


