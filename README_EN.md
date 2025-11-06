# ![RePlaced](assets/RePlaced_blue_logo.png)

![Python](https://img.shields.io/badge/python-v3.10-blue.svg) ![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg) ![React Native](https://img.shields.io/badge/-React_Native-05122A?logo=react&style=flat)


**RePlaced** is a student project developed in just a few weeks, aiming to make parking access and location simpler and more accessible to everyone.  
Thanks to **OpenData APIs**, **publicly available CCTV cameras**, and **artificial intelligence**, **finding a parking spot has never been easier!**

---

## The RePlaced Application

### Description:
RePlaced is currently an **Android application**.  
To find an available parking spot nearby, nothing could be simpler — RePlaced automatically detects your position.  
When you see a marker appear on the map, just tap it to **reserve the spot** and navigate there.

![App demo image 1](assets/app_show_1.png)

### Features:
- **Real-time parking availability:**
  - Users can get an overview of available parking spaces nearby in just a few seconds.
- **Parking spot reservation:**
  - Once a spot is reserved, it becomes unavailable to other users.
- **User registration & login:**
  - In the settings, you can sign up and log in to enable future features such as parking reservation.
- **App themes:**
  - Users can toggle between light and dark mode.
- **Navigation:**
  - At any time, users can open the route in *Google Maps* to drive directly to the chosen parking spot.
- **Nearest parking spot:**
  - With the *magnifier* button, the app automatically locates and highlights the nearest available spot.

---

## Artificial Intelligence & APIs
RePlaced relies partly on **AI-powered image analysis**.  
It fetches video streams from **public CCTV cameras**, extracts a frame every minute, and analyzes it.  

In the app, the markers corresponding to camera data appear **in red**.  
Other markers — **blue ones** — represent parking areas fetched from **OpenData APIs**.  
The map is updated **in real time**, combining both sources for optimal accuracy!

![AI demo](RePlaced-Website/assets/parkingOCR.png)

**Currently integrated OpenData sources:**
- [Lille](https://opendata.lillemetropole.fr)
- [Marseille / Aix-en-Provence](https://data.ampmetropole.fr)
- [Montpellier](https://portail-api-data.montpellier3m.fr)

---

## Installation
You can install the Android app directly from the [GitHub repository](./RePlaced-Website/RePlaced.apk)  
or through our [RePlaced website](http://51.75.142.229:3001/).

Simply open the downloaded file on your Android device using the file explorer  
and launch it via the **Package Installer**.
