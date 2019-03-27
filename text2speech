import pyttsx3
engine = pyttsx3.init()
text="This is the text i will read"
voices = engine.getProperty('voices')
engine.setProperty('voice', voices[1].id) # use 0 for male voice
engine.setProperty('rate', 180) # change the speed
engine.setProperty('volume', 0.8) # change the volume range 0-1
engine.say(text)
engine.runAndWait()
engine.stop()
