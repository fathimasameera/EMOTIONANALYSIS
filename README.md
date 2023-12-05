# Emotion Analysis Project

This project is a simple emotion analysis application with voice recording and sentiment analysis features.

## Introduction

This project aims to provide a basic GUI application for emotion analysis. Users can record their voice, perform sentiment analysis on the recorded voice, and view the emotion detected.

## Features

- **User Authentication:** Login system to access the main application.
- **Voice Recording:** Record voice with a specified duration.
- **Sentiment Analysis:** Analyze the sentiment of the recorded voice or pre recorded audio files using NLTK.
- **Graphical User Interface (GUI):** Built using Tkinter for a user-friendly experience.

## Project Structure

- **EMOTIONANALYSIS**
  - **EMOTION**
    - **Admin.py:** Contains the `AdminHome` class for the main application window.
  - **login.py:** Main entry point for the application.
  - **out.wav:** Audio file created during the voice recording process.
  - **new.wav:** Recorded audio file containing the voice data.
  - **README.md:** Documentation for the project.

## Usage

### Running the Application
- Run the login.py script
- Enter your username and password.
- Record your voice or analyse the sentiment of a pre-recorded audio file.

## Dependencies

- **mysql-connector:** For MySQL database interaction.
- **tkinter:** GUI toolkit for the application.
- **sounddevice:** For recording audio.
- **scipy:** For working with audio files.
- **soundfile:** Used for reading and writing sound files.
- **nltk:** For sentiment analysis.
- **speech_recognition:** For working with audio files and speech recognition.

