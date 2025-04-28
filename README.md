"# text-to-speech" 





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
