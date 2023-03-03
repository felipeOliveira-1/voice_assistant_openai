# Python AI Voice Assistant using OpenAI and Speech Recognition
This project is a Python AI Voice Assistant that uses OpenAI's GPT-3 to generate responses to user input and text-to-speech technology to respond to user input with spoken responses. Speech recognition is used to transcribe the user's voice input to text, which is then used as input for the OpenAI model.

## Installation
Before running the program, you must first install the required libraries:

openai
pyttsx3
speech_recognition
To install these libraries, run the following command:
``
pip install openai pyttsx3 SpeechRecognition
``
## Usage
To use the AI Voice Assistant, simply run the jarvis_voice.py script. The program will listen for the user to say "Jarvis" to initiate a voice command. Once initiated, the program will record the user's voice input, transcribe it to text, generate a response using OpenAI's GPT-3, and then speak the response back to the user.

The program uses a female English voice by default, but this can be changed by modifying the setProperty method of the pyttsx3 engine. To change the voice to a male English voice, change the voices[1].id argument to voices[0].id in the following line:

engine.setProperty('voice', voices[1].id) 0 is for the male voice. To change the language of the voice, modify the setProperty method argument to the desired language code. For example, to change the language to French, change the argument to 'fr'.

## Credits
This project was created by [Felipe Oliveira](https://github.com/felipeOliveira-1)  with the help of OpenAI's GPT-3, pyttsx3, and speech_recognition libraries.
