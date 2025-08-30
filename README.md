# Morse Code Translator (Python)

A simple Python project to translate between **English text** and **Morse code**.  
Supports both **encoding** (text → Morse) and **decoding** (Morse → text).

---

## 🚀 Features
- Convert English text into Morse code.
- Convert Morse code back into English text.
- CLI-based interactive program.
- Handles letters, digits, and common punctuation marks.

---


---

## ⚙️ Implementation Details
- **Encoding**: Direct dictionary lookup for each character.
- **Decoding**: Reverse lookup by scanning dictionary values.
- **Error Handling**:
  - Prints error if input character is not supported.
  - Prints error if Morse code symbol is invalid.
- **I/O**: 
  - Input taken using `input()`.
  - Output displayed using `print()`.
- **Performance**:
  - Encoding: O(1) lookup per character.
  - Decoding: O(n) per Morse symbol (can be optimized with reverse dict).

---

## 🖥️ Usage
1. Run the program:
   ```bash
   python main_morse_code.py

2. Choose an option:
encode → Convert text to Morse.
decode → Convert Morse to text.
stop → Exit program.

3. Example:
enter whether you want to encode or decode the message otherwise enter stop: encode
enter the sentence:
HELLO
.... . .-.. .-.. ---
   
✅ Supported Characters
Letters: A–Z
Numbers: 0–9
Symbols: . , ? ' ! / ( ) & : ; = + - _ " $ @ *
Space represented as /
