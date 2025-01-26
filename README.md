# Coqui TTS GenAI: Multilingual Text-to-Speech App

## Overview
The **Coqui TTS GenAI** is a text-to-speech (TTS) application that converts written text into natural-sounding speech. Built using **Coqui TTS** and **Gradio**, this app supports multiple languages and speakers, making it a versatile tool for generating high-quality audio. It also includes a waveform visualization feature to provide a visual representation of the generated speech.

This project was developed as part of my learning journey on **StackUp**, a learn-and-earn platform that empowers individuals to build real-world projects while gaining valuable skills.

## Features
- **Multilingual Support**: Generate speech in multiple languages, including **US English** and **Spanish (LatAm)**.
- **Multiple Speakers**: Choose from a variety of voices, such as **Daisy Studious**, **Sofia Hellen**, and **Asya Anara**.
- **Waveform Visualization**: Visualize the generated speech as a waveform for better analysis.
- **User-Friendly Interface**: Built with **Gradio**, the app provides an intuitive and interactive interface for seamless user experience.

## Preview
Here’s a screenshot of the app in action:

![TTS App Screenshot](./preview.png)

## Technologies Used
- **Python**: The core programming language used for development.
- **Coqui TTS**: For text-to-speech synthesis.
- **Gradio**: For building the interactive user interface.
- **Matplotlib**: For generating waveform visualizations.
- **NumPy**: For numerical computations and audio processing.

## How It Works
1. **Text Input**: The user enters the text they want to convert into speech.
2. **Voice and Language Selection**: The user selects a speaker and language from the available options.
3. **Speech Generation**: The app uses Coqui TTS to generate the speech and saves it as a `.wav` file.
4. **Waveform Visualization**: The app generates a waveform image of the audio for visual analysis.
5. **Audio Playback**: The user can listen to the generated speech directly in the app.
