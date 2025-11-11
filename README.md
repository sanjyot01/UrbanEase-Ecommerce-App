# UrbanEase eCommerce Android Application

Android eCommerce app for Individual Project 2 - Following John Horton's Chapter 16 RecyclerView patterns with Firebase Firestore database.

## Features
- Firebase Authentication with email validation
- Firebase Firestore database (8 unique products)
- RecyclerView with Chapter 16 patterns
- Product details page
- Responsive layouts (portrait + landscape)
- Currency symbols on all prices

## Setup Instructions
1. Clone the repository
2. Open in Android Studio
3. Add google-services.json file (see Firebase Setup below)
4. Sync Gradle
5. Run the app

## Firebase Setup
1. Go to https://console.firebase.google.com/
2. Create project "UrbanEase"
3. Add Android app with package: com.urbanease.ecommerce
4. Download google-services.json
5. Place in app/ folder
6. Enable Authentication (Email/Password)
7. Enable Firestore Database (Test Mode)

## Project Structure
- MainActivity: Homepage with logo
- LoginActivity: Firebase Authentication
- ProductActivity: RecyclerView with Firestore data
- ProductDetailActivity: Product details
- ProductAdapter: Chapter 16 ViewHolder pattern
