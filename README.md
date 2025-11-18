a# Windows-basic-commands-batchscript
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

## COMMAND AND OUTPUT
<img width="1082" height="268" alt="image" src="https://github.com/user-attachments/assets/b9f5e5a1-6735-44c8-8a7c-405bb6396277" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="1096" height="358" alt="image" src="https://github.com/user-attachments/assets/3c6f92b7-1dfa-4f4f-aca5-92529f50a685" />

Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="1056" height="403" alt="image" src="https://github.com/user-attachments/assets/b48fc36e-4662-4c8a-961b-c72553a067b9" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="1179" height="117" alt="image" src="https://github.com/user-attachments/assets/2a133742-1460-4011-a032-2c2a382fb8bb" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="1128" height="138" alt="image" src="https://github.com/user-attachments/assets/9bdbf924-ba91-4232-853b-a81dfe3e44e8" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="1032" height="56" alt="image" src="https://github.com/user-attachments/assets/74958b83-21b8-4cdc-adbd-4ee4b279874d" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="1032" height="209" alt="image" src="https://github.com/user-attachments/assets/e375c9b8-29d9-4a38-9518-db8bff5d6537" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="1038" height="396" alt="image" src="https://github.com/user-attachments/assets/080535c3-1cd6-4275-9011-074ab5c823da" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="1070" height="208" alt="image" src="https://github.com/user-attachments/assets/80d0986f-c50a-4d3a-84ee-9f096768b2dd" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

<img width="547" height="227" alt="image" src="https://github.com/user-attachments/assets/15152c91-0358-454c-9dd7-0203a25c9bdc" />


## OUTPUT

<img width="1014" height="99" alt="image" src="https://github.com/user-attachments/assets/bb127444-0c2e-48c8-9128-ea8a5228a840" />

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

<img width="731" height="525" alt="image" src="https://github.com/user-attachments/assets/ae6d1662-7421-4fd2-9b45-b1e744a55eec" />


## OUTPUT

<img width="962" height="252" alt="image" src="https://github.com/user-attachments/assets/ea98b1a7-dac4-473a-8eb1-84fc8b488510" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

<img width="477" height="245" alt="image" src="https://github.com/user-attachments/assets/4ee8e761-4ff5-41a2-bdfc-78e71f774c5e" />



## OUTPUT
<img width="1009" height="200" alt="image" src="https://github.com/user-attachments/assets/253f8f2c-5137-472e-8881-0036c177c2c6" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):
<img width="524" height="285" alt="image" src="https://github.com/user-attachments/assets/621617df-5f2d-49c4-897f-f6ed791b67c6" />

## OUTPUT
<img width="1205" height="250" alt="image" src="https://github.com/user-attachments/assets/ebd8d92e-63df-40ef-bf4d-c3516063510b" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.
<img width="780" height="574" alt="image" src="https://github.com/user-attachments/assets/92877ea0-f6cb-4229-be32-38a3fec684be" />


## OUTPUT
<img width="1056" height="456" alt="image" src="https://github.com/user-attachments/assets/af1a68a4-964c-4a80-bce6-2ee96f38d8aa" />



# RESULT:
The commands/batch files are executed successfully.

