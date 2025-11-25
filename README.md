# 🛡️ StegaShield – Hybrid Encryption + Image Steganography Tool

StegaShield is a Python-based information security tool that combines modern cryptographic
algorithms with LSB (Least Significant Bit) image steganography to provide multi-layered
secure communication. It encrypts sensitive data (text/files) and embeds the encrypted
payload inside images without noticeable visual changes.

---

## 🚀 Features

### 🔐 Cryptography
- AES-GCM authenticated symmetric encryption  
- RSA key pair generation (1024/2048/4096-bit)  
- RSA encryption using PKCS#1 OAEP padding  
- Encrypt/decrypt text or files  

### 🖼️ Steganography (LSB)
- Hide encrypted data inside PNG/BMP images  
- Extract and recover embedded data  
- Very small pixel-level changes (imperceptible)  
- Supports encrypted + compressed payloads  

### 🖥️ Graphical User Interface
- Built using PySimpleGUI  
- Select encryption method (AES/RSA)  
- Choose cover image for embedding  
- Extract & decrypt data with a single click  
- Clean and beginner-friendly workflow  
