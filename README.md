# Windows-basic-commands-batchscript
## Ex08-Windows-basic-commands-batchscript
## NAME: SANTHOSH T
## REGISTER NO: 212223220100

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT
![alt text](<Screenshot 2024-10-19 220055.png>)

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.


## COMMAND AND OUTPUT
![alt text](<Screenshot 2024-10-19 220108.png>)

List the contents of the "MyLab" directory.


## COMMAND AND OUTPUT
![alt text](<Screenshot 2024-10-19 220127.png>)

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT
![alt text](image.png)
![alt text](image-1.png)

Move the "MyLab" directory to the "Documents" folder.


## COMMAND AND OUTPUT
![alt text](<Screenshot 2024-10-19 221311.png>)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
```notepad
open a notepad file named BackupScript.bat and enter the following:
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\DocBackup\*.docx
echo Backup and deletion completed successfully!

Save the file and come back to command prompt.
Now execute as
BackupScript.bat

```






## OUTPUT
![alt text](image-2.png)




# RESULT:
The commands/batch files are executed successfully.

