# 📁 Advanced File Organizer Bot

A smart desktop tool to **auto-organize files** in real-time as they're added to a folder — based on **extension**, **type**, or **size**. Built with `tkinter` for the UI and `watchdog` for monitoring.

---

## ✨ Features

- ✅ Organize files:
  - By extension (`.PDF`, `.JPG`, etc.)
  - By file type (Image, Document, Video, etc.)
  - By file size (Small, Medium, Large)
- 📂 Choose any folder to monitor
- 📡 Auto-sorts files as soon as they appear
- 🖥️ Clean GUI using Python’s `tkinter`
- 🧠 Error-handled and robust

---

## 🛠️ Requirements

- Python 3.x
- Required packages:

```bash
pip install watchdog
````

> ✅ `tkinter`, `os`, `shutil`, and `time` are part of the Python standard library.

---

## 🚀 How to Run

1. 💾 Save the file as:

   ```
   Advanced File Organizer Bot.py
   ```

2. Open your terminal or command prompt.

3. 🏃‍♂️ Run the script:

```bash
python "Advanced File Organizer Bot.py"
```

---

## 🖱️ How to Use

1. Click **📂 Browse** and select the folder to monitor.
2. ✅ Choose one or more **sorting options**:

   * By Extension
   * By File Type (Image, Document, Video, etc.)
   * By File Size (Small <1MB, Medium <10MB, Large >10MB)
3. Click **▶ Start Organizing and Monitoring**
4. 🛑 Keep the window open — it runs until you close it.

---

## 📁 Folder Structure Output Example

With "By File Type" enabled:

```
Downloads/
├── Image_Files/
│   └── pic.jpg
├── Document_Files/
│   └── resume.pdf
├── Video_Files/
│   └── demo.mp4
├── Other_Files/
│   └── setup.exe
```

---

## 📌 Notes

* Combines sorting logic based on user selection — can sort by multiple rules.
* Add delay to file move (1 second) to ensure file writes are complete before moving.
* Safe error handling for corrupt or locked files.

---

## 🧑‍💻 Author

Crafted with 💚 using Python, `tkinter`, and `watchdog`.

---

Take control of your messy folders — auto-organize like a pro! 🚀🗂️🤖

```
