# 🐉 AR Image-Tracking Dragon Controller
An interactive Augmented Reality application built with **Unity 2021.3.6f1** and **AR Foundation**.

## 🚀 Overview
This project goes beyond basic AR by combining **Image Tracking** with **Real-time Input**. The application identifies a specific "Dragon" target image in the physical world, spawns a 3D Dragon model, and gives the user full control over its movement using an on-screen **Virtual Joystick**.

## 🛠️ Technical Features
* **AR Image Tracking:** Utilizes `ARTrackedImageManager` to detect and track a specific reference image.
* **Dynamic Prefab Spawning:** Automatically instantiates the 3D Dragon at the exact position and rotation of the tracked image.
* **Joystick Integration:** Features a custom C# movement controller linked to a UI Virtual Joystick.
* **Interactive Movement:** The Dragon can be moved freely around the real-world environment once it has been "summoned" by the image.

## 🕹️ Controls
* **Scan:** Point your phone camera at the Dragon Image Marker.
* **Move:** Use the **On-Screen Joystick** to move the Dragon forward, backward, left, and right.

## 🏗️ Requirements
* **Unity Version:** 2021.3.6f1
* **Mobile OS:** Android (ARCore compatible)
* **AR Foundation:** 4.2.x or higher

## 📂 Key Folders
* `/Assets/Scripts`: C# Logic for movement and tracking.
* `/Assets/ReferenceImages`: Contains the "Dragon" image needed for tracking.
* `/Assets/Prefabs`: The animated Dragon model.

---
**Developed by Kirubel Adisu Firew** *Computer Science Student, Arbaminch University*
