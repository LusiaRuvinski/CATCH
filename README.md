CATCH – Connect & Discover

📌 Overview

CATCH is an Android application developed as a Computer Science graduation project at Afeka College of Engineering.

The application is designed to bridge the gap between digital communication and real-life interactions by helping users discover people nearby and connect through their social media profiles in a safe and privacy-focused way.

Unlike traditional social platforms, CATCH encourages spontaneous real world connections while giving users full control over their visibility and personal information.


🎯 Motivation

Meeting new people in places such as universities, conferences, events, cafés, or parties can be difficult.

Many people hesitate to start conversations with strangers, even when they share the same environment.

CATCH was created to reduce this barrier by allowing users to discover nearby people and access the social profiles they have chosen to share, making the first connection easier and more natural.



✨ Features

🔐 Secure user authentication using Firebase Authentication
📍 Real-time nearby user discovery using GPS
👤 User profile creation and customization
🌐 Direct links to social media accounts
🎯 Filter nearby users by age and gender
👀 Live location synchronization through Firebase Cloud Firestore
🔒 Privacy controls, including the ability to hide location
🖼 Profile image upload
⚡ Fast refresh of nearby users



🏗 System Architecture

The application follows a client-cloud architecture.

Frontend:

 Android Studio
ז Java
 XML

Backend:

* Firebase Authentication
* Cloud Firestore

🛠 Technologies Used

* Java
* Android Studio
* Firebase Authentication
* Firebase Cloud Firestore
* Google Location Services
* XML
* Picasso
* Cloudinary


## 📱 How It Works

1. The user creates an account or logs in.
2. The application requests location permission.
3. The user's current location is synchronized with Firebase.
4. Nearby users are detected and displayed in real time.
5. Users can view nearby profiles.
6. Selecting a profile opens the social media links that the user has chosen to share.


🔒 Privacy & Security

* Only authenticated users can access the application.
* Users have complete control over their visibility.
* Communication between the application and Firebase is encrypted using HTTPS (SSL/TLS).
* Users decide which social media accounts to share.


 


