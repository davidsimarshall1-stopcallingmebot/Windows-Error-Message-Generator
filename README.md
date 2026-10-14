# Windows Error Message Generator

A lightweight VBScript utility that generates customizable Windows error pop-up dialog boxes.

## Features

- Custom error message text and window titles.
- Flexible icon types (Critical Stop Sign, Warning, Information).
- Customizable button layouts (OK, OK/Cancel, Yes/No).
- Native Windows execution with no external dependencies required.

## How to Download and Run

1. Go to the [Releases](https://github.com/davidsimarshall1-stopcallingmebot/Windows-Error-Message-Generator/releases) section.
2. Download `error_generator.vbs` from the latest release assets.
3. Double-click the downloaded `.vbs` file to run it on your Windows machine.

## Customizing the Script

You can open `error_generator.vbs` in Notepad or any text editor to customize your pop-up window:

```vbs
Dim message, buttons, title, result

message = "Your custom error message goes here!"
buttons = vbCritical + vbOKOnly
title = "Custom Error Title"







result = MsgBox(message, buttons, title)
<img width="602" height="396" alt="image" src="https://github.com/user-attachments/assets/25008183-2a7b-42cc-ac15-d178d43ad129" />
Enter your custom messages. Then press "OK".
<img width="459" height="217" alt="image" src="https://github.com/user-attachments/assets/27c15648-2942-463d-a5a9-f3a3f276590a" />
Now, type in the window title, then click "OK".
<img width="472" height="247" alt="image" src="https://github.com/user-attachments/assets/844c7cac-221f-4cc0-b8b5-93b901037970" />
Choose a icon type like 16, 48, or 64. Then choose buttons type like 0, 1 or 4.
