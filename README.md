# 🔐 Password Manager

## Overview
A **Password Manager** application built with Python and Tkinter that helps generate, store, and retrieve passwords securely. It supports **automatic password generation**, **searching saved passwords**, and **copying passwords to the clipboard**.

## Features
- **Securely store credentials** (Website, Email, Password)
- **Generate strong random passwords**
- **Copy passwords to clipboard automatically**
- **Search for stored credentials**
- **Save and retrieve data using a JSON file**

## Requirements
- Python 3.x
- `tkinter` (built-in with Python)
- `pyperclip` (for copying passwords to clipboard)
- `json` (for data storage)

## Installation
1. Clone or download this repository.
2. Ensure `logo.png` is present in the same directory as the script.
3. Install dependencies:
   ```bash
   pip install pyperclip
4. Run the script:
   ```bash
   python password_manager.py
   ```

## Usage
### Adding a New Credential
1. Enter the **Website**, **Email**, and **Password**.
2. Click **"Generate Password"** for a strong password.
3. Click **"Add"** to save credentials in `data.json`.

### Searching for a Credential
1. Enter the **Website** and click **"Search"**.
2. If found, the **Email** and **Password** will be displayed.

### Generating a Password
1. Click **"Generate Password"** for a **random strong password**.
2. The password is copied to the clipboard automatically.

## File Structure
```
|-- password_manager.py  # Main script
|-- data.json            # Stores credentials (auto-created)
|-- logo.png             # UI logo
```

## Future Enhancements
- **Encrypt stored passwords for added security**
- **Add a master password to access saved credentials**
- **Export/import saved passwords**

Keep your credentials secure with **Password Manager!** 🔐
