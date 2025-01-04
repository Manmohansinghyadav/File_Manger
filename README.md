# File Manager

This project is a simple command-line file manager in C++ that allows users to perform basic file operations like listing files, creating directories, copying/moving files, and reading files. It utilizes the C++17 `<filesystem>` library for file system manipulation.

# Features

1. **List Files**  
   Lists all files and directories in the specified directory.
   
2. **Create Directory**  
   Creates a new directory at the specified path.

3. **Copy File**  
   Copies a file from a source location to a destination, overwriting if the file already exists.

4. **Move File**  
   Moves a file from the source path to the destination path.

5. **View File**  
   Displays the contents of a text file in the terminal.

# Requirements

- C++17 or higher
- A C++ compiler (e.g., GCC, Clang)

# How to Compile

1. Open a terminal or command prompt.
2. Navigate to the directory where the `file_manager.cpp` file is located.
3. Compile the code using the following command (assuming you are using `g++`):
4. Run the program:
   g++ -std=c++17 -o file_manager file_manager.cpp


# Usage

Upon running the program, you will be presented with a menu where you can enter your choice:

Command-Line File Manager

List files in a directory
Create a directory
Copy a file
Move a file
View a file
Exit

