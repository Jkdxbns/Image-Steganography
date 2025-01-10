# Image Steganography Library

A simple Python library for encoding and decoding hidden messages in images using steganography.

## Features
- Embed text messages in PNG images.
- Extract hidden messages from steganographed images.

## Usage
1. Download the library using any methods listed below
2. Open terminal on your device and run the below script
   `from imgsteg import Encrypt`
3. This will prompt you to enter a password
4. Enter the text once it is done it will output a unique number which is the public key to be used while decrypting the text.
5. Select the image to be encrypted and then save the encrypted image using `.png` extention
6. Executing `from imgsteg import Decrypt` on terminal will result in prompting you to select the encrypted image
7. Enter the password entered during encryption and the public key displayed during encryption
8. The output will be displayed in the terminal itself 


## Installation
GitHub: git clone https://github.com/Jkdxbns/Image-Steganography.git
PyPI: pip install ImageSteganography
