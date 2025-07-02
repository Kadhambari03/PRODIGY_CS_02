This Python program performs basic image encryption and decryption using pixel manipulation in Google Colab.

The encryption logic simply reverses the RGB pixel values using `255 - pixel`, making the image unreadable. Decryption uses the same operation to restore the original image.

Features:
- Upload and view any image
- Encrypt the image by reversing pixel values
- Decrypt to restore original image
- Download encrypted/decrypted images
- Uses OpenCV in Google Colab

How to Run:
- Open the code in Google Colab
- Run all cells in order
- Upload an image (e.g., input.jpg)
- Use `encrypt_image()` and `decrypt_image()` functions
- Download results using `files.download()`

Requirements:
- Python (Google Colab)
- opencv-python library

