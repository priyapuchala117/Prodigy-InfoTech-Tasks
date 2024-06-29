# 1. Caesar Cipher

This repository contains a Python program that performs encryption and decryption using the Caesar Cipher algorithm. The Caesar Cipher is a type of substitution cipher in which each letter in the plaintext is shifted a certain number of places down or up the alphabet.

## Features

- Encrypts a message using the Caesar Cipher algorithm.
- Decrypts a message encrypted with the Caesar Cipher algorithm.
- Allows the user to input a custom shift value.

## How to Use

1. **Clone the Repository**

   ```sh
   git clone https://github.com/priyapuchala117/caesar-cipher.git
   cd caesar-cipher

2. **Run the Python script using the following command:**
   ```sh
   python caesar_cipher.py



# 2. Pixel Manipulation for Image Encryption

## Image Encryption Tool

This is a simple image encryption tool that encrypts and decrypts images using basic pixel manipulation techniques. The tool swaps pixel values and applies basic mathematical operations to each pixel to obscure the original image. This is not intended for high-security encryption but rather for educational purposes and simple use cases.

## Features

- **Encrypt Image**: Encrypt an image by manipulating its pixels.
- **Decrypt Image**: Decrypt an encrypted image back to its original form.

## Requirements

- Python 3.x
- PIL (Pillow)

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/priyapuchala117/image-encryption-tool.git
    cd image-encryption-tool
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Encrypt an Image**:
    ```bash
    python encrypt.py --input input_image.png --output encrypted_image.png
    ```

2. **Decrypt an Image**:
    ```bash
    python decrypt.py --input encrypted_image.png --output decrypted_image.png
    ```

## Example

To encrypt an image:

```bash
python encrypt.py --input example.png --output example_encrypted.png
```

# 3. Password Strength Checker

## Introduction

The Password Strength Checker is a tool that assesses the strength of a password based on several criteria, including length, presence of uppercase and lowercase letters, numbers, and special characters. It provides feedback to users on the password's strength and offers additional features like password generation, copying, and clearing.

## Features

- **Password Strength Assessment**: Evaluates password strength based on various criteria and provides feedback.
- **Password Generation**: Generates a strong random password.
- **Password Copying**: Allows users to copy the password to the clipboard.
- **Progress Bar**: Visual representation of password strength.
- **Responsive GUI**: User-friendly interface built with Tkinter.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/priyapuchala117/password-strength-checker.git
    cd password-strength-checker
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the application:
    ```bash
    python app.py
    ```

2. Enter a password in the input field.
3. Click the "Check" button to assess the strength of the password.
4. Use the "Generate Password" button to create a strong random password.
5. Click the "Copy Password" button to copy the password to the clipboard.
6. Use the "Clear" button to clear the input field and output.

# 4. Keylogger Program

## Introduction

This keylogger program records and logs keystrokes on a system. It captures keys pressed and saves them to a file. **Note: This program should only be used for ethical and educational purposes, with explicit permission from all parties involved. Unauthorized use is illegal and unethical.**

## Features

- Logs all keystrokes.
- Saves logged keys to a file.

## Installation

### Prerequisites

- Python 3.x
- `pynput` library

### Installing the Tool

1. Clone the repository:
    ```bash
    git clone https://github.com/priyapuchala117/keylogger-tool.git
    cd keylogger-tool
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### Installing `pynput`

If `pynput` is not included in the `requirements.txt` file, install it manually:
```bash
pip install pynput
```

# 5. Packet Sniffer Tool

## Introduction

The Packet Sniffer Tool is designed for educational purposes to capture and analyze network packets. It displays relevant information such as source and destination IP addresses, protocols, and payload data. This tool is intended for ethical use only.

## Features

- **Packet Capture**: Captures network packets in real-time.
- **Packet Analysis**: Analyzes captured packets and extracts information such as source and destination IP addresses, protocols, and payload data.
- **User-Friendly Interface**: Provides a simple command-line interface for users to view captured packet data.

## Installation

### Prerequisites

- Python 3.x
- `scapy` library

### Installing the Tool

1. Clone the repository:
    ```bash
    git clone https://github.com/priyapuchala117/packet-sniffer-tool.git
    cd packet-sniffer-tool
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### Installing `scapy`

If `scapy` is not included in the `requirements.txt` file, install it manually:
```bash
pip install scapy
```



This README file provides an overview of the project, how to use it, an example, licensing information, and contributing guidelines. Make sure to replace placeholders like `priyapuchala117` and `priya` with your actual GitHub username and name.

