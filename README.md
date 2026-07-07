# 🏋️ Real-Time AI Gym Trainer

An intelligent fitness assistant that acts like a virtual personal trainer using Computer Vision, Artificial Intelligence, and Real-Time Pose Detection.

The system tracks body movements through a webcam, identifies exercises, counts repetitions, evaluates exercise form, and provides AI-generated coaching feedback with voice guidance.

---

## 🚀 Features

### 🎯 Real-Time Pose Detection
- Tracks body landmarks using AI-based pose estimation.
- Monitors user movements through webcam feed.

### 💪 Exercise Recognition
Supports:
- Squats
- Push-Ups
- Bicep Curls

### 🔢 Automatic Rep Counting
- Counts repetitions in real time.
- Tracks workout performance accurately.

### ✅ Form Correction System
- Detects incorrect posture and movement patterns.
- Provides corrective feedback to improve exercise form.

### 🤖 AI Coaching Assistant
- Generates personalized workout feedback.
- Acts as a virtual fitness trainer.

### 🎤 Voice Feedback
- Real-time voice instructions and motivation.
- Trainer-like interaction during workouts.

### 👤 User Authentication
- User login system.
- Secure access to workout records.

### 📊 Workout History Tracking
- Stores workout sessions.
- Tracks progress over time.

---

## 🧠 Why This Project Matters

This project combines multiple modern AI technologies into a practical real-world application:

- Computer Vision for body tracking
- Rule-Based AI for exercise detection
- Real-Time Processing
- Voice Generation
- LLM-Based Coaching

The goal is to make fitness coaching more accessible, affordable, and interactive.

---

## 🏗️ System Architecture

Camera Feed
↓
MediaPipe Pose Detection
↓
Pose Landmark Extraction
↓
Exercise Detection Logic
↓
Rep Counting & Form Analysis
↓
AI Coaching Engine
↓
Voice Feedback + Dashboard Display
↓
Workout History Storage

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|----------|
| Python | Core Programming Language |
| Streamlit | User Interface |
| WebRTC | Real-Time Camera Streaming |
| MediaPipe | Pose Detection |
| OpenCV | Image Processing |
| SQLite | Database Management |
| gTTS | Voice Feedback |
| LLM API | AI Coaching Intelligence |

