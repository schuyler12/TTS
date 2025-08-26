# TTS
A Working tts (TEXT TO SPEECH) for only windows

# Voice Assistant Demo (`tts.py`)

This is a simple Python voice assistant demo that uses speech recognition and text-to-speech (TTS) to interact with the user via voice commands.

## Features

- **Speech Recognition:** Listens for your voice commands using your microphone.
- **Text-to-Speech (TTS):** Responds using synthesized speech (via `pyttsx3`).
- **Wake Words:** Responds to "Tony Stark", "hello", or "hi" with custom greetings.
- **Continuous Listening:** Keeps listening for commands until you say "stop".
- **Error Handling:** Handles microphone and recognition errors gracefully.

## Requirements

- Python 3.10+
- [PyAudio](https://pypi.org/project/PyAudio/) (for microphone access)
- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/)
- [pyttsx3](https://pypi.org/project/pyttsx3/)

## Installation

1. **Install dependencies:**
    ```bash
    pip install SpeechRecognition pyttsx3 pyaudio
    ```

2. **(Windows only)**  
   If you have trouble installing PyAudio, download the appropriate `.whl` file from [here](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio) and install with:
    ```bash
    pip install path\to\PyAudio‑...whl
    ```

## Usage

1. Make sure your microphone is connected and working.
2. Run the script:
    ```bash
    python tts.py
    ```
3. Speak clearly when prompted. Try commands like:
    - "Tony Stark"
    - "hello"
    - "hi"
    - "stop" (to exit)

## Notes

- The script uses the default system voice for TTS.
- The wake words ("Tony Stark", "hello", "hi") are case-insensitive.
- If the assistant doesn't recognize your speech, it will prompt you to repeat.

## Example

```
I'm listening... Please speak clearly.
You said: hello

Hello! How can I assist you today? SIR
```

## License

This project is
