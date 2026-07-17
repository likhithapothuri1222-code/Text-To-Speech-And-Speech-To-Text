# Speech-to-Text & Text-to-Speech Web App

A modern web application that enables real-time speech-to-text and text-to-speech conversion directly in your browser. Built with Flask and the Web Speech API.

## Features

- **Text-to-Speech (TTS)** — Convert any text to spoken audio using the browser's speech synthesis API
- **Speech-to-Text (STT)** — Transcribe your voice to text using the browser's speech recognition API
- **Clean UI** — Intuitive and responsive web interface
- **No Backend Audio Processing** — Runs entirely on the browser for privacy and speed

## Demo

Visit `http://localhost:5000` after running the app.

## Requirements

- Python 3.8+
- Flask 2.3.0+
- A modern web browser (Chrome or Edge recommended for best speech recognition support)

## Installation

1. Clone or download this repository:
   ```bash
   git clone <your-repo-url>
   cd speech-app
   ```

2. Install dependencies:
   ```bash
   python -m pip install -r requirements.txt
   ```

## Usage

1. Start the Flask server:
   ```bash
   python tts.py
   ```

2. Open your browser and navigate to:
   ```
   http://127.0.0.1:5000
   ```

3. Use the interface:
   - **Text-to-Speech**: Enter text and click "Speak"
   - **Speech-to-Text**: Click "Start Listening" and speak into your microphone

4. Stop the server by pressing `Ctrl+C` in the terminal

## Project Structure

```
.
├── tts.py                  # Flask application entry point
├── requirements.txt        # Python dependencies
├── templates/
│   └── index.html          # Web interface (HTML, CSS, JavaScript)
└── README.md               # This file
```

## Browser Compatibility

| Feature | Chrome | Edge | Firefox | Safari |
|---------|--------|------|---------|--------|
| Text-to-Speech | ✅ | ✅ | ✅ | ✅ |
| Speech-to-Text | ✅ | ✅ | ❌ | ✅ |

## Future Enhancements

- [ ] Multi-language support
- [ ] Speech rate and pitch control
- [ ] Audio output file download (WAV/MP3)
- [ ] Voice selection options
- [ ] Recording and playback history

## License

This project is open source and available under the MIT License.

## Author

Mini Project Team 11
