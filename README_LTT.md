# Language Translation Tool

CodeAlpha AI Internship, Task 1.

A web app where you type text, pick a source and target language, and get the translation on screen.

## Features
- Text input with source and target language selectors (21 languages, including Hindi, Urdu and other Indian languages)
- Translation through the MyMemory Translation API (free, no API key needed)
- Swap languages button
- Copy button for the translated text
- Text-to-speech for both the input and the translation (browser Web Speech API)
- Character counter and clear error messages

## How to run
1. Download or clone this repository.
2. Open `index.html` in any modern browser (Chrome or Edge recommended).
3. An internet connection is required.

No installation or build step is needed.

## Tech used
HTML, CSS, JavaScript, MyMemory REST API, Web Speech API

## Notes
- MyMemory limits each request to 500 characters and gives a daily free quota for anonymous use.
- To use Google Translate or Microsoft Translator instead, replace the `fetch` URL in the `translate()` function with their endpoint and add your API key.
- Text-to-speech voices depend on the languages installed on your device.

## Author
Ayan Kumar, CodeAlpha AI Intern
