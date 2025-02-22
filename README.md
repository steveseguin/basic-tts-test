# Browser Text-to-Speech Demo

A lightweight, dependency-free demonstration of browser-based Text-to-Speech capabilities using the Web Speech API.

## Features

- Real-time voice selection from available system voices
- Dark mode UI
- Error handling and status feedback
- No external dependencies
- Cross-browser support

## Demo

[Live Demo](https://steveseguin.github.io/basic-tts-test/) <!-- Add your deployed demo link here -->

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/steveseguin/basic-tts-test.git
```

2. Open `index.html` in a modern web browser

That's it! No build process or installation required.

## Browser Support

The Web Speech API is supported in:
- Chrome 33+
- Edge 14+
- Safari 7+
- Firefox 49+
- Opera 27+

Note: Available voices depend on your browser and operating system. Audio output uses the system's default audio device.

## Usage

1. Select a voice from the dropdown menu
2. Enter text in the textarea
3. Click "Speak" to hear the text
4. Status and error messages will appear below the button

## Technical Details

The demo uses:
- Web Speech API for text-to-speech synthesis
- CSS Variables for theming
- Vanilla JavaScript with no dependencies
- Error handling for unsupported browsers

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## License

MIT License - feel free to use this code in your own projects.

## Acknowledgments

- [MDN Web Speech API Documentation](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API)
- [Can I Use - Speech Synthesis API](https://caniuse.com/speech-synthesis)
