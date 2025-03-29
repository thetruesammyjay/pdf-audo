# Python PDF to Audio Converter

A simple Python script that converts PDF text content into an audio file (MP3) using `pyttsx3` and `PyPDF2` libraries.

## Features

- Extracts text from PDF files
- Converts extracted text to speech
- Saves audio output as an MP3 file
- Lightweight and easy to use

## Requirements

- Python 3.x
- pyttsx3
- PyPDF2

## Installation

1. Clone this repository or download the `main.py` file
2. Install the required dependencies:

```bash
pip install pyttsx3 PyPDF2
```
## Usage
1. Place your PDF file (named book.pdf) in the same directory as the script

2. Run the script:
    ```bash
    python main.py
    ```
3. The script will:

    - Extract text from each page of the PDF

    - Clean the text by removing extra whitespace and newlines

    - Convert the text to speech

    - Save the audio as `story.mp3` in the same directory

## Customization
- To use a different PDF file, change `'book.pdf'` to your filename in the script

- To change the output audio filename, modify `'story.mp3'` to your preferred name

- You can adjust speech rate, volume, or voice by adding pyttsx3 engine configurations

## Notes
- The script processes all pages of the PDF by default

- Text extraction quality depends on the PDF format

- For large PDFs, the conversion might take some time

## License
This project is open-source and available for free use.

## Contact Us
- email: thetruesammyjay@gmail.com
- X(formerly Twitter): x.com/thatbwoysammyj
- Telegram: t.me/sammyjayisthename