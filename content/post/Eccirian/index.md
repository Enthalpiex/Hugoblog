---
title: "Eccirian: Better Encryption for Obsidian"
author: Entropiex
description: 
date: 2025-04-24
image: Eccirian.png
categories:
  - Plugin & Software
math: false
toc: true
tags:
  - Obsidian
  - plugin
---
**Eccirian** is a security-focused Obsidian encryption plugin that supports seamless encryption and decryption of files using multiple advanced password-based encryption methods. 

It introduces a custom `.eccirian` file extension and provides a unique read-only view for locked files, allowing you to easily manage sensitive information directly in Obsidian.


[![Stars](https://img.shields.io/github/stars/Enthalpiex/Eccirian-Encrypt?style=social)](https://github.com/Enthalpiex/Eccirian-Encrypt/stargazers)
[![Release](https://img.shields.io/github/v/release/Enthalpiex/Eccirian-Encrypt?include_prereleases&label=release)](https://github.com/Enthalpiex/Eccirian-Encrypt/releases)
[![Issues](https://img.shields.io/github/issues/Enthalpiex/Eccirian-Encrypt)](https://github.com/Enthalpiex/Eccirian-Encrypt/issues)
[![License](https://img.shields.io/github/license/Enthalpiex/Eccirian-Encrypt)](https://github.com/Enthalpiex/Eccirian-Encrypt/blob/main/LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/Enthalpiex/Eccirian-Encrypt)](https://github.com/Enthalpiex/Eccirian-Encrypt/commits/main)

---

##  Features

- 🔁 One-click encryption and decryption of `.md` files (or any other types) into `.eccirian`, and vice versa.
- 🔒 AES-256-CGM and ECC-P-256 based password encryption.
- 📄 Custom `eccirian-view` that shows a locked message instead of the default editor.
- 🧷 Files remain read-only until unlocked via user input.
- ⚙️ UI and control panel support.
- 📦 Modular architecture for maintainability and expansion.pansion.

---

##  Installation

### Method 1. (Under review) Official Community Release

To be published to the Obsidian Community Plugin Marketplace.

You can clone the current repository to try it out first, but please do not update before the official release - the encryption logic may **change**.


###  Method 2. Release File

1. **Download & extract** the release.
2. Move the files into your Obsidian vault's plugin directory:

```
<your-vault>/.obsidian/plugins/eccirian-encrypt/
```

3. Open Obsidian:
   - Go to **Settings → Community Plugins**.
   - Enable **Eccirian Encrypt** from the list.

---

##  Usage

1. Open any file.
2. Run the `Encrypt/Decrypt Note` command from the Command Palette (`Ctrl+P`) or click left icon.
3. Enter a password to encrypt or decrypt.
4. Encrypted files will be renamed to `.eccirian` and shown as locked views.
5. Click “Unlock” and enter the password to decrypt and return to edit mode.
6. Decrypted notes will automatically be renamed back to `.md` (or origional namme).

---

##  Security Notes

- Do not use it to store critical secrets. The developer is not responsible for any loss of content.
- The password you set will not be stored in any way, if you forget the password you will lose your file.

---

##  License

MPL-2.0 License © 2025 Entropiex

