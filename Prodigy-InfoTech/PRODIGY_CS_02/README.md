Task 2
Image Encryption Tool

This Python program implements a simple image encryption tool using pixel manipulation techniques. It allows users to encrypt and decrypt images by performing mathematical operations on pixel values. Designed for ease of use, the program provides clear prompts to guide users through the encryption and decryption process.

Features
Image Encryption: Modifies pixel values using a mathematical operation to create an encrypted image.

Image Decryption: Restores the original image by reversing the encryption process.

User Input: Allows users to specify the image file and encryption key.

File Handling: Saves encrypted and decrypted images to user-defined locations.

How It Works
Encrypt Image: Each pixel value is multiplied by a key and divided by the key plus one.

Decrypt Image: The encryption process is reversed by multiplying each pixel by the key plus one and dividing by the key.

Usage
Run the Program: Start the Image Encryption tool.

Select Action: Choose 'e' to encrypt, 'd' to decrypt, or 'q' to quit.

Encrypt Image:

Enter an encryption key.

Provide the image file path or URL.

Decrypt Image:

Enter the decryption key.

Provide the encrypted image file path.

View Results: The program saves and displays the file location of encrypted and decrypted images.

This program was developed as part of my internship at The Prodigy Infotech, demonstrating a basic approach to image encryption and decryption through pixel manipulation.