# Python Text & Number Encryption Script

A lightweight Python utility for encrypting and decrypting text and numeric characters using a Caesar cipher approach with a customizable key.

---

## Table of Contents

* [Features](#features)
* [Requirements](#requirements)
* [Installation](#installation)
* [Usage](#usage)
* [Script Structure](#script-structure)
* [Examples](#examples)
* [Contributing](#contributing)
* [License](#license)

---

## Features

* Encrypts alphabetic characters (both uppercase and lowercase) by shifting them by a key (0–25).
* Leaves non-alphabetic characters (e.g., numbers, punctuation) unchanged.
* Provides both encryption and decryption functions.
* Simple command-line interface for quick use.

---

## Requirements

* Python 3.6 or higher

---

## Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

---

## Usage

Run the script directly:

```bash
python encrypt_v-4.py
```

You will be prompted to enter:

1. **Message:** The text to encrypt/decrypt.
2. **Key:** An integer between 0 and 25.

The script will display both the encrypted and decrypted messages.

---

## Script Structure

```
├── LICENSE
├── README.md
├── encrypt_v-4.py    # Main encryption/decryption script
└── .gitignore        # Ignore Python cache files, etc.
```

---

## Examples

```bash
Enter the message: Hello, World! 123
Enter the key (0-25): 3
Encrypted message: Khoor, Zruog! 123
Decrypted message: Hello, World! 123
```

---

## Contributing

1. Fork the repository.
2. Create a branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m "Add feature"`).
4. Push to branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

---

## License

Distributed under the MIT License. See `LICENSE` for details.
