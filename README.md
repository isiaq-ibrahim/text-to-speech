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
- pywin32 library

You can install pyttsx3 using pip:
```bash
pip install pyttsx3
```

You can install pywin32 using pip:
```bash
pip install pywin32
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

### 📜 Source Code

#### Code 1

Before computing the final program, I built a text-to-speech Python program with a predefined text and doesn't accept input from the user.

```bash
import pyttsx3

engine = pyttsx3.init()
engine.say("This is my eight project on learning Python")
engine.runAndWait()
```

When I started this Python project, my Text-to-Speech program could only speak a hardcoded sentence. It was simple and exciting to see it work!
Today, I’ve taken that initial idea further — now my program allows real user interaction, taking any text input and instantly converting it to speech.
Looking back, it’s amazing to see the growth from writing static code to creating a dynamic, user-driven application.
Small steps, consistent practice, and curiosity truly make a difference! 🚀

#### Code 2

The code below takes input from the user, making my program much more dynamic and practical.

```bash
import pyttsx3

data = input("Enter the text you want to convert to speech\n")

engine = pyttsx3.init()
engine.say(data)
engine.runAndWait()
```

✨ Key Differences:
```
| Aspect                     |         Code 1                                   | Code 2                                          |
|----------------------------|--------------------------------------------------|-------------------------------------------------|
| Input Source               |         Hardcoded text inside the code           |   Dynamic user input through input() function   |
| Flexibility                | Can only speak one specific, predefined sentence |   Can speak any text entered by the user        |
| User Interaction           | No interaction — program simply runs and speaks  | Interactive — asks the user for custom input    |
| Practicality               | Very basic and limited use case                  | More practical, reusable, and user-friendly     |
| Learning Progress          | Focused on syntax and basic usage of `pyttsx3`   | Advanced to adding interactivity and real-world usability  |
```
