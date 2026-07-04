# AI Real-Time Gym Coach

An AI-powered fitness application that watches your workout form through a webcam and gives you instant feedback to keep you safe and moving correctly. 

## 🚀 Features
* **Real-Time Form Checking:** Uses computer vision to calculate joint angles (knees, hips, elbows) and instantly checks your form for exercises like Squats and Push-ups.
* **AI Voice Coaching:** Uses an AI language model (Groq LLM) combined with Text-to-Speech to give you live audio corrections without slowing down your video feed.
* **Smooth Dashboard:** Built with a clean interface where live rep counts and workout data update instantly alongside the camera stream.

## 🛠️ Tech Stack
* **Frontend/Deployment:** Streamlit Cloud & Netlify
* **Computer Vision:** Google MediaPipe (Lite Model) & OpenCV
* **Streaming:** WebRTC & OpenRelay Tunnels
* **AI Engine:** Groq LLM & Text-to-Speech (TTS)
