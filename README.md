# Desktop-Virtual-Assistant
# Desktop Virtual Assistant Using Voice Recognition


# Project Description
This project involves the development of a personal desktop virtual assistant capable of performing a range of tasks through voice commands.
By leveraging speech recognition, natural language processing, and task execution modules, this virtual assistant delivers a seamless and interactive user experience.

# Key Functionalities

1. Voice Recognition
Implemented using the speech_recognition library to convert user voice commands into text.
Enhanced accuracy with dynamic adjustments for ambient noise.

2. Task Execution
Email Sending: Securely handles user credentials to send emails via SMTP (smtplib) with support for subject and body inputs.
Wikipedia Search: Fetches concise information from Wikipedia using its API based on user queries.
Music Playback: Plays audio files using pygame with provisions for dynamic file selection.
Online Search: Opens YouTube and Google search results for user-defined queries via webbrowser.
Calculator: Performs basic arithmetic operations (addition, subtraction, multiplication, and division) through voice input.

3. Interactive Features
Greeting Module: Greets the user based on the current time (morning, afternoon, or evening).
Name Customization: Allows the user to rename the assistant dynamically.
Fallback Suggestions: Provides helpful feedback when encountering unrecognized commands.

4. Implementation
Programming Languages: python-3.7.1-amd64

# Libraries/Tools Used:
PyAudio-0.2.11.win-amd64-py3.7

pyttsx3 (Text-to-Speech)

speech_recognition

smtplib

pygame
wikipedia
datetime, os, and webbrowser

This project demonstrates a foundational implementation of a virtual assistant capable of streamlining everyday tasks using natural voice interactions. It provides a robust and extensible framework for future enhancements, such as advanced NLP integration and GUI support.
