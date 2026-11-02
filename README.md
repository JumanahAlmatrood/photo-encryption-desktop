# Photo Encryption (Desktop App)

A Python desktop app for encrypting and decrypting photos, with user login. It was built with [Shatha](https://github.com/sha7cs) using Tkinter.

## Features

- Register and log in with a username and password
- Store passwords as SHA-256 hashes in `users.json`
- Encrypt JPG, JPEG, and PNG photos with Fernet
- Decrypt a photo by file name and show it in the app

## Setup

The app needs Tkinter, which is included with most Python installers.

```bash
git clone https://github.com/JumanahAlmatrood/photos-encryption.git
cd photos-encryption
pip install -r requirements.txt
python main.py
```

## Limitations

This is a learning project and should not be used for real private photos.

- The encryption key is created when the main window opens and is not saved. Photos can only be decrypted in the same session.
- Passwords use plain SHA-256 without a salt.

## Tools

Python, Tkinter, cryptography, Pillow

## Related project

[photo-encryption](https://github.com/JumanahAlmatrood/photo-encryption) is a Flask web version of this idea.
