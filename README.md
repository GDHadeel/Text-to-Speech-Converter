# Text-to-Speech-Converter

# Task 6: Building a User Interface for Text-to-Voice Conversion

## Description
This project is a simple web application that converts text to speech in both English and Arabic. Users can input text, select the language, and listen to the text being read aloud.


## Features

- Converts text to speech in English and Arabic
- User-friendly interface


## Demo
Below are two demos of the Text-to-Speech Converter in action:

- **English**:
https://github.com/user-attachments/assets/cbadeab5-4867-4d22-8b14-0e2ac3d08358

- **Arabic**:
https://github.com/user-attachments/assets/785e1dbd-d3c9-4f33-9075-8447eb0eb3be


## Code Explanation

1. **HTML Structure**:

    - The `<textarea>` element allows users to enter text that they want to be converted to speech.

    - The `<select>` dropdown lets users choose the language for the speech output (English or Arabic).

    - The `<button>` element triggers the speech synthesis when clicked.


2. **CSS Styling**:

    - The CSS provides a visually appealing design with a gradient background, centered content, and styled buttons and text areas.

    - It ensures the application is responsive and looks good on various screen sizes.


3. **JavaScript Functionality**:

    - **Event Listener**: An event listener is attached to the "Listen" button. When clicked, it triggers the text-to-speech functionality.

    - **Text Retrieval**: The script retrieves the text entered by the user and the selected language from the dropdown.

    - **Speech Synthesis**:
        - A `SpeechSynthesisUtterance` object is created with the text to be spoken and the selected language.
        - The `speechSynthesis.speak()` method is used to convert the text into speech.

    - **Error Handling**: If no text is entered, an alert prompts the user to enter text.


## Usage

1. **Enter Text:**
    - Type or paste the text you want to convert to speech in the text area.

2. **Select Language:**
    - Choose either English or Arabic from the dropdown menu.

3. **Convert to Speech:**
    - Click the "Listen" button to hear the text read aloud in the selected language.


## Acknowledgements
https://www.geeksforgeeks.org/build-a-text-to-speech-converter-using-html-css-javascript/

https://www.youtube.com/watch?v=kAWNSolkkqg

