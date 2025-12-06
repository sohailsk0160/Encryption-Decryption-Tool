🔐 Encryption & Decryption Web Tool

This is a simple and interactive web-based cryptography tool built using HTML, CSS, and JavaScript.
It allows users to encrypt and decrypt text using multiple classical cipher algorithms.

🚀 Features

✔ User-friendly interface
✔ Supports multiple encryption/decryption algorithms
✔ Real-time processing
✔ No backend required — fully client-side
✔ Clean and responsive UI

🔑 Supported Algorithms
1. Caesar Cipher

Simple shift-based substitution

Works on both uppercase and lowercase letters

2. Multiplicative Cipher

Encrypts text using multiplication modulo 26

Includes automatic modular inverse calculation for decryption

3. Playfair Cipher

Creates a 5×5 key matrix

Handles repeated letters & padding

Implements row, column, and rectangle rules

4. Hill Cipher

Uses matrix multiplication for encryption

Supports 2×2 key matrix

Automatically computes inverse matrix for decryption

5. Rail Fence Cipher

Uses zig-zag pattern to rearrange characters

Supports both encryption and decryption

6. Vigenère Cipher

Keyword-based polyalphabetic cipher

Works on uppercase & lowercase letters

📁 Project Structure
/project-folder
│── index.html
│── README.md
└── (No external dependencies required)

🛠️ Technologies Used

HTML5 – Structure

CSS3 – Styling & UI

JavaScript (ES6) – All encryption/decryption logic

📝 How It Works

Select your algorithm

Choose mode → Encrypt or Decrypt

Enter the required key or shift

Type your input text

Click Run to get the output

Everything runs inside the browser — no data is stored or uploaded.

🎯 Use Cases

Students learning classical cryptography

Testing encryption algorithms

Educational demonstrations

Personal experiments with ciphers
