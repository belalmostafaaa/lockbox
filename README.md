# LockBox Password Manager

### A secure command-line password manager with military-grade encryption and intuitive features.

## Features

| Feature | Description |
|---------|-------------|
| **Secure Storage** | AES-256 encrypted vault |
| **Password Generation** | Create 16-character strong passwords |
| **Instant Search** | Fuzzy-find passwords in milliseconds |
| **Cross-Platform** | Windows/macOS/Linux support |
| **Zero Trust** | No internet connection needed for core operations |
| **Breach Check** | Verify passwords against HIBP database |

## New Security Feature: Password Breach Check

LockBox now integrates with Have I Been Pwned's (HIBP) API to check if your passwords have been exposed in known data breaches. This feature:

- Checks passwords against 613+ million breached credentials
- Uses secure k-Anonymity model (only sends first 5 chars of SHA-1 hash)
- Provides instant feedback before password storage
- Helps prevent using compromised credentials

## Installation

### Linux
bash
# 1. Install system dependencies
```
sudo apt-get update
sudo apt-get install -y python3 python3-pip python3-tk python3-dev git
```
```
# 2. Clone the repository
git clone https://github.com/belalmostafaaa/lockbox.git
cd lockbox
```
```
# 3. Install Python packages directly
sudo pip3 install cryptography pyperclip requests
```
```
# 4. Make the script executable
chmod +x lockbox.py
```
```
# 5. Run (with sudo for proper permissions)
sudo ./lockbox.py
```
