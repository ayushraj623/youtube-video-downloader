# 📺 YouTube Video Downloader

A lightweight Python utility script to download YouTube videos directly to your local machine at their highest available resolution.

## 🚀 Features
* **High-Quality Downloads:** Utilizes the `pytubefix` library to automatically fetch and download the highest resolution `.mp4` stream available for a given video.
* **Interactive Directory Selection:** Uses Python's built-in `tkinter.filedialog` to open a graphical pop-up window, allowing users to easily choose exactly where they want to save their video.
* **Error Handling:** Includes `try/except` blocks to safely catch and print download errors without instantly crashing the application.

## 📋 Prerequisites
Ensure you have Python installed on your system. 

You will also need to install the `pytubefix` library (a reliable, actively maintained fork of `pytube`). You can install it via pip:
```bash
pip install pytubefix
