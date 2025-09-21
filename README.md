☁️ Contact Collector Cloud
A simple, secure, and cloud-based contact management application built with Firebase. This project allows users to sign in, save their contacts to the cloud, and access them from anywhere.

🚀 Features
🔑 Secure Authentication: Users can sign in securely using their Google account via Firebase Authentication.

📝 CRUD Functionality: Full Create, Read, Update, and Delete capabilities for managing contacts.

☁️ Cloud Storage: All contact data is stored in Firebase Firestore, ensuring data is safe and synced across devices.

🔒 User-Specific Data: Firestore security rules are implemented to ensure users can only access their own contacts.

🌐 Hosted Live: Deployed and accessible online through Firebase Hosting.

🛠️ Tech Stack
Frontend: HTML, CSS, JavaScript

Backend & Database: Firebase Firestore

Authentication: Firebase Authentication (Google Sign-In)

Hosting: Firebase Hosting

📦 Project Setup
To run this project locally, follow these steps:

Clone the repository:

git clone [https://github.com/GauriSasikumar/contact-collector-cloud.git](https://github.com/GauriSasikumar/contact-collector-cloud.git)

Navigate to the project directory:

cd contact-collector-cloud

Set up Firebase:

Create a new project on the Firebase Console.

Set up Firestore and Authentication (enable Google Sign-In).

In your index.html or a new script.js file, replace the placeholder Firebase configuration with your own project's config keys.

Run the project:

You can open the public/index.html file directly in your browser.

For a more robust setup, you can use the Firebase CLI to serve the project locally:

# Install Firebase CLI if you haven't already
npm install -g firebase-tools

# Serve the project
firebase serve
