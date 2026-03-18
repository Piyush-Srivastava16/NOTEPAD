# 📝 Java Notepad Application

A simple **Notepad-like text editor** built using **Java Swing**. This project demonstrates GUI development, file handling, and basic text editing features in Java.

---

## 🚀 Features

### 📁 File Operations

* Create a new file
* Open existing files
* Save files
* Save As functionality
* Exit application

### ✏️ Edit Options

* Copy / Cut / Paste (with keyboard-style options)
* Custom **stack-based clipboard**
* Insert current **Time & Date**

### 🎨 Formatting

* Word Wrap ON/OFF
* Multiple fonts:

  * Arial
  * Comic Sans MS
  * Times New Roman
* Adjustable font sizes (8 to 28)

### 🎨 Background Colours

* White
* Black
* Blue

---

## 🏗️ Project Structure

```
├── GUI.java        # Main application window and event handling
├── File.java       # File operations (open, save, etc.)
├── Edit.java       # Editing features (copy, paste, time/date)
├── Format.java     # Font and word wrap settings
├── Colour.java     # Background color handling
```

---

## 🛠️ Technologies Used

* Java
* Java Swing (GUI)
* AWT (for dialogs, colors, fonts)

---

## ▶️ How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. **Navigate to project folder**

   ```bash
   cd your-repo-name
   ```

3. **Compile the project**

   ```bash
   javac *.java
   ```

4. **Run the application**

   ```bash
   java GUI
   ```

---

## 📌 Notes

* The project uses a **custom stack clipboard** in addition to normal copy-paste.
* GUI is built using **JFrame, JTextArea, JMenuBar, and FileDialog**.
* Simple and beginner-friendly structure for learning Java GUI concepts.

---

## 💡 Future Improvements

* Add keyboard shortcuts (Ctrl+C, Ctrl+V, etc.)
* Add dark/light theme toggle
* Add undo/redo functionality
* Add search and replace feature
* Improve UI design

---

## 👨‍💻 Author

Your Name
GitHub: https://github.com/your-username

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!

