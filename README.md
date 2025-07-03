🧠 Typing Speed Test in Python
A simple terminal-based typing speed test built using Python. This project allows users to test their typing speed in words per minute (WPM) and accuracy by typing randomly selected sentences.

🛠️ Features
Random sentence selection

Real-time typing test

Calculates:

Typing speed (WPM)

Accuracy (%)

Easy to run in the terminal

Clean and beginner-friendly code

📸 Demo
yaml
Type the following sentence:
> The quick brown fox jumps over the lazy dog.

Start typing below:

Your input: The quick brown fox jumps over the lazy dog
Time taken: 10.45 seconds
WPM: 51.4
Accuracy: 100.0%
📂 Project Structure
bash
Copy
Edit
typing_test/
├── sentences.txt        # List of sentences for testing
├── typing_test.py       # Main Python script
└── README.md            # Project documentation
🚀 How to Run
Clone the Repository

bash
Copy
Edit
git clone https://github.com/yourusername/typing-test.git
cd typing-test
Install Requirements
No external libraries are required (uses built-in Python modules).

Run the Script

bash
python typing_test.py
🧠 How It Works
The program randomly selects a sentence from a file.

It records the start time and takes user input.

It then calculates the number of words typed per minute and the accuracy by comparing input with the original sentence.

✅ Example Sentence File (sentences.txt)
swift
The quick brown fox jumps over the lazy dog.
Typing is a fundamental skill in the digital age.
Practice makes perfect.
You can add more sentences to this file.

🧑‍💻 Technologies Used
Python 3

Standard libraries: time, random

📝 TODO (optional)
Add GUI using Tkinter or PyQt

Save high scores

Add difficulty levels (Easy, Medium, Hard)

Improve accuracy checking with typo tolerance

📃 License
This project is licensed under the MIT License.
