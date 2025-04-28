# 🗣️ Text-to-Speech Python Program

This repository contains a simple Text-to-Speech (TTS) Python program.

The program takes user input as text and converts it into a computer-generated voice using the `pyttsx3` library.

### 🚀 Features
- Converts any text input into speech
- Works offline (no internet connection needed)
- Easy to run and modify

### 🛠️ Requirements
- Python 3.x
- pyttsx3 library

You can install pyttsx3 using pip:
```bash
pip install pyttsx3
```

### 📄 How to Use
1. Clone this repository:
```bash
git clone https://github.com/isiaq-ibrahim/text-to-speech.git
```

2. Navigate to the project directory:
```bash
cd text-to-speech
```

3. Run the Python program:
```bash
python text_to_speech.py
```

```bash
import pyttsx3

engine = pyttsx3.init()
engine.say("This is my eight project on learning Python")
engine.runAndWait()
```



```bash
import pyttsx3

data = input("Enter the text you want to convert to speech\n")

engine = pyttsx3.init()
engine.say(data)
engine.runAndWait()
```
