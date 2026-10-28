# Text to Speech Converter

Type text, pick a voice, and have the browser read it aloud — no server, no API key, just the browser's built-in speech engine.


## Features

- Text input area
- Voice selection from the voices available in your browser (defaults to Google US English when present)
- **Convert To Speech** button, with pause / resume for longer text (over 80 characters)
- Works entirely in the browser via the Web Speech API (`speechSynthesis`)

## Tech Stack

- HTML
- CSS
- JavaScript (Web Speech API)

## How to Run

Just open `index.html` in any browser that supports the Web Speech API (Chrome or Edge work best). No build step, no server needed.

```bash
# or serve it locally
python3 -m http.server
# then open http://localhost:8000
```

## Notes

The page references `style.css` and `script.js`, which are not in this repo — the page is self-contained through its inline styles and script, so those missing files do not affect it. Available voices depend on the browser and operating system.
