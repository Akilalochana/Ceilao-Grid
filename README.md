# 🌱 CeilaoGrid - Smart Urban Farming Solution

<div align="center">

<img src="https://github.com/user-attachments/assets/214c403b-79e4-49dd-91c5-0433ea5e23be" alt="CeilaoGrid Logo" width="200"/>

### 🏆 Winner - Cutting Edge 2025 Competition (1st Place)

[![Website](https://img.shields.io/badge/Website-ceilaogrid.live-green?style=for-the-badge)](https://www.ceilaogrid.live/)
[![YouTube](https://img.shields.io/badge/YouTube-Demo-red?style=for-the-badge&logo=youtube)](https://youtu.be/WPl7Ob-SBwA?si=dHaYJ2rQex5x-QSc)
[![Medium](https://img.shields.io/badge/Medium-AR_Article-black?style=for-the-badge&logo=medium)](https://medium.com/@akilalochana7/building-an-ar-land-measurement-app-with-android-and-arcore-795c26388baa)

*Empowering urban dwellers to grow chemical-free produce in small spaces*

</div>

---

## 📖 About CeilaoGrid

In today's fast-paced world, many individuals unknowingly consume vegetables and produce treated with harmful chemicals. Despite the advice to grow vegetables in small spaces to enjoy fresh, chemical-free produce, a gap in understanding persists regarding the benefits of home gardening. 

**CeilaoGrid** bridges that gap by providing an intelligent solution that empowers individuals to:
- 📏 Evaluate their available land using cutting-edge AR technology
- 🌾 Make informed decisions about planting based on AI recommendations
- 📊 Track yields and optimize garden productivity
- 💰 Sell surplus produce and generate additional income

Our system not only assists users in planning their gardens efficiently but also promotes sustainable living and offers opportunities for economic empowerment.

---

## ✨ Key Features

### 🔮 Augmented Reality Land Measurement
- **Real-time AR visualization** of planting spaces
- **3D model rendering** for garden planning
- **SceneForm SDK integration** for accurate measurements
- **Plane detection** technology for precise land evaluation

> 📝 [Read our detailed Medium article](https://medium.com/@akilalochana7/building-an-ar-land-measurement-app-with-android-and-arcore-795c26388baa) about implementing AR land measurement with ARCore

### 🤖 AI-Powered Chat Assistant
- Powered by **Google Gemini AI**
- Instant answers to gardening questions
- Personalized farming advice
- 24/7 availability for user support

### 🌿 Intelligent Plant Recommendations
- Smart suggestions based on:
  - Available land area
  - Local climate conditions
  - Seasonal factors
  - User preferences
- Detailed information for each vegetable including:
  - Growing requirements
  - Expected yield
  - Care instructions
  - Harvest timeline

### 🌤️ Real-Time Weather Integration
- **OpenWeather API** integration
- Location-based weather forecasts
- Planting alerts based on weather conditions
- Seasonal planning recommendations

### 📄 Comprehensive Report Generation
- **PDF report generation** for garden planning
- Detailed yield predictions
- Cost-benefit analysis
- Planting schedules and timelines

---

## 🎬 Demo & Documentation

### 📹 Watch Our Demo
Experience CeilaoGrid in action! Check out our comprehensive demo video showcasing all features:

[![CeilaoGrid Demo](https://img.youtube.com/vi/WPl7Ob-SBwA/maxresdefault.jpg)](https://youtu.be/WPl7Ob-SBwA?si=dHaYJ2rQex5x-QSc)

### 📱 App Screenshots

| Home Screen | AR Measurement | Plant Recommendations |
|:---:|:---:|:---:|
| ![](https://github.com/user-attachments/assets/602624a1-7bf0-4520-a0dc-b420d843e27b) | ![](https://github.com/user-attachments/assets/0c05e9bc-eecc-4f4d-88a5-30037d1fa489) | ![](https://github.com/user-attachments/assets/4c4db37a-725f-4813-81e7-8a0deddd9214) |

| AI Chatbot | Weather Forecast | Vegetable Details |
|:---:|:---:|:---:|
| ![](https://github.com/user-attachments/assets/a5fa5254-7d71-4388-be47-405d3bab5083) | ![](https://github.com/user-attachments/assets/c5498db6-fb7c-4232-89ba-6dab620da227) | ![](https://github.com/user-attachments/assets/884c659f-e2a0-4dd8-affa-2eba7de17781) |
---

## 🛠️ Technology Stack

### Frontend
- **Language:** Kotlin
- **Framework:** Android SDK
- **AR Technology:** ARCore, SceneForm SDK
- **UI/UX:** Material Design 3

### Backend
- **Runtime:** Kotlin Backend
- **Database:** Firebase Realtime Database / Firestore
- **Authentication:** Firebase Auth
- **Storage:** Firebase Cloud Storage

### APIs & Services
- **Weather Data:** OpenWeather API
- **AI Assistant:** Google Gemini AI
- **PDF Generation:** Android PDF Library
- **3D Rendering:** SceneForm SDK

### Development Tools
- Android Studio
- IntelliJ IDEA
- Firebase Console
- GitHub CI/CD for APK automation

---

## 🏗️ System Architecture

```
┌─────────────────┐
│  Android App    │
│   (Kotlin)      │
└────────┬────────┘
         │
    ┌────┴─────┐
    │          │
┌───▼───┐  ┌──▼──────┐
│Firebase│  │ ARCore  │
│Backend │  │SceneForm│
└───┬────┘  └─────────┘
    │
┌───┴──────────────┐
│  External APIs   │
├──────────────────┤
│ • Gemini AI      │
│ • OpenWeather    │
│ • PDF Generator  │
└──────────────────┘
```

---

## 🚀 Getting Started

### Prerequisites
- Android Studio Arctic Fox or later
- Android SDK 24 or higher
- ARCore supported device
- Firebase account

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/ceilaogrid.git
   cd ceilaogrid
   ```

2. **Open in Android Studio**
   ```bash
   # Open the project in Android Studio
   # File → Open → Select the project directory
   ```

3. **Configure Firebase**
   - Download `google-services.json` from Firebase Console
   - Place it in the `app/` directory

4. **Add API Keys**
   Create `local.properties` file:
   ```properties
   GEMINI_API_KEY=your_gemini_api_key
   OPENWEATHER_API_KEY=your_openweather_api_key
   ```

5. **Build and Run**
   ```bash
   # Sync Gradle files
   # Build → Make Project
   # Run → Run 'app'
   ```

### 📦 Download APK

Want to try CeilaoGrid without building from source?

**Email us at:** [team@ceilaogrid.live](mailto:ceilaogrid@gmail.com)

> 📧 Send us an email with "CeilaoGrid APK Request" in the subject line, and we'll send you the latest APK build!

*Our GitHub CI/CD pipeline automatically generates APK builds for easy distribution.*

---

## 🏆 Recognition & Achievements

### Cutting Edge 2025 - 1st Place Winner 🥇
CeilaoGrid won first place at the prestigious **API Cutting Edge 2025** competition, competing against innovative projects from across the industry.

| Competition Booth | Award Ceremony |
|:---:|:---:|
| ![](https://github.com/user-attachments/assets/d9469ba2-c92d-4712-a651-c793c4735366) | ![](https://github.com/user-attachments/assets/9e78955f-b533-45fa-a127-35b3f0c76dc5) |

*Our team showcasing CeilaoGrid at Cutting Edge 2025*

</div>

**What the judges said:**
> "CeilaoGrid demonstrates exceptional innovation in combining AR technology with sustainable agriculture. The practical application and user-centered design make it a standout solution for urban farming challenges."

---

## 👥 Team

Meet the talented team behind CeilaoGrid:

<div align="center">

| Name | Role |
|------|------|
| **Promodi Silva** | QA Engineer & Frontend Dev | 
| **Akila Lochana** | Full Stack Developer & AI Integration | 
| **Ravindu Sandumith** | Backend Developer &  AI Integration | 
| **Navinya Dewamiththa** | UI/UX Designer& Frontend Dev |
| **Yuneth Samarasinghe** | Full Stack Developer & Documentation |
| **Pujana Rathnayake** | Frontend Dev & Documentation |

</div>

### 🎓 Institution
**Informatics Institute of Technology (IIT Campus)**
- Affiliated with University of Westminster, UK

---

## 📅 Project Timeline

| Milestone | Status | Date |
|-----------|--------|------|
| 📋 Project Proposal Submitted | ✅ Completed | 31-10-2024 |
| 📊 Progress Report Submitted | ✅ Completed | 22-11-2024 |
| 🎥 Demo Video Released | ✅ Completed | December 2024 |
| 🏆 API Cutting Edge 2025 - 1st Place | ✅ Won | 2025 |
| 📱 Beta Testing Phase | 🔄 In Progress | Q1 2025 |
| 🚀 Public Release | 📅 Planned | Q2 2025 |

---

## 🌟 Feature Highlights

### AR Land Measurement in Action
Our AR feature uses cutting-edge ARCore technology to provide:
- ✨ Real-time plane detection
- 📐 Accurate measurements in square meters/feet
- 🎨 Visual overlays for better understanding
- 📸 Capture and save measurements

### Smart Recommendations Engine
The app analyzes multiple factors:
```
User Land Area + Weather Data + Seasonal Info
           ↓
    Gemini AI Processing
           ↓
  Personalized Plant Recommendations
           ↓
  Yield Predictions + Care Instructions
```

---

## 📱 Core Modules

### 1. AR Measurement Module
- Utilizes ARCore and SceneForm SDK
- Real-time surface detection
- 3D visualization of planting areas
- Save and share measurements

### 2. Plant Database
- Comprehensive vegetable information
- Growing guides and tips
- Seasonal availability
- Nutrient requirements

### 3. Weather Integration
- Current weather conditions
- 7-day forecast
- Planting alerts
- Climate-based recommendations

### 4. AI Assistant
- Natural language processing
- Context-aware responses
- Farming knowledge base
- Multi-language support (future)

### 5. Report Generation
- PDF export functionality
- Garden planning documents
- Yield projections
- Cost analysis

---

## 🔒 Security & Privacy

- 🔐 Firebase Authentication for secure access
- 🛡️ Encrypted data transmission
- 📍 Optional location sharing
- 🗑️ User data deletion on request
- 📋 GDPR compliant (planned)

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

1. 🍴 Fork the repository
2. 🌿 Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push to the branch (`git push origin feature/AmazingFeature`)
5. 🔄 Open a Pull Request

### Contribution Guidelines
- Follow Kotlin coding conventions
- Write meaningful commit messages
- Add comments for complex logic
- Update documentation as needed
- Test thoroughly before submitting PR

---

## 📄 License

This project is currently under development. License information will be added soon.

---

## 📞 Contact & Support

- 🌐 **Website:** [www.ceilaogrid.live](https://www.ceilaogrid.live/)
- 📧 **Email:** ceilaogrid@gmail.com
- 📺 **YouTube:** [CeilaoGrid Channel](https://youtu.be/WPl7Ob-SBwA?si=dHaYJ2rQex5x-QSc)
- 📝 **Medium:** [@akilalochana7](https://medium.com/@akilalochana7)
- 🐙 **GitHub:** [CeilaoGrid Repository](#)

---

## 🙏 Acknowledgments

- **Informatics Institute of Technology** for their support and resources
- **API Cutting Edge 2025** organizers for the platform
- **Google** for ARCore and Gemini AI
- **OpenWeather** for weather data API
- **Firebase** team for excellent backend services
- Our amazing **beta testers** and early supporters

---

## 🌱 Future Roadmap

- [ ] iOS version development
- [ ] Multi-language support (Sinhala, Tamil, English)
- [ ] Community marketplace for surplus produce
- [ ] Integration with local agricultural experts
- [ ] Gamification features for engagement
- [ ] IoT sensor integration for automated monitoring
- [ ] Social features for community gardening
- [ ] Carbon footprint tracking

---

## 📊 Project Stats

![GitHub stars](https://img.shields.io/github/stars/yourusername/ceilaogrid?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourusername/ceilaogrid?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/yourusername/ceilaogrid?style=social)

---

<div align="center">

### 🌟 Star us on GitHub — it motivates us a lot!

**Made with 💚 by Team CeilaoGrid**

*Grow smarter, live healthier, farm sustainably*

[⬆ Back to Top](#-ceilaogrid---smart-urban-farming-solution)

</div>
