# Bitasmbl-Fitness-Tracker-Dashboard-d2f9e9-Nodar_Mebunia

## Description
Build a web and optional mobile dashboard that tracks user workouts, steps, and calories. The project focuses on integrating APIs, storing data in a database, and displaying interactive charts and statistics.

## Tech Stack
- FastAPI
- Flutter
- PostgreSQL
- React

## Requirements
- Track user workouts, steps, and calorie intake
- Display data visually in charts or graphs
- Allow users to input new workout sessions
- Store user data persistently in a database
- Optionally support mobile-friendly access or apps

## Installation
bash
git clone https://github.com/MrBitasmblTester/Fitness-Tracker-Dashboard.git
cd Fitness-Tracker-Dashboard
# Backend
pip install fastapi uvicorn
# Database
# Setup PostgreSQL and connection string
# Frontend (React)
npm install
# Mobile (Flutter, optional)
flutter pub get


## Usage
bash
# Backend
uvicorn main:app --reload
# Frontend
npm start
# Flutter (optional)
flutter run


## Implementation Steps
1. Define PostgreSQL schema for users, workouts, steps, and calories.
2. Implement FastAPI models and CRUD endpoints for tracking data.
3. Connect FastAPI to PostgreSQL.
4. Build React components for charts and statistics using API data.
5. Implement workout input forms in React.
6. Create Flutter app (optional) consuming the same FastAPI endpoints.
7. Ensure responsive layout for mobile-friendly web access.

## API Endpoints
- POST /workouts
- GET /workouts
- GET /stats