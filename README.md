# XOR Steganography

A simple Python tool to hide and reveal secret messages in PNG images using XOR encryption.

📁 Project Structure:

- ├── hidden_message.png        # Output image with hidden message
- ├── input-image.png           # Original image used for encoding
- ├── steganography.py          # Script for encoding/decoding
- └── README.md                 # Project documentation

# How to Use

$ python steganography.py

1. Encrypt
   
2. Decrypt

Choose operation (1/2): 1

Enter input PNG image path: input-image.png

Enter secret message to hide: Hello World

Enter encryption key: mykey123

Enter output image filename (with .png): hidden_message.png

Success – Encrypted image saved as 'hidden_message.png'

$ python steganography.py

1. Encrypt

2. Decrypt
   
Choose operation (1/2): 2

Enter PNG image path to decode: hidden_message.png

Enter decryption key: mykey123

Success – Decrypted message: Hello World

# Notes:
### - Only .png images are supported.
### - The same key used for encryption must be used for decryption.
### - Keep your encryption key safe – it's required to extract the original message.

# Output

![output-eg](https://github.com/user-attachments/assets/58f8ee88-4899-4ba6-9b08-20115085a236)

