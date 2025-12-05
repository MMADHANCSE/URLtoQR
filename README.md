# 📦 QR Code Generator (Node.js CLI)

This is a simple **QR Code Generator** built using **Node.js**, which allows users to input a URL and automatically generates:
- A **QR code image** named `qr_img.png`
- A text file `URL.txt` that stores the entered URL

This project uses:
- `inquirer` for command line input
- `qr-image` for QR code generation
- `fs` for file handling

---

## 🚀 Features
- 🚀 Simple and fast command-line interface
- ✍️ Enter any URL to convert into a QR code
- 🖼️ Generates QR in PNG format
- 📄 Automatically stores URL into `URL.txt`
- 🔧 Easy to modify and extend
- 🌎 Cross-platform support

---

## 📸 **Demo**
### ▶ Running the App

---

---

## 🧠 **How It Works**
1. User inputs a URL in the terminal
2. `inquirer` collects the input
3. `qr-image` converts URL into QR code PNG
4. `fs` writes URL into text file
5. Terminal confirms process

---

## 📦 **Installation Instructions**

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/qr-code-generator.git
cd qr-code-generator
<img width="1135" height="371" alt="image" src="https://github.com/user-attachments/assets/a916210f-0660-4926-b5f0-6d67fa6a4863" />

🧩 Future Improvements

Add support for different QR formats (svg, jpg, pdf)

Add color customization options

Build a web UI version using Express or React

Enable multiple link processing batch mode

📝 License
This project is licensed under the MIT License.
