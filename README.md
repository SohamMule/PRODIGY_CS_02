# PRODIGY_CS_02
Image Encryption/Decryption Tool
This is a simple Python script that performs encryption and decryption on images using a bitwise XOR operation on pixel values. It's easy to use, lightweight, and works with any standard image file.

How It Works
The script loads the input image and converts it to RGB mode.
Each pixel's Red, Green, and Blue values are XORed with a user-provided numeric key (between 0 and 255).
The modified image is saved to a new file.
Running the same process again with the same key will decrypt the image back to its original form.

How to Run
Make sure your input image is in the same folder as the script, or provide the full path to the image when prompted.
The output image will be saved in the same folder as the script.

Example
Encrypting an image:
Enter path to input image: image.jpg
Enter output image path (e.g., encrypted.png): encrypted.png
Enter numeric key (0–255): 123
Saved result: encrypted.png

Decrypting the image:
Enter path to input image: encrypted.png
Enter output image path (e.g., decrypted.png): decrypted.jpg
Enter numeric key (0–255): 123
Saved result: decrypted.jpg

