# Caesar-Playfair-Cipher-Implementation
This project is a Python-based GUI cryptography tool that implements Caesar and Playfair ciphers. It allows users to encrypt and decrypt messages through an interactive, user-friendly interface while demonstrating core classical cryptography concepts in a practical and educational way.
# Caesar & Playfair Cipher GUI Tool

## 📌 Project Overview
This project is a Python-based graphical cryptography application that demonstrates **classical encryption and decryption techniques** using **Caesar Cipher** and **Playfair Cipher**. The tool is designed for beginners to intermediate learners to understand how classical ciphers work through a **clean, interactive, and user-friendly GUI**. Users can easily encrypt and decrypt messages while visually interacting with the cryptographic process.

The application focuses on **functionality, usability, and educational value**, making it suitable for academic projects, cybersecurity basics, and cryptography learning.

---

## 🎯 Features
- Fully functional **Caesar Cipher** encryption and decryption
- Fully functional **Playfair Cipher** encryption and decryption
- GUI-based application (no command-line usage required)
- Dynamic interface that updates based on cipher selection
- Input validation with friendly error messages
- Copy-to-clipboard functionality for encrypted/decrypted output
- Responsive and beginner-friendly UI/UX
- Clean separation of cryptography logic and GUI code

---

## 🛠️ Technologies Used
- **Python 3.x**
- **Tkinter / CustomTkinter** (for GUI)
- Standard Python libraries only (no external dependencies required)

---


---

## ⚙️ How the Application Works

### Caesar Cipher
- User enters a message (plaintext or ciphertext)
- User provides a numeric shift key
- On clicking **Encrypt**, the message is shifted forward
- On clicking **Decrypt**, the message is shifted backward
- Output is displayed instantly in the result area

### Playfair Cipher
- User enters a secret key
- The system generates a 5×5 Playfair matrix internally
- Message is processed into digraphs following Playfair rules
- Encryption and decryption follow:
  - Same row rule
  - Same column rule
  - Rectangle rule
- Output is displayed with correct formatting

---

## ▶️ How to Run the Project

### Step 1: Install Python
Ensure Python 3.x is installed on your system.

Check version:
```bash
python --version

Step 2: Clone or Download the Project
git clone https://github.com/yourusername/caesar-playfair-cipher.git
OR download the ZIP and extract it.

Step 3: Navigate to Project Directory
cd caesar-playfair-cipher

Step 4: Run the Application
python main.py

The GUI window will open automatically.

🖥️ GUI Usage Instructions

Launch the application

Select Caesar Cipher or Playfair Cipher

Enter the required inputs (message, key/shift)

Click Encrypt or Decrypt

View and copy the result from the output box

🚫 Input Validation & Error Handling

Empty inputs are not allowed

Shift key accepts only numeric values

Playfair key automatically removes duplicates

Friendly error messages guide the user

📚 Educational Value

This project helps users:

Understand classical cryptography concepts

Learn encryption vs decryption logic

Practice Python GUI development

Apply algorithmic thinking in real-world scenarios

🔮 Future Enhancements

Add more classical ciphers (Vigenère, Rail Fence)

Dark mode UI

Export encrypted text to file

Visual Playfair matrix display

👨‍💻 Author

Developed as an educational cryptography project using Python.

📜 License

This project is open-source and free to use for educational purposes.
