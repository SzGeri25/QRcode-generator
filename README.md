# 📦 QR Code Generator

A simple command-line tool that converts any URL into a QR code image using Node.js.

## 🚀 Features

- ✅ CLI prompt for URL input
- ✅ Generates QR code as `png` image (`qr_img.png`)
- ✅ Saves the original URL to a `URL.txt` file
- ✅ Uses `inquirer`, `qr-image`, and Node's native `fs` module

## 🛠️ Technologies

- Node.js
- [inquirer](https://www.npmjs.com/package/inquirer)
- [qr-image](https://www.npmjs.com/package/qr-image)
- `fs` module (built-in)

## 📄 How It Works

1. Prompts the user to enter a URL via CLI.
2. Generates a `.png` QR code of the entered URL.
3. Saves the QR code as `qr_img.png` and logs the URL to `URL.txt`.

## ▶️ Getting Started

1. Clone the repo:
    ```bash
   git clone https://github.com/SzGeri25/QRcode-generator.git
   cd QRcode-generator
   
2. Install dependencies:
    ```bash
    npm install

3. Run the app:
    ```bash
    node index.js

## ✨ Ideas for Future Improvements

These features are not implemented yet, but could be added later to enhance the project:

### 🖥️ Web Interface

- Build a user-friendly frontend to enter URLs and see the QR code immediately.

- Use React or Vanilla JS to create a real-time generator.

### 🎨 Customization Options

- Choose QR code color, background color, and size.

- Add support for inserting logos or branding inside the QR.

### 🔄 More Data Types

- Generate QR codes for:

  - Text

  - Wi-Fi credentials

  - vCards (contact info)

  - Emails or phone numbers

### 📷 QR Reader

- Add functionality to scan/upload a QR image and decode its content.

- Could be done via browser using libraries like html5-qrcode.

### 💾 History / Log

- Save previously generated QR codes with timestamps.

- Show a log of generated URLs and images.

### 📦 Advanced CLI

- Add more CLI options:

  - Custom filename

  - Custom output folder

  - ASCII preview in terminal
