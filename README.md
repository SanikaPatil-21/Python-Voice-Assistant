# Voice Assistant Using Python

## 1. Project Overview
The Voice Assistant is a Python-based application that listens to spoken commands, processes them, and responds using speech.

## 2. Objectives
- Recognize voice commands through a microphone.
- Respond to users using text-to-speech.
- Provide the current time and date.
- Open websites using voice commands.
- Perform basic tasks through voice interaction.

## 3. Technologies Used
- Python
- SpeechRecognition
- PyAudio
- pyttsx3
- datetime
- webbrowser

## 4. Features
- Voice-based greeting.
- Current time announcement.
- Current date announcement.
- Open Google.
- Open YouTube.
- Help command.
- Exit command.

## 5. Installation
Install the required libraries using:

pip install -r requirements.txt

## 6. How to Run
Execute the following command:

python voice_assistant.py

## 7. How It Works
1. The assistant initializes the text-to-speech engine.
2. It listens to audio through the microphone.
3. SpeechRecognition converts the audio into text.
4. The program identifies the requested command.
5. The corresponding action is performed.
6. The assistant speaks a response.

## 8. Example Commands
- Hello
- What is the time?
- What is today's date?
- Open Google
- Open YouTube
- Help
- Exit

## 9. Limitations
- Online speech recognition requires an internet connection.
- Recognition accuracy depends on microphone quality and background noise.
- The assistant supports a predefined set of commands.

## 10. Conclusion
This project demonstrates how Python can be used to develop a simple voice-controlled assistant that performs basic tasks and responds through speech.
