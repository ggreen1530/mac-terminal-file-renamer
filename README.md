# Mac Terminal File Renamer

## 📌 Project Summary
This project demonstrates how to batch rename files in a folder using Mac’s built-in Terminal.

## 🚀 How It Works
1. Open Terminal and navigate to the folder.
2. Run the following command to rename `.txt` files:
   ```bash
   for file in *.txt; do mv "$file" "renamed_$file"; done
