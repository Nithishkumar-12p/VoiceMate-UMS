# VoiceMate-UMS
VoiceMate UMS is a Python-powered voice assistant designed for smart automation and secure interactions. It recognizes your speech, talks back like a virtual buddy, opens your favorite websites, and even sends OTPs securely via email—all through voice commands.

This project showcases the power of integrating AI voice interaction, web automation, and email authentication in one sleek system. Whether you're a developer exploring AI or a student building real-world projects, VoiceMate UMS is your go-to assistant!

🌟 Key Features

Feature	Description
🎤 Voice Command Recognition	Uses Google’s Speech Recognition API to listen and understand your speech in real time.
🔊 Text-to-Speech Interaction	Replies back to the user using pyttsx3 – a natural-sounding voice engine.
🌍 Website Launcher	Open Amazon, Flipkart, and custom sites hands-free.
✉️ OTP Sender	Securely sends OTPs to an email address using a dedicated module.
💬 Conversational Assistant	Responds to casual user queries like “How are you?” or “Help me.”
🚀 Easy Shutdown	Voice command to terminate the assistant gracefully.
🛠️ Technologies Used
Python 3.8+

speech_recognition – For converting speech to text

pyttsx3 – For voice output

webbrowser – For opening URLs via commands

pyaudio – For accessing the microphone

Custom OTP module – Sends OTP emails to provided addresses
