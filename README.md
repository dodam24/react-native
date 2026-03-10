# 📱 React Native App

![React Native](https://img.shields.io/badge/ReactNative-0.73-blue?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-4.x-blue?logo=typescript)
![Platform](https://img.shields.io/badge/platform-iOS%20%7C%20Android-lightgrey)

React Native 기반 크로스 플랫폼 모바일 애플리케이션입니다.  
iOS와 Android에서 동일한 코드베이스로 실행됩니다.

---
<!--
# 🚀 Demo

![Demo](./demo/app-demo.gif)

---
-->
# 📌 Project Introduction

React Native 기반 모바일 앱 아키텍처를 학습하고  
실제 서비스와 유사한 구조를 구현하기 위해 제작한 프로젝트입니다.

### 목표

- React Native 앱 구조 이해
- 재사용 가능한 컴포넌트 설계
- API 연동 및 데이터 처리
- 상태 관리 구조 설계

---

# ✨ Features

### 🔐 Authentication

- 회원가입
- 로그인
- 토큰 기반 인증

### 📄 Data

- API 데이터 조회
- 리스트 화면
- 상세 화면

### 📱 UI

- 재사용 가능한 컴포넌트
- 모바일 반응형 UI

### 🔄 Navigation

- Stack Navigation
- Screen Transition

---

# 🛠 Tech Stack

### Frontend

- React Native
- TypeScript
- React Navigation

### State Management

- Redux Toolkit / Context API

### Networking

- Axios

### Styling

- Styled Components
- React Native StyleSheet

---

# 🧱 Architecture

```
src
│
├── components
├── screens
├── navigation
├── store
├── hooks
├── services
├── utils
└── assets
```

---

# 📂 Folder Structure

```
project-root
│
├── android
├── ios
│
├── src
│   ├── components
│   ├── screens
│   ├── navigation
│   ├── store
│   ├── hooks
│   ├── services
│   └── utils
│
├── App.tsx
└── package.json
```

---

# ⚙️ Environment Variables

`.env`

```
API_URL=https://api.example.com
```

---

# 🚀 Getting Started

## Clone Repository

```
git clone https://github.com/your-username/react-native-app.git
cd react-native-app
```

## Install Dependencies

```
npm install
```

---

# ▶️ Run Application

## Android

```
npx react-native run-android
```

## iOS

```
cd ios
pod install
cd ..
npx react-native run-ios
```

---

# 🐛 Troubleshooting

### Metro Cache Reset

```
npx react-native start --reset-cache
```

### node_modules 재설치

```
rm -rf node_modules
npm install
```
<!--
---

# 👨‍💻 Author

GitHub

```
https://github.com/dodam24
```
-->
