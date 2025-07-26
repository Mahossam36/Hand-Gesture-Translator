# Hand-Gesture-Translator
A smart system that converts real-time hand gestures into text and speech using machine learning. It recognizes English and Arabic letters, numbers, and common words. Built with Python, it features a GUI, supports audio output, and optionally integrates with a robotic arm via network connection.
# ✋ Hand Gesture Translator

This project translates **hand gestures into text and speech**. It supports:

- English letters (A–Z)
- Arabic letters (أ–ي)
- Numbers (0–9)
- Some common English words

It helps people with hearing or speaking difficulties by turning their gestures into readable and spoken words.

---

## 🔍 What It Does

- 📷 Detects your hand in real time using your webcam  
- 🧠 Uses machine learning to understand your gesture  
- 💬 Shows the result on screen and speaks it out loud  
- 🤖 Can also send the result to a robotic arm over the network  

---

## ⚙️ What It’s Built With

- **Python** for programming  
- **Tkinter** for the app interface  
- **MediaPipe** and **OpenCV** to find your hand  
- **scikit-learn** for machine learning  
- **gTTS / pyttsx3 / pygame** to speak the output  
- **WebSocket** to connect with a robot (optional)

---


## 🏆 Awards & Recognition

- 🥉 Won 3rd place in a university AI and robotics competition  
- 📱 Project combines AI, machine learning, IoT, and a user-friendly app  

---

## 🧠 How It Works

1. **Camera** detects your hand using MediaPipe  
2. Extracted **features** are passed to a machine learning model  
3. The model **predicts** the correct gesture  
4. The result is **shown and spoken**  
5. *(Optional)* It can be sent to a robot arm through WebSocket

---

