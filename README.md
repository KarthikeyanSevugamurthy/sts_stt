# Voice Translation and Playback

This Python script captures voice input, translates it to a specified language, and then plays the translated text back to the user. It uses several libraries including `speech_recognition`, `googletrans`, `gtts`, `pyttsx3`, and `playsound`.

## Prerequisites

Make sure you have the following Python packages installed:

- `playsound`
- `speech_recognition`
- `googletrans`
- `gtts`
- `pyttsx3`
- `pyaudio` (for microphone access)

You can install these using pip:

```bash
pip install playsound speech_recognition googletrans gtts pyttsx3 pyaudio
```

## How It Works
Voice Capture: Captures voice input from the microphone.
Language Selection: Asks the user for the target language to which the text should be translated.
Translation: Translates the captured text into the selected language using Google Translator.
Playback: Converts the translated text to speech and plays it back.
``

## Usage
Run the script:
python voice_translation.py
Speak the text you want to translate when prompted.

Specify the target language when prompted.

The translated text will be spoken back to you.

## Example:
```
listening.....
Recognizing.....
The User said Hello
Enter the language in which you want to convert: Ex. Hindi , English , etc.
Say something like: French
```
