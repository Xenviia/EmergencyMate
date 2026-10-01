EmergencyMate

EmergencyMate is an Android application designed to provide users with quick access to emergency information, communication tools, and essential resources through a single mobile platform.

The application was developed as a university project, with a focus on Android development, user authentication, REST API integration, database management, and mobile interface design.

OVERVIEW

EmergencyMate brings together several emergency-related resources in one application.

Users can create an account, log in, and access different sections from the main menu, including emergency numbers, emergency alerts, emergency protocols, a virtual emergency kit, an interactive map, and emergency-related news.

FEATURES

* User registration
* User login
* Emergency numbers
* Emergency alert section
* Emergency protocols
* Virtual emergency kit
* Interactive map
* Emergency news
* Main navigation menu
* Bottom navigation

AUTHENTICATION

The application includes a registration and login system connected to the EmergencyMate backend API.

The authentication flow is:

Android Application
|
v
Retrofit
|
v
EmergencyMate API
|
v
SQL Server

Users can register using their name, surname, email, and password.

The Android application sends authentication requests to the ASP.NET Core API, which handles communication with the database.

TECHNOLOGIES

Mobile Application

* Kotlin
* Android Studio
* XML
* ConstraintLayout
* Retrofit
* Gson
* Android SDK

Backend Integration

* ASP.NET Core Web API
* REST API

Database

* Microsoft SQL Server

Development Tools

* Git
* GitHub
* Android Emulator

APPLICATION STRUCTURE

EmergencyMate

├── LoginActivity
├── RegisterActivity
├── MenuInicio
├── ApiClient
├── ApiService
├── LoginRequest
├── LoginResponse
├── activity_login.xml
├── activity_register.xml
└── Resources

API COMMUNICATION

Retrofit is used to handle communication between the Android application and the EmergencyMate API.

The API provides the backend services required for user authentication and data management.

The application uses the backend rather than connecting directly to the SQL Server database.

APPLICATION FLOW

Login
|
v
Authentication
|
v
Main Menu
|
├── Emergency Numbers
|
├── Emergency Alert
|
├── Emergency Protocols
|
├── Virtual Emergency Kit
|
├── Interactive Map
|
└── Emergency News

USER INTERFACE

The application uses XML layouts and ConstraintLayout to build its interface.

The main navigation includes a bottom navigation bar that allows users to move between the main sections of the application.

The interface was designed to keep emergency-related information accessible and easy to navigate.

PROJECT GOALS

This project was developed to gain practical experience in:

* Android application development with Kotlin
* XML-based user interface development
* REST API integration
* Client-server communication
* User authentication
* Backend integration
* Database management
* Mobile application architecture
* Git and GitHub version control

RELATED PROJECT

EmergencyMate uses a separate ASP.NET Core backend API.

EmergencyMateAPI:
https://github.com/Xenviia/EmergencyMateAPI

FUTURE IMPROVEMENTS

Potential future improvements include:

* Google authentication
* Facebook authentication
* Push notifications
* Improved location-based services
* Real-time emergency information
* Additional emergency resources
* Expanded map functionality

AUTHOR

Hilary Rodríguez

Software Development Student
