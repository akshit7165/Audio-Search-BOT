 # AI Voice Assistant Bot

This project implements an AI voice assistant bot that can listen to user's voice commands, transcribe the audio using speech recognition and perform relevant actions like web searches.

## Features

- Listens to user's voice commands through the microphone  
- Saves the recorded audio in .wav files  
- Splits the long audio into smaller chunks for improved speech recognition accuracy using PyDub library   
- Performs speech to text conversion on the audio chunks using a speech recognition library    
- Combines the converted text from all chunks to get the most accurate transcription
- Performs web searches based on the converted text query using the googlesearch package  
- Opens the resulting URLs from the web search in the default browser using the webbrowser module, providing a seamless search experience.

## Technologies Used

- Python
- PyDub library - For opening and splitting audio files   
- Speech Recognition library - For speech to text conversion
- googlesearch package - For finding relevant web search results    
- webbrowser module - For opening URLs in the default browser

That's it! You now have a functional AI voice assistant bot built with Python.
