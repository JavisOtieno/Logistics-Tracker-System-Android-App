# Logistics Tracker System – Android App

An Android mobile application for real-time logistics and trip tracking. Designed for drivers and field agents to manage trips, customers, orders, stopovers, and live location updates. Works with the companion Laravel web dashboard.

---

## Overview

**Logistics Tracker System** enables logistics teams to:

- Create and manage trips
- Add customers and stopovers
- Track orders (including pending orders)
- Share live GPS location in the background
- Start and end trips
- View trip history and details

The app communicates with a Laravel backend via REST API and supports offline-friendly local storage for key data.

---

## Key Features

- **User Authentication** – Secure login with token-based authentication
- **Trip Management** – Create trips, start/end trips, view trip details
- **Customer Management** – Add and select customers
- **Order Tracking** – View pending orders and order details
- **Stopovers** – Add intermediate stopovers to trips
- **Live Location Tracking** – Background GPS updates using WorkManager and Location Services
- **Maps Integration** – Google Maps support for location visualization
- **Profile Management** – View and manage user profile
- **Crash Reporting** – Firebase Crashlytics integration
- **Offline Support** – Local SQLite storage for resilience

---

## Tech Stack

| Component          | Technology                          |
|--------------------|-------------------------------------|
| Language           | Java                                |
| Min SDK            | 27                                  |
| Target SDK         | 34                                  |
| Networking         | Retrofit 2 + OkHttp + Gson          |
| Image Loading      | Picasso                             |
| Location           | Google Play Services Location       |
| Maps               | Google Maps                         |
| Background Tasks   | WorkManager                         |
| Crash Reporting    | Firebase Crashlytics + Analytics    |
| Local Storage      | SQLite + Android Security Crypto    |
| UI                 | Material Design + ConstraintLayout  |

---

## Project Structure
