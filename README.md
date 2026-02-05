# 🔐 Image Encryption Tool

A Python-based image encryption and decryption tool using pixel manipulation techniques. This project demonstrates how digital images can be securely encrypted and restored using multiple algorithms, reinforcing core cybersecurity and image processing concepts.

---

## 📌 Project Overview

This project secures images by manipulating pixel values at the RGB level. It supports multiple encryption techniques such as XOR operations, pixel swapping, mathematical transformations, and channel shuffling. The tool uses a key-based approach to ensure secure and reversible encryption.

**Created as part of:** Cybersecurity Internship Project  
**Author:** Manividyadhar  
**Date:** November 2025  

---

## ✨ Features

- Encrypt images using multiple pixel-based algorithms  
- Decrypt images using the correct key and method  
- Supports XOR, Swap, Mathematical, and Channel Shuffle encryption  
- Preserves original image when decrypted correctly  
- Works with common image formats (PNG, JPG, BMP, etc.)  
- Menu-based command-line interface  
- Input validation and error handling  
- Cross-platform support (Windows & Linux)  

---

## 🛠 Technologies Used

- Programming Language: Python 3  
- Libraries:
  - Pillow (PIL) – Image processing  
  - NumPy – Pixel-level numerical operations  
- Editor: Visual Studio Code  
- Version Control: Git and GitHub  

---

## 📥 Installation

### Prerequisites

- Python 3.7 or higher  
- pip package manager  

### Steps

Clone the repository:
Navigate into the project directory:

cd image-encryption-tool


Install dependencies:

pip install pillow numpy


Run the program:

python image_encryptor.py

🚀 Usage
Menu Options
1. Encrypt Image
2. Decrypt Image
3. Exit

🧪 Example
Encryption Example

Input:

Enter encryption key: 12345
Enter input image path: photo.jpg
Enter output image path: encrypted.png
Select encryption method: XOR


Output:

Image encrypted successfully!

Decryption Example

Input:

Enter encryption key: 12345
Enter encrypted image path: encrypted.png
Enter output image path: decrypted.jpg
Select encryption method: XOR


Output:

Image decrypted successfully!

🔐 Encryption Methods

XOR Encryption
Applies bitwise XOR operations on pixel values using a key-based pattern.

Swap Encryption
Randomly swaps pixel positions based on the encryption key.

Mathematical Encryption
Performs arithmetic operations on pixel intensity values.

Channel Shuffle Encryption
Shuffles RGB channels to distort image structure.

⚙️ How It Works
Encryption Process

Load image and convert it to RGB format

Convert image into a NumPy pixel array

Apply selected encryption algorithm using a secret key

Convert encrypted array back to image format

Save encrypted image to disk

Decryption Process

Load encrypted image

Convert to NumPy array

Apply reverse operation using the same key and method

Restore original image

Save decrypted output

🎓 Learning Outcomes

Image encryption fundamentals

Pixel-level data manipulation

Python image processing

Use of NumPy for numerical operations

Secure and reversible encryption techniques

Command-line application development

👤 Author Information

Name: Manividyadhar
Email: manividyadhar143@gmail.com

GitHub: https://github.com/manividyadhar

LinkedIn: https://www.linkedin.com/in/manividyadhar/

