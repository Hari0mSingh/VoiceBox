# VoiceBox 🔊

A simple yet powerful Python-based Text-to-Speech (TTS) application that converts your text input into natural-sounding speech.

## Features

- 🎯 Simple and intuitive command-line interface
- 🔊 Clear and natural speech output
- ⚡ Adjustable speech rate and volume
- 🔄 Continuous conversation mode
- 🛑 Easy exit command

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Hari0mSingh/VoiceBox.git
cd VoiceBox
```

2. Install required packages:
```bash
pip install pyttsx3
```

## Usage

1. Run the script:
```bash
python speaker.py
```

2. Enter the text you want to convert to speech when prompted.

3. To quit the program, simply type 'q' when prompted.

## Configuration

The application comes with default settings:
- Speech Rate: 120 words per minute
- Volume: 1.2 (20% louder than default)

You can modify these settings in the code:
```python
engine.setProperty('rate', 120)    # Adjust speech rate
engine.setProperty('volume', 1.2)  # Adjust volume
```

## Requirements

- Python 3.6+
- pyttsx3

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
- Open a Pull Request
