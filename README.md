# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"
```
mkdir %userprofile%\Desktop\MyLab
```
![444634285-80370d59-0fee-4bd3-8c8d-75579ea43f9b](https://github.com/user-attachments/assets/94bb22ac-d40a-4c68-83c6-a6b35e3b2cb8)

## COMMAND AND OUTPUT

Remove the directory "my-folder"

## COMMAND AND OUTPUT
```
cd %userprofile%\Desktop\MyLab
```
![444634434-35039e63-542e-406a-a069-0c354690f62d](https://github.com/user-attachments/assets/1bcc7e5c-8e15-4e60-8a5b-594a83f231a5)
![444634487-212e2ccf-0e2e-49e0-8c37-9762f0bd38d5](https://github.com/user-attachments/assets/b46bc1c9-246a-48f3-9f35-0f343a644b42)

Create the file Rose.txt

## COMMAND AND OUTPU
```
dir %userprofile%\Desktop\MyLab
```
![444634695-ca7e36bd-0027-43a9-913d-57176ea59df2](https://github.com/user-attachments/assets/4bb76f3f-8202-4d21-a1ef-7e78fe15a77a)

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Backup

copy MyFile.txt %userprofile%\Desktop\Backup
```
Copy the file hello.txt into the file hello1.txt
![444634913-1aa3e077-5820-477e-b05c-bac217f007d5](https://github.com/user-attachments/assets/e2558c64-2904-41b3-83cd-7e8fd128a43e)
![444635001-bf0c292e-7677-49dc-9dc3-09db0766a3df](https://github.com/user-attachments/assets/d7d04231-c1b3-44a4-882c-f53b12aa3c3b)



## COMMAND AND OUTPUT
```
mv Myfile.txt %userprofile%\Documents
```
Remove the file hello1.txt
![444635197-13d10e67-7ecf-477d-819a-f8606fb2b4c9](https://github.com/user-attachments/assets/172379a2-6626-457b-80e7-2e2de6c36ecf)

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

List out all the associated file extensions 

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```



## OUTPUT

![444635643-fafecf65-151a-4219-956d-712d7b07c092](https://github.com/user-attachments/assets/dfd1187b-0282-4b39-a394-c40776d8c9d9)


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT



# RESULT:
The commands/batch files are executed successfully.

