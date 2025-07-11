# FaceAccess: Firebase Access Logs Management App

## Overview

**FaceAccess** is a Flutter mobile application that connects to your Firebase backend for real-time monitoring and management of door access logs. It allows administrators to:

- Authenticate securely via Firebase Authentication.
- Receive real-time notifications (both door access and intruder alerts).
- Filter, search, and export historical access logs.
- Inspect full details of each access event, including timestamps and captured images.

The app works in tandem with your Face Recognition Door System which logs events into Firebase Firestore and triggers alerts via Firebase Cloud Messaging.

---

## Features

- ✅ Admin Login using Firebase Authentication
- ✅ Real-time access logs from Firestore (live update via streams)
- ✅ Tab navigation: Allowed Access & Intruder Access
- ✅ Powerful search and date range filtering
- ✅ Export access logs as CSV files directly from mobile
- ✅ Receive real-time push notifications via Firebase Messaging
- ✅ Detailed view for every access log entry, including captured image (if available)

---

## Technology Stack

| Technology       | Purpose                                |
|-------------------|-----------------------------------------|
| Flutter           | Cross-platform mobile app (Dart)        |
| Firebase Auth     | Admin authentication                   |
| Firestore         | Real-time access log database          |
| Firebase Messaging| Real-time alerts (notifications)       |
| Cloud Firestore SDK | Firestore data streaming            |
| CSV               | CSV exporting for logs                 |
| Share Plus        | Native file sharing from mobile        |
| Path Provider     | File system access for CSV storage     |

---

## Setup Instructions

### Prerequisites

- Flutter SDK installed (stable version recommended)
- Firebase project already configured (same one used in backend system)
- Valid `firebase_options.dart` file (generated by FlutterFire CLI)

### Clone the Repository

```bash
git clone https://github.com/Rania334/FaceAccessApp.git
cd FaceAccessApp
