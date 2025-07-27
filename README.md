# File-organizer-project
Title: 
                Smart file organizer
NAME: 
                 Laiba Khalil

Submission Date:
                                  27-7-2025

1. Introduction
A desktop program called the Python File Sorter Tool was created to assist users in automatically classifying files in a folder according to their file types, such as text, PDF, and image files. It makes use of Object-Oriented Programming (OOP) concepts and offers a user-friendly graphical user interface.

2. Objectives
•	To create a file sorting application using Python and Tkinter.
•	To implement Object-Oriented Programming principles.
•	To provide a user-friendly GUI for folder selection and organizing.
•	To maintain a log of actions performed.
•	To include an Undo feature for reversing the last sorting action.
3. Technology Stack
Component	Technology
Language	Python
GUI Framework	Tkinter
Logging	Python logging module
File Operations	os, shutil, datetime
Undo Functionality	Custom implemented
IDE	PyCharm

4. System Design
The project consists of two main modules:
•	organizer.py: Contains the core logic using OOP for sorting, undo, and logging.
•	gui.py: Uses Tkinter to provide a graphical user interface to interact with the sorter.
A class called FileSorter is responsible for:
•	Scanning the directory.
•	Creating subfolders based on file extensions.
•	Moving files to their corresponding folders.
•	Logging the operations.
•	Reverting the last operation (undo).

5. Features
Sorts files based on extensions (.pdf, .txt, .jpg, etc.)
GUI for folder selection and actions
Log file to track sorting history
 Undo button to revert the last sorting
 Error handling (e.g., missing folder, permission issues)<img width="1053" height="412" alt="Screenshot 2025-07-27 162342" src="https://github.com/user-attachments/assets/d557e381-b923-484f-b779-ed846b60446b" />
<img width="1656" height="747" alt="Screenshot 2025-07-27 182132" src="https://github.com/user-attachments/assets/7666d9dd-14e7-4533-9ad8-ccd945fe36eb" />
<img width="1633" height="687" alt="Screenshot 2025-07-27 182105" src="https://github.com/user-attachments/assets/a795c619-91e1-40c8-8321-9a01c2cbb761" />

6. Implementation Details
•	GUI File (gui.py): Built using Tkinter with buttons for Choose Folder, Organize, Undo, and View Log.
•	Core Logic (organizer.py):
o	Reads files from the selected folder.
o	Sorts them into folders like Images, PDFs, Text Files, etc.
o	Keeps a history of moved files to enable undo.
o	Creates file_sorter.log to track all operations.

7. Testing
•	Tested using a variety of files (PDF, text, images, unknown formats).
•	All files were moved to their correct subfolders.
•	Undo functionality was tested after each sort operation.
•	Log file records every successful action and error if any.


8. Conclusion
This project shows how Python can be used practically to automate file management. The tool becomes functional and easy to use by combining GUI with backend logic. While robustness is added by logging and undo features, maintainability is enhanced by using OOP.

9. Future Improvements
•	Add support for custom rules (e.g., sorting by file size or date).
•	Provide preview before sorting.
•	Add multi-language support.
•	Allow scheduled or background sorting.

