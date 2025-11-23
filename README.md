# Introduction
This project focuses on securing digital images by manipulating their pixel values and positions. Instead of using traditional heavy encryption algorithms, the method works directly on the image matrix, altering pixel arrangements and intensities to produce a distorted, unreadable result. Only the correct key can reverse these steps, making the technique fast, lightweight, and effective for protecting sensitive images.
# Objectives
To apply pixel-level transformations for image encryption.
To convert the original image into an unreadable format using simple operations.
To ensure a fully reversible process using a secret key.
To demonstrate a fast and efficient technique for image security.
# Problem Statement
Images shared or stored online can be easily viewed or misused. There is a need for a quick and simple method that encrypts the image at pixel level, making it visually inaccessible without the correct key.
# Scope of the Project
Supports RGB and grayscale images.
Suitable for learning, research, and basic security applications.
Can be extended into more advanced encryption methods.
# Methodology
1 Pixel Extraction
The image is converted into a pixel matrix for easy manipulation.
2 Pixel Shuffling
Rows, columns, or blocks are rearranged based on a secret key to hide the original structure.
3 Pixel Value Modification
Pixel values are altered using simple operations like XOR, addition, subtraction, or channel reversal.
4 Channel Swapping
RGB channels are interchanged for added confusion and randomness.
5 Encrypted Image Generation
The modified pixel matrix is converted back into an encrypted image.
6 Decryption
Reverse operations restore the original image using the same key.

<img width="798" height="504" alt="Screenshot 2025-11-23 083748" src="https://github.com/user-attachments/assets/2bdd5056-4e81-420a-ad93-a3e4fad7ca01" />

<img width="799" height="489" alt="Screenshot 2025-11-23 083824" src="https://github.com/user-attachments/assets/5e8d9c35-3efe-4076-bf7b-6e42c19032cb" />

<img width="788" height="453" alt="11" src="https://github.com/user-attachments/assets/9b9029db-c533-4986-bd46-80c1fd67cdbd" />

# Technologies Used
Language: Python
Libraries: OpenCV/Pillow, NumPy
Tools: VS Code / PyCharm
Version Control: GitHub
# Applications
Secure transmission of sensitive images
Protection of medical and forensic visuals
Privacy in surveillance footage
Safe cloud storage of photographs
# Advantages
Fast and lightweight
Key-based reversible encryption
Easy to implement
Works with most image formats
# Limitations
Not as strong as advanced cryptographic systems
Security depends on key complexity
Basic pixel operations may be vulnerable to high-level attacks
# Conclusion
The project successfully shows how pixel manipulation can be used to encrypt images in a simple and efficient way. By shuffling pixels, modifying their values, and swapping channels, the original image becomes fully distorted and secure. The method offers a practical and lightweight solution for basic image protection and can be expanded into more advanced encryption systems
