# CollegeConnect

CollegeConnect is a college event management app developed for HackVortex 2025. It connects students and admins, allowing admins to create announcements and manage events, while students can view updates, register for events, and engage with communities.

Problem Statement
Colleges often struggle with efficient event management and communication. Students miss important announcements due to scattered platforms, and admins lack a centralized system to manage events, track engagement, and connect with students. There’s a need for a single platform that streamlines event updates, fosters student engagement, and provides actionable insights for admins.

Solution and Approach
CollegeConnect addresses these issues by providing a unified Android app for college event management. We adopted a role-based approach with separate panels for students and admins, ensuring tailored functionalities. The app uses Firebase for real-time data syncing, enabling instant updates and notifications. A clean, card-based UI ensures ease of use, while features like stats and communities promote engagement. Our iterative development process involved designing XML layouts, integrating Firebase, and planning scalable features like community formation for future growth.

Features
Student Features

View announcements with details (title, category, dates, location).
Register and attend events.
Manage profile (name, email, interest).
Provide feedback on the app.
Logout securely.

Admin Features

Create and manage announcements (category, dates, priority).
View stats (total announcements, active students, today’s posts, engagement rate).
Manage admin profile (name, email, college name).
Navigate to admin profile section.
Logout securely.

Future Scope

Communities formation for interest-based groups.
Real-time chat within communities.
Personalized event recommendations.
Offline mode for announcements.

Tech Stack

Frontend: Android (Java, XML)
Backend: Firebase Realtime Database, Firebase Authentication
Libraries:
Picasso: For loading profile images
Material Components: For UI elements (cards, buttons, text fields)


Tools: Android Studio, Git

Screenshots : 

Please Check the ppt, and other resouces of repository.


Demo Video : Please check the resources of repository.

Watch the demo video on YouTube: CollegeConnect Demo
Run Instructions
Prerequisites

Android Studio (latest version)
Firebase project with Realtime Database and Authentication enabled
Git

Steps

Clone the Repository: https://github.com/Ishuxify/CollegeConnect


Open in Android Studio: Import the project into Android Studio.
Add Firebase Configuration:
Download google-services.json from your Firebase project.
Place it in the app/ directory.


Add Dependencies: Ensure build.gradle includes:implementation 'com.google.firebase:firebase-auth:23.0.0'
implementation 'com.google.firebase:firebase-database:21.0.0'
implementation 'com.squareup.picasso:picasso:2.8'
implementation 'com.google.android.material:material:1.12.0'


Sync and Build: Sync the project with Gradle and build the app.
Run: Deploy the app on an emulator or device (API 21+).


Developed by: IGNOUDuomates Team for HackVortex 2025

