# SPEECH-RECOGNITION-SYSTEM
Company Name:CodTech Company

Name:Abinaya K

Intern ID :CT04DG2129

Domain:AI

Duration:4 Weeks

Mentor:Neela Santosh

# 🎙️ Task 2 – Speech-to-Text Converter using Python

This project is part of my **CodTech AI Internship**.  
The objective is to develop a Python-based tool that transcribes spoken audio into text using the Google Speech Recognition API.

---

## 📌 Objective

To build a simple tool that:
- Accepts a `.wav` audio file
- Converts the speech content into text
- Displays and optionally saves the transcription

---

## 🚀 How It Works

This tool uses the `SpeechRecognition` library, which sends audio to Google's free Web Speech API for transcription.

### ✅ Key Features:
- Takes WAV audio file as input
- Transcribes entire file content to text
- Handles basic errors (file not found, unclear audio)
- Allows saving the transcription to a `.txt` file

---

## ⚙️ Requirements

Install the required library:

```bash
pip install SpeechRecognition
```

You also need a `.wav` file (mono-channel preferred).

---

## 🧠 How to Run

```bash
python speech_to_text.py
```

When prompted:

- Enter the full path to your WAV file (e.g., `speech_demo.wav`)
- View or save the generated text

---

## 🧪 Example

### 🎧 Input:

`speech_demo.wav` – audio that says:

> "This is a test for the CodTech AI internship speech recognition task."

### 📝 Output:

```
This is a test for the CodTech AI internship speech recognition task.
```

---

## 📸 Output Screenshot

![Image](https://github.com/user-attachments/assets/74f0a74e-2041-4e47-8723-b932cd76601b)
---

## 📁 Files Included

- `speech_to_text.ipynb` – Python script for Task 2
- `speech_demo.wav` – Sample audio input
- `README.md` – This documentation file

---

## 📚 Libraries Used

- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/)

---

## 🙋‍♀️ Author

**Abinaya K**  
B.Tech Information Science and Engineering  
Specialization: AI & Robotics

---

## 🔗 Internship

CodTech Artificial Intelligence Internship (June 2025)
