# PDF to Speech & Speech to Text Converter (Python)

This project is a simple Python-based application that demonstrates **PDF to audio (text-to-speech)** and **speech-to-text** conversion using Python libraries and a basic graphical user interface.

The repository contains two Python scripts, each focusing on a different approach to converting text and speech.

---

## Project Overview

The main goal of this project is to:
- Convert **PDF file content into spoken audio**
- Convert **spoken voice input into text**
- Provide a basic GUI for user interaction

This project is intended for **learning and experimentation purposes**, focusing on Python libraries related to text processing, speech recognition, and GUI development.

---

## Files in This Repository

### 1. `pdf_to_speech.py`
- Converts text from a selected **PDF file into audio**
- Uses a file dialog to select the PDF
- Reads extracted text using a text-to-speech engine
- Allows basic control over speech rate and voice

### 2. `PDF to audio _ vice versa_DataFlair.py`
- GUI-based application built using **Tkinter**
- Supports:
  - Speech to Text conversion
  - Text to Speech conversion
- Allows reading text from `.txt` files
- Uses microphone input for speech recognition
- Designed for interactive usage

---

## Technologies & Libraries Used

- Python  
- Tkinter (GUI)  
- PyPDF2  
- pyttsx3  
- SpeechRecognition  
- win32com.client (Windows Text-to-Speech)  

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-name>
   ```
2. Install required dependencies:
   ```
   pip install pyttsx3 PyPDF2 SpeechRecognition pypiwin32
   ```
3. Run any script:
   ```
   python pdf_to_speech.py
   ```

## Note:
- Microphone access is required for speech recognition
- Internet connection may be needed for speech-to-text functionality
- Best supported on Windows OS

## Use Cases:
- Learning text-to-speech and speech-to-text in Python
- Understanding PDF text extraction
- Practicing GUI development with Tkinter

## Author
- Developed for learning and practice purposes.

## Disclaimer
- This project is intended for educational use only and may require further improvements for production-level usage.
