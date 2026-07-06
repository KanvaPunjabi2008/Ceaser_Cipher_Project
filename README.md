# Caesar Cipher 🔐

A simple Python implementation of the classic **Caesar Cipher** encryption and decryption technique. This project allows users to encode and decode messages by shifting letters through the alphabet.

## Features

* Encrypt messages using the Caesar Cipher algorithm
* Decrypt encrypted messages
* Supports any shift value (automatically wraps around the alphabet)
* Preserves spaces, numbers, and special characters
* Interactive command-line interface
* Allows multiple encryption/decryption operations in a single session
* ASCII art logo for an enhanced user experience

## How It Works

The Caesar Cipher is one of the oldest and simplest encryption methods. Each letter in the plaintext is shifted a certain number of positions down the alphabet.

### Example

**Original Message**

```text
hello world
```

**Shift Value**

```text
3
```

**Encrypted Message**

```text
khoor zruog
```

## Project Structure

```text
caesar-cipher/
│
├── main.py          # Main application file
├── art.py           # ASCII art logo
└── README.md        # Project documentation
```

## Requirements

* Python 3.x

No external libraries are required.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/caesar-cipher.git
```

2. Navigate to the project directory:

```bash
cd caesar-cipher
```

3. Run the program:

```bash
python main.py
```

## Usage

When the program starts, select one of the following options:

```text
Type 'encode' to encrypt, type 'decode' to decrypt:
```

Then enter:

* Your message
* The shift number

Example:

```text
Type 'encode' to encrypt, type 'decode' to decrypt:
encode

Type your message:
hello

Type the shift number:
5

Here is the encoded result: mjqqt
```

## Code Highlights

* Uses modular arithmetic (`%`) to wrap shifts beyond the alphabet length.
* Handles both encoding and decoding using a single function.
* Maintains non-alphabetic characters unchanged.

## Learning Objectives

This project demonstrates:

* Functions in Python
* Loops and conditionals
* Lists and indexing
* String manipulation
* Modular arithmetic
* User input handling

## Future Improvements

* Support uppercase letters
* Custom alphabets
* GUI version using Tkinter
* File encryption/decryption support

## Author

Created as a Python learning project to understand basic cryptography concepts and programming fundamentals.

## License

This project is open source and available under the MIT License.
