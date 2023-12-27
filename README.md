##Morse Code Generator

A Python console-based Morse Code Generator that facilitates the conversion of text to Morse code and vice versa.

## Overview

The Morse Code Generator is a versatile tool that serves as a Morse code encoder and decoder. It provides an easy-to-use console interface, making Morse code conversion accessible to users with varying levels of technical expertise.

## Features

### 1. Text to Morse Conversion

- Accepts input text and converts it to Morse code.
- Supports letters A-Z, numbers 0-9, and common punctuation.
- Spaces between words are represented by '/'.

### 2. Morse to Text Conversion

- Accepts Morse code input and decodes it into plain text.
- Handles Morse code with letters A-Z, numbers 0-9, and common punctuation.
- Spaces between words are expected to be represented by '/'.

### 3. User-friendly Console Interface

- Provides clear prompts and instructions for seamless user interaction.
- Allows users to enter text or Morse code directly through the console.

## Usage

1. **Run the Morse Code Generator:**
   - Execute the Python script `morse-code-generator.py` in your terminal.

2. **Choose Conversion Mode:**
   - Select either "Text to Morse" or "Morse to Text" as prompted.

3. **Enter Input:**
   - For "Text to Morse," input the text you want to convert.
   - For "Morse to Text," input the Morse code you want to decode.

4. **View Result:**
   - The program will display the generated Morse code or decoded text.

5. **Repeat or Exit:**
   - Optionally, you can repeat the process or type any key to exit the program.

## Morse Code Reference

The Morse Code Generator uses the standard Morse code representations:

```python
morse_dict = {
    'A': '.-', 'B': '-...', 'C': '-.-.', 'D': '-..', 'E': '.', 'F': '..-.',
    'G': '--.', 'H': '....', 'I': '..', 'J': '.---', 'K': '-.-', 'L': '.-..',
    'M': '--', 'N': '-.', 'O': '---', 'P': '.--.', 'Q': '--.-', 'R': '.-.',
    'S': '...', 'T': '-', 'U': '..-', 'V': '...-', 'W': '.--', 'X': '-..-',
    'Y': '-.--', 'Z': '--..',
    '1': '.----', '2': '..---', '3': '...--', '4': '....-', '5': '.....',
    '6': '-....', '7': '--...', '8': '---..', '9': '----.', '0': '-----',
    ' ': '/'
}
