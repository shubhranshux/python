# AI-Based Voice Assistant

This project is an AI-based voice assistant named Jarvis, built using Python. Jarvis can perform various tasks such as opening websites, playing music, fetching news, and responding to general queries using OpenAI's GPT-3.5-turbo model.

## Features

- **Voice Recognition**: Uses `speech_recognition` to recognize voice commands.
- **Text-to-Speech**: Uses `pyttsx3` and `gTTS` for converting text to speech.
- **Web Browsing**: Opens websites like Google, Facebook, YouTube, and LinkedIn.
- **Music Playback**: Plays songs from a predefined music library.
- **News Fetching**: Fetches the latest news headlines using the News API.
- **AI Responses**: Uses OpenAI's GPT-3.5-turbo model to respond to general queries.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/voice-assistant.git
    cd voice-assistant
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

3. Install `pocketsphinx` for speech recognition:
    ```sh
    pip install pocketsphinx
    ```

## Usage

1. Run the main script:
    ```sh
    python main.py
    ```

2. Say "Jarvis" to activate the assistant and give your command.

## Configuration

- **API Keys**: Replace the placeholder API keys in the script with your own API keys for OpenAI and News API.
- **Music Library**: Update the `musicLibrary` module with your own music links.

## Example Commands

- "Open Google"
- "Play [song name]"
- "What's the news?"

## Dependencies

- `speech_recognition`
- `webbrowser`
- `pyttsx3`
- `musicLibrary`
- `requests`
- `openai`
- `gtts`
- `pygame`
- `os`

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- SpeechRecognition
- pyttsx3
- gTTS
- OpenAI
- Pygame

