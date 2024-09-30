# Basic Keylogger Program

## Description
This is a basic keylogger program written in C for educational purposes. It records keystrokes and logs them into a file named keylog.txt. The program logs both individual characters and special keys (e.g., space, enter, shift, etc.). Note: This program should only be used with proper ethical considerations and permission from the owner of the computer being monitored.

## Features
*Keystroke Logging: Captures all keys pressed, including letters, numbers, and special keys (e.g., backspace, enter, tab).
*File Logging: Saves all captured keystrokes to a file (keylog.txt) for review.
*Continuous Capture: The keylogger runs indefinitely until manually terminated.

## Ethical Considerations
Using keyloggers without consent can lead to serious legal and ethical issues. Always ensure that you:

*Have explicit permission from the owner of the device on which you plan to use this program.
*Use this tool only for legitimate purposes, such as security audits or parental control.
*Unauthorized use of keyloggers is illegal in many jurisdictions and could lead to prosecution.

## Usage
Install a C Compiler: Ensure you have a C compiler installed (e.g., MinGW or Visual Studio).
Copy code
Compile the program.
Run the keylogger:

The program will create or append to a file called keylog.txt where all captured keystrokes are stored.

Stop the program: To stop the keylogger, manually terminate the process (e.g., by closing the terminal or pressing Ctrl + C).

## Example Output
An example of what the log file (keylog.txt) might look like:

Hello[SPACE]World[ENTER]
[SHIFT]This[SPACE]is[SPACE]a[SPACE]Test!

## Limitations
This program works only on Windows, as it uses the windows.h library and Windows-specific APIs like GetAsyncKeyState.
It runs indefinitely and must be manually stopped.
The current implementation logs basic keystrokes without timestamp or context information.

## Legal Disclaimer
This program is provided strictly for educational purposes. Misuse of this software can result in criminal charges. By using this program, you agree to take full responsibility for its use and understand the legal implications involved.

## License
This project is licensed under the MIT License.
