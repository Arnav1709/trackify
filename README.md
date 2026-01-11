# Trackify - AI Attendance Tracker  

Trackify is a next-generation AI-powered attendance tracker built with **Gemini**, **Flutter**, **Firebase**, and **RevenueCat**. It simplifies attendance management by enabling natural language queries and leveraging advanced machine learning for seamless operation across educational institutions, workplaces, and events.  

## Features  

- **AI-Powered Natural Language Query**: Powered by Gemini, enabling users to ask questions like "Who was absent last week?" or "What is the attendance rate for today?"  
- **Cross-Platform Compatibility**: Built with Flutter to ensure a smooth experience on Android, iOS, and the web.  
- **Authentication**: Secure and scalable authentication powered by Firebase.  
- **Cloud-Based Storage**: Attendance data is securely stored and managed using Firebase's Realtime Database or Firestore.  
- **In-App Purchases**: Monetized with **RevenueCat**, offering premium features like advanced analytics and custom reports.  
- **Customizable Groups**: Manage attendance for classes, teams, or departments effortlessly.  
- **Insights & Reporting**: Generate detailed attendance reports in PDF or Excel formats.

## Resume Highlights  

- Built a Flutter + GetX cross-platform attendance tracker with Firebase Auth/Firestore for user, subject, and log persistence.  
- Created an AI attendance assistant powered by Gemini API that answers natural-language questions using contextual subject stats.  
- Implemented premium gating with in-app purchases (in_app_purchase) including restore flows and persisted premium state.  
- Designed attendance analytics UI: overall dashboard, search/filterable subject cards, detailed logs, and bulk actions.  

## Screenshots  

<div style="display: flex; flex-wrap: nowrap; gap: 10px;">
  <img src="assets/01.png" alt="Home Screen" width="200" />
  <img src="assets/02.png" alt="Attendance Report" width="200" />
  <img src="assets/03.png" alt="NLQ" width="200" />
  <img src="assets/04.png" alt="Screens" width="200" />
  <img src="assets/05.png" alt="Screens" width="200" />
</div>


## Tech Stack  

- **Frontend**: Flutter  
- **Natural Language Processing**: Gemini for AI-powered natural language queries  
- **Backend**: Firebase (Authentication, Database Storage)  
- **In-App Purchases**: in_app_purchase for native store billing and premium gating  

## Installation  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/saquibjawedbit/trackify.git  
   cd trackify
   ```
2. Install dependencies:  
   ```bash
   flutter pub get
   ```
