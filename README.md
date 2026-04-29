# 🎮 Top Down Shooter – Unreal Engine 5 Training Project

This repository contains a complete **Top Down Shooter prototype** developed as part of a structured learning journey using Unreal Engine 5.

The project is based on the following training course:  
👉 https://dev.epicgames.com/community/learning/tutorials/nzxl/apprendre-unreal-engine-5-de-a-a-z-formation-debutants  
by Evans Bohl, available on :contentReference[oaicite:0]{index=0} learning platform.

Video Demo: https://youtu.be/FtMCvptPBls

---

## 📌 Project Overview

https://private-user-images.githubusercontent.com/153461032/583277692-dc2979c0-b4e0-4c0e-b668-7194a0420c08.mp4

This project is not just a simple beginner tutorial, but a **deep exploration of Unreal Engine 5 fundamentals and production workflows**.

It covers essential game development systems such as:
- Level design
- Materials & shaders
- Gameplay architecture
- Input systems
- UI & HUD
- Performance considerations
- Animation systems
- Deployment pipeline
- C++ (custom Blueprints)

The final result is a **fully playable Top Down Shooter prototype**.

---

## 🧱 Core Systems & Architecture

### 🧠 Unreal Engine Framework Hierarchy

Understanding Unreal’s object architecture was a key part of this project:

- **Actor** → Base object in the world
- **Pawn** → Possessed entity (player-controlled or AI)
- **Character** → Extended Pawn with movement system
- **Controller** → Handles input and possession logic
- **GameMode / GameState** → Rules and global gameplay state

This structure is fundamental to building scalable gameplay systems.

---

## 🎮 Gameplay System

The gameplay loop includes:
- Player movement (top-down camera perspective)
- Shooting mechanics
- Basic enemy interactions (AI - NavMesh)
- Interaction with the environment

Implemented primarily using:
- Blueprints visual scripting
- Unreal input system
- Component-based architecture

---

## 🎮 Input & Control Mapping

Custom input mapping includes:
- Movement (WASD / controller stick)
- Aim direction (mouse or analog stick)
- Shooting actions
- Camera control (top-down follow system)

Mapped using Unreal Enhanced Input system.

---

## 🎥 Camera System

The camera system is designed for a **Top Down Shooter perspective**:
- Fixed or semi-dynamic top-down view
- Follow behavior
- Rotation-independent movement system

---

## 🧩 Level Design

Level design focuses on:
- Level Design – Blockout & Material Layers
- Gameplay flow and navigation readability
- Enemy/player interaction spaces
- Iterative refinement from prototype to final layout

---

## 🎨 Materials & Shaders

This project explores Unreal’s material system:
- PBR (Physically Based Rendering)
- Material instances for performance optimization
- Environment materials (ground, props, etc.)

---

## 🧩 Blueprints System

A major part of the project relies on Blueprints:
- Gameplay logic implementation
- UI interaction
- Character behavior
- Event-driven programming model

Blueprints allowed rapid iteration without C++.

---

## 🧬 Inheritance & Interfaces

Key programming concepts explored:
- Blueprint inheritance for reusable logic
- Interface usage for decoupled systems
- Component-based design for modularity

---

## 🎬 Animation System

Includes:
- Character animation setup
- Animation Blueprints
- Blend Spaces for smooth movement transitions
- State machines for animation logic

---

## 🔊 Audio System

Basic audio integration:
- Sound effects for actions (shooting, movement, etc.)
- Spatial audio setup (if applicable)
- Event-triggered audio feedback

---

## 🧭 UI / HUD

User Interface system includes:
- Player HUD (health, ammo, etc.)
- Blueprint-based UI logic
- UMG (Unreal Motion Graphics)
- Event-driven UI updates

---

## ⚡ Optimization & Performance Considerations

Introduced concepts such as:
- Efficient use of Blueprints
- Material instance optimization
- Asset management
- Avoiding unnecessary tick functions

---

## 🚀 Deployment / Packaging

The project covers build preparation:
- Packaging for Windows platform
- Cooked content management
- Build configuration (Development / Shipping)
- File size considerations and cleanup

---

## 📚 Learning Outcome

Coming from a Unity background, this project helped highlight key differences:
- C# vs C++ / Blueprints paradigm
- Editor-driven workflow vs code-centric workflow
- Strong integration of tools within the engine
- Different architectural philosophy (Actor-based system)

---

## 🔗 Credits

- Training: Evans Bohl
- Platform: :contentReference[oaicite:1]{index=1} Learning
- Course: Unreal Engine 5 from A to Z (Beginner to Advanced)

---

## 📌 Notes

This project is part of a personal learning journey aimed at:
- Understanding Unreal Engine 5 in depth
- Transitioning from Unity development
- Building production-ready game/immersive environment development skills
