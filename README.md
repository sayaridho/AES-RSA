
-> pip install -r requirements.txt
-> run GUIxCODE.py

# 🔒 CryptoVault - Hybrid File Encryption Toolkit

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white" alt="Python Version">
  <img src="https://img.shields.io/badge/GUI-CustomTkinter-483D8B?logo=tkinter" alt="GUI Framework">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
</div>

---

## 🌟 **Fitur Unggulan**
### Hybrid Encryption System
🔄 **AES-RSA Synergy**  
Menggabungkan kecepatan AES (128/192/256-bit) dengan keamanan RSA (1024/2048/4096-bit) dalam sistem enkripsi berlapis:

```mermaid
graph LR
    A[File Original] --> B{AES-256 Enkripsi} 
    B --> C[Kunci AES Terenkripsi]
    C --> D{RSA Enkripsi}
    D --> E[File Aman]
=
