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
