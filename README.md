# AICTE-Project-1
Secure Data Hiding In Images Using Steganography
This project demonstrates a simple implementation of image steganography using Python and OpenCV. The application allows users to hide (encrypt) a secret message inside an image and later retrieve (decrypt) the message using a simple UI built with Tkinter.
# Features
Data Hiding (Encryption):
Embed a secret text message into a cover image. The program writes each character's ASCII value into the image pixels and saves the modified image as a lossless PNG file to preserve data integrity.

Decryption:
Retrieve the hidden message from the modified image by providing the correct passcode and the message length.

# Requirements
Python 3.x

OpenCV
## Installation
Install via pip:

```sh
pip install opencv-python

