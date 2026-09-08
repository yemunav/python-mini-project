File Handling Application (Python Mini Project)

A simple, menu-driven Python program built to practice file handling and the os module, written and run in Jupyter Notebook (Anaconda Navigator).

This project was built as a mini-project for the Python course at Besant Technologies, as part of preparation for a Data Analytics role.

About

Instead of running each file operation as a separate, one-off notebook cell, this project brings every operation taught in class together into a single menu-driven application. Each operation is written as its own function, and one menu — running inside a loop — lets the user perform any of them, as many times as needed, until they choose to exit.

Menu Options
---------------FILE HANDLING MENU---------------
1. Create a File
2. Write Data
3. Read File
4. Replace File Content
5. Append to File
6. Rename File
7. Delete File
8. Show Current Directory
9. List Files in the Directory
10. Change the Directory
11. Exit
Concepts Used
File handling basics — open(), write(), read(), close()
File access modes — "w" (write/replace), "a" (append), "r" (read)
The os module — os.getcwd(), os.listdir(), os.chdir(), os.rename(), os.unlink()
Functions (def)
input() for interactive use
if / elif / else as a menu dispatcher
while loop for the repeating menu
int() type conversion for the menu choice
How to Run
Clone this repository:
   git clone https://github.com/yemunav/python-mini-project.git
Open File_Handling_app.ipynb in Jupyter Notebook (via Anaconda Navigator).
Run every cell from top to bottom so all functions are defined.
Run the final cell containing the menu loop, and enter a number (1–11) when prompted.
Project Structure
python-mini-project/
├── File_Handling_app.ipynb              # Main notebook with all functions and the menu
├── File_Handling_App_Report.pdf         # Full mini-project report (concepts, code, output screenshots)
└── README.md
Author

Yemuna V GitHub: github.com/yemunav

Acknowledgement

Trainer: Gowthami Shyam, Besant Technologies
