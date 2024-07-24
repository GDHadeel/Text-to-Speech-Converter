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

### HTML Structure

- **`<html>` and `<head>`**:
  - Standard HTML elements to define the document and include meta tags for character encoding and responsive design.

- **`<title>`**:
  - Sets the webpage title to "Text to Speech Converter".

- **`<style>`**:
  - Contains CSS styles that define the look and feel of the application, including background gradients, container styling, and button appearance.

- **`<body>`**:
  - Contains the main application content inside a container `<div>`.

- **Inside the Container**:
  - **`<h1>`**: Displays the application title.
  - **`<textarea>`**: Allows users to input text for conversion.
  - **`<select>`**: Dropdown menu for selecting the language of the speech output.
  - **`<button>`**: Button to trigger the speech synthesis.

### CSS Styling

- **`body`**:
  - Centers the content vertically and horizontally with a gradient background.

- **`.container`**:
  - Styles the main application container with padding, rounded corners, and a maximum width.

- **`h1`**:
  - Styles the heading with specific font size and color.

- **`#speak-btn`**:
  - Styles the button with padding, font size, and a hover effect.

- **`textarea`**:
  - Styles the text area with padding, border, and dimensions.

- **`select`**:
  - Styles the dropdown menu with padding, border, and width.

### JavaScript Functionality

- **Event Listener**:
  - Attaches a click event to the "Listen" button.

- **Text and Language Retrieval**:
  - Retrieves the text from the `<textarea>` and the selected language from the dropdown.

- **Speech Synthesis**:
  - Uses the Web Speech API to convert the text to speech in the selected language.

- **Error Handling**:
  - Alerts the user if no text is entered when clicking the button.


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

