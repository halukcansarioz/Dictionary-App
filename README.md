# 📖 Dictionary-App
### (A Simple English-Turkish / Turkish-English Console Dictionary Application Written in C)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)](#)
[![Console App](https://img.shields.io/badge/Console%20App-4D4D4D?style=flat&logo=windowsterminal&logoColor=white)](#)
[![Made with Learning](https://img.shields.io/badge/Made%20with-Learning-1f425f.svg)](#)

This project is a simple bilingual dictionary application written in C. It reads word lists from external files and provides both English-to-Turkish and Turkish-to-English translation via the console.

## 📚 Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation & Usage](#installation--usage)
- [Project Structure](#project-structure)
- [Development Process](#development-process)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

---

## About the Project
This application reads word lists stored in `ingilizce.txt` and `turkce.txt` and allows the user to translate words in both directions. Built as a console-based tool, it reinforces file handling, string manipulation, and user interaction in C.

- **Developer:** Haluk Can SARIÖZ
- **Type:** Console Dictionary Application
- **Purpose:** Practice C programming and algorithm development

---

## Features
- **Bidirectional Translation:** English → Turkish and Turkish → English word lookup.
- **External Word Lists:** Dictionary data is stored in separate `.txt` files and can be easily expanded.
- **Simple & Clean Code:** Beginner-friendly C code with clear logic.
- **Fast Execution:** Console-based design ensures low resource consumption.

---

## Technologies Used
- **C Programming Language** – Primary development language.
- **GCC / G++** – Compilation tools.
- **VS Code / Dev-C++** – Development editors.

---

## Installation & Usage

### 1. Clone the Repository
```bash
git clone https://github.com/halukcansarioz/Dictionary-App.git
```

### 2. Navigate to the Project Directory
```bash
cd Dictionary-App
```

### 3. Compile the Application

**Linux / macOS:**
```bash
gcc sozluk.c -o sozluk
```

**Windows (MinGW / GCC required):**
```bash
gcc sozluk.c -o sozluk.exe
```

### 4. Run the Application
```bash
# Linux / macOS
./sozluk

# Windows
sozluk.exe
```

> ⚠️ **Note:** Ensure that `ingilizce.txt` and `turkce.txt` are in the same directory as the executable.

---

## Project Structure
```text
Dictionary-App/
├── sozluk.c               # Main application source code
├── sozluk.exe             # Compiled Windows executable (optional)
├── ingilizce.txt          # English word list
├── turkce.txt             # Turkish word list
├── .gitattributes         # Git configuration
└── README.md              # Project documentation
```

---

## Development Process

### 1. Fork the Repository
Fork the project to add your own features or expand the word list.

### 2. Create a New Branch
```bash
git checkout -b feature/add-new-words
```

### 3. Push Your Code
```bash
git push origin feature/add-new-words
```

---

## Contributing
1. **Fork** this repository.
2. Create a **Branch** (`git checkout -b feature/NewFeature`).
3. Add new words or improve the code.
4. **Commit** your changes (`git commit -m 'Add: New words'`).
5. **Push** your branch (`git push origin feature/NewFeature`).
6. Open a **Pull Request**.

> 💡 **Tip:** When adding words, make sure the order in `ingilizce.txt` and `turkce.txt` matches exactly.

---

<a name="contact"></a>
## Contact
**Haluk Can Sarıöz**
- GitHub: [@halukcansarioz](https://github.com/halukcansarioz)
- Email: [halukcansarioz19@gmail.com](mailto:halukcansarioz19@gmail.com)
- LinkedIn: [Haluk Can Sarıöz](https://www.linkedin.com/in/halukcansarioz)

**Project Link:** [https://github.com/halukcansarioz/Dictionary-App](https://github.com/halukcansarioz/Dictionary-App)

---

## License
This project is licensed under the [MIT License](LICENSE).
