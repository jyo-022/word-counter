📄 Word Counter – Python

 🔍 Description

This project is a basic-level Python script that **reads a text file** and **counts the number of words** in it. It is designed to demonstrate file handling, error handling, and basic string operations in Python.


 🎯 Objectives

* 📂 Read the content of a text file
* ✂️ Split the content into individual words
* 🔢 Count and display the number of words
* ⚠️ Gracefully handle exceptions like *File Not Found*


🧠 How It Works

1. The program asks the user to input the filename (with extension).
2. It opens and reads the file using 'with open'
3. It splits the entire content into words using '.split()'
4. It counts the words using 'len()' and prints the total.
5. If the file doesn’t exist, it catches the 'FileNotFoundError' and displays a helpful message.

## 🛠️ Tech Stack

* Python 3.x
* No external libraries required

💻 Usage
python word_counter.py

📝 Enter a valid filename when prompted, for example: 
      Enter the filename to count words: sample.txt

⚠️ Error Handling
    If the file does not exist, you’ll get a clear error message:
     "Error: The file 'sample.txt' was not found."
