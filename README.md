Secure Data Hiding in Images Using Steganography

Overview

This project demonstrates how steganography can be used to securely hide messages within images. The hidden data is protected with a password, ensuring that only authorized users can retrieve it.

Features

Encrypt and hide secret messages in an AI-generated image.
Password protection for an added layer of security.
Minimal image distortion to avoid detection.
Cross-platform compatibility (Windows, Linux, macOS).
Simple, user-friendly implementation.

Technology Stack

Programming Language: Python
Libraries Used:
OpenCV – Image processing
NumPy – Pixel manipulation
os – File handling
Cryptography (future scope) – Additional encryption layer

Installation & Setup

Link : https://github.com/Dhrubapanda/SECURE-DATA-HIDING-IN-IMAGES-USING-STEGANOGRAPHY

Install the required dependencies: pip install opencv-python numpy
Run the program: python steganography.py

Usage

Enter the secret message you want to hide.
Provide a password for encryption.
The image will be generated with the hidden message.
To decrypt, enter the correct password.
If the password is incorrect, access will be denied.

Output

Encryption: The program hides the message inside an AI-generated image.
Decryption: The message is retrieved only if the correct password is provided.


Future Scope

Implement AES encryption for stronger security.
Develop a GUI-based interface for ease of use.
Support for various file types (text, PDFs, audio files).
AI-optimized steganography for better data concealment.
