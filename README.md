# PRODIGY_CS_02

## Task-02: Image Encryption Tool

### Description
This tool implements image encryption and decryption using pixel manipulation techniques. It provides a graphical user interface for users to encrypt images using various methods like XOR encryption, RGB channel swapping, pixel value shifting, and bit manipulation.

### Features
- Multiple encryption methods:
  - XOR encryption with a user-defined key
  - RGB channel swapping
  - Pixel value shifting
  - Bit manipulation
- User-friendly GUI with image preview
- Real-time encryption/decryption
- Debug mode with detailed information
- Format warnings to prevent data loss

### Installation
```bash
'pip install pillow numpy'
```

### Usage
Run the application: `python image_encryption_tool2.py`
- Select an image using the "Select Image" button
- Enter an encryption key or generate one randomly
- Choose an encryption method
- Click "Encrypt Image" or "Decrypt Image"
- Save the result with "Save Result"
- 
### Important Notes
- Always save encrypted images in PNG format to preserve all pixel data
- Remember your encryption key and method - they're required for decryption
- The debug panel shows valuable information about the encryption/decryption process




