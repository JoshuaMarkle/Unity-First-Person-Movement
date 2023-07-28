<h1 align="center">Advanced First Person Movement (Unity)</h1>

A fast paced force based movement system that is designed around continous momentum.

## 🛠 Breakdown

This system is broken down into two scripts: the **Player Movement** and the **Camera Controller**. Both are attached to the player and specialize in different things. The Player Movement handles the actual positioning and inputs of the player while the Camera Controller uses context from the Player Movement to procedurally move the camera.

### 💨 Player Movement:
- Basic force based (rigidbody) movement
- Sliding
- Wallrunning & Walljumping
- Vaulting
- Dashing
- Ground Pound/Slam

### 🎥 Camera Controller:
- Basic look
- Landing feedback
- Head Tilting
- Peaking
- Camera Shake

### 🎮 Input System
There is a script called the Input Master that by default, uses unity's new input system. This makes it easy for the Player Movement to support controllers and other input devices. If you rather use the unity's default input system, there are instructions within the Input Master in order to only support the default movement system.

## 📄 License & Distrobution
This project is **Unlicensed**! Anyone is free to copy, modify, publish, or distribute this software for any purpose, commercial or non-commercial, and by any means. If you want to credit me ❤️, go ahead but I do not require it.
