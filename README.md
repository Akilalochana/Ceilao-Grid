# Ceilão Grid

[![Website](https://img.shields.io/badge/Website-Live-green)](https://www.ceilaogrid.live)
[![Platform](https://img.shields.io/badge/Platform-Android-blue)]()
[![Kotlin](https://img.shields.io/badge/Language-Kotlin-orange)]()
[![ARCore](https://img.shields.io/badge/AR-ARCore-red)]()
[![Firebase](https://img.shields.io/badge/Backend-Firebase-yellow)]()

## Overview

Ceilão Grid is an innovative AR-powered agricultural planning platform designed to help individuals transform their available land into productive home gardens. The project bridges the gap between traditional farming knowledge and modern technology, enabling users to make informed decisions about land use, crop selection, and garden management.

In today's world, where chemical-laden produce is widespread, Ceilão Grid empowers users to grow their own chemical-free vegetables and fruits, promoting sustainable living while providing opportunities for additional income through surplus sales.

## Project Components

### Mobile Application (Android)
The core component of Ceilão Grid, providing augmented reality land measurement, crop planning, and garden management tools.

### Marketing Website
A React-based website serving as the project's public face, offering information about our platform, features, and agricultural best practices.

## Mobile App Features

### 🔍 AR Land Measurement
- **Precise Area Calculation**: Measure any plot of land using smartphone AR capabilities
- **3D Visualization**: See your garden layout in 3D with virtual crop placement
- **Grid Planning**: Create optimized planting grids with proper spacing for each crop type

### 🌱 Plant Recommendation System
- **Location-Based Suggestions**: Crop recommendations based on your district's climate
- **Seasonal Planting Guide**: Know when to plant based on your local weather patterns
- **Visual Plant Library**: Comprehensive database of suitable crops with images and information

### 🤖 AI Chatbot Assistant
- **Gardening Guidance**: Get instant answers to common gardening questions
- **Troubleshooting Help**: Identify and solve issues with your plants
- **Feature Navigation**: Direct access to app features through conversational UI

### 📊 Reporting & Analytics
- **Yield Prediction**: Estimate potential harvest quantities based on your garden layout
- **Resource Planning**: Calculate water and fertilizer needs for your specific garden
- **PDF Export**: Generate detailed reports of your garden plan for offline reference

### 🌤️ Weather Integration
- **Local Conditions**: Real-time weather data for your specific location
- **Planting Alerts**: Recommendations on ideal planting times based on weather forecasts
- **Adverse Weather Warnings**: Notifications about conditions that may affect your garden

### 📚 Gardening Tips & Education
- **Crop-Specific Guides**: Detailed instructions for growing each plant type
- **Sustainable Practices**: Learn eco-friendly gardening techniques
- **Pest Management**: Natural solutions to common garden problems

## Technical Architecture

### Mobile Application
- **Language**: Kotlin
- **AR Framework**: Google ARCore
- **UI Components**: Material Design, Custom Views
- **Animation**: Lottie for fluid animations
- **Backend**: Firebase (Authentication, Firestore, Storage)
- **Image Loading**: Glide
- **Weather API**: Integration with weather services

### Development Requirements
- Android Studio Arctic Fox or newer
- Kotlin 1.5+
- Minimum SDK: Android 8.0 (API 26)
- Target SDK: Android 14 (API 34)
- ARCore compatible device

## Getting Started

### Prerequisites
- Android Studio Arctic Fox or newer
- Git
- ARCore supported Android device (Android 8.0+)
- Firebase account (for backend functionality)

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/rasandu17/Ceilao-Grid.git
   cd Ceilao-Grid
   ```

2. **Open the project in Android Studio**
   - Launch Android Studio
   - Select "Open an existing Android Studio project"
   - Navigate to the cloned repository and select the `cg_mobile_app` folder

3. **Configure Firebase**
   - Create a Firebase project at [firebase.google.com](https://firebase.google.com)
   - Add an Android app to your Firebase project
   - Download the `google-services.json` file and place it in the `app/` directory
   - Enable Authentication, Firestore, and Storage services

4. **Build and Run**
   - Connect your ARCore-compatible device
   - Click "Run" in Android Studio

### Configuration
- Edit `app/build.gradle.kts` for dependency management
- Firebase rules are available in the repository for reference

## Project Structure

```
cg_mobile_app/
├── app/                        # Main application module
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/           # Kotlin source files
│   │   │   │   └── com/example/arlandmeasuretest33/
│   │   │   │       ├── activities/    # Main app activities
│   │   │   │       ├── adapters/      # RecyclerView adapters
│   │   │   │       ├── models/        # Data models
│   │   │   │       └── services/      # Background services
│   │   │   ├── res/            # Resources (layouts, drawables, etc.)
│   │   │   └── AndroidManifest.xml
│   ├── build.gradle.kts        # App-level Gradle build file
├── build.gradle.kts            # Project-level Gradle build file
└── gradle/                     # Gradle wrapper and dependency versions
```

## Contributing

We welcome contributions to help improve Ceilão Grid! Please follow these steps to contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

### Coding Standards
- Follow Kotlin coding conventions
- Include comments for complex logic
- Write unit tests for new features

## Contact

Project Link: [https://github.com/rasandu17/Ceilao-Grid](https://github.com/rasandu17/Ceilao-Grid)

Website: [https://www.ceilaogrid.live/](https://www.ceilaogrid.live/)
