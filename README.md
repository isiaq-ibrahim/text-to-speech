🗣️ Text-to-Speech Python Program
This repository contains a simple Text-to-Speech (TTS) Python program.
The program takes user input as text and converts it into a computer-generated voice using the `pyttsx3` library.





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
