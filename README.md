# Automated_file_manager
 Python-based automated file organizer that sorts files into folders by type (images, documents, text files) using the shutil and os libraries.
Automated File Organizer 📁
Description
The Automated File Organizer is a Python project that sorts and organizes files by type (images, documents, text files) into designated folders. It uses Python's shutil and os libraries to identify file types and move them into specific directories, keeping your workspace clean and organized.

Features

Automatically categorizes files based on their extensions (.jpg, .pdf, .txt).

Organizes files into pre-defined folders (e.g., images, documents, text).

Simple and efficient way to manage files in bulk.

Technologies Used

Python

shutil library for file operations

os library for directory handling

Getting Started

Prerequisites
Python 3.x: Make sure Python is installed on your machine. You can download it here.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/your-repo-name.git
Navigate to the project directory:

bash
Copy code
cd your-repo-name
Run the Python script: Run the code from your local environment (e.g., VS Code or command line) to see the automated file organization in action.

How to Use
Set up the base directory:

Ensure that your target files are in the combine folder within the specified base directory (e.g., D:\SHUTIL\combine).
Run the script:

Execute the Python script, and it will create folders (documents, image, txt) in the base directory and organize files by type.
Output:

After running, the combine folder's contents will be moved to the appropriate folders based on file extension.
Example Code Snippet
Here’s a sample of how the project code works:

python Copy code
import shutil
import os

# Define the base folder and file categories
folders = ["documents", "image", "txt", "combine"]
base_dir = "D:\\SHUTIL\\"

# Code to create folders and organize files by type
...
Project Structure
sql
Copy code
|-- D:\SHUTIL\
|   |-- combine\             # Folder with mixed file types to be organized
|   |-- documents\           # Folder for PDF files
|   |-- image\               # Folder for JPG files
|   |-- txt\                 # Folder for TXT files
Future Enhancements
Add support for more file types.
Implement user input for dynamic file path setup.
Create a GUI for easier interaction.

Contributing
Feel free to submit issues or pull requests for improvements and new features. Contributions are always welcome!

License
This project is licensed under the MIT License. See the LICENSE file for details.