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

## COMMAND AND OUTPUT
```
mkdie my-folder
```
![Screenshot 2025-05-26 141820](https://github.com/user-attachments/assets/7eb7aa27-7ba6-4ed1-b469-265564879138)

Remove the directory "my-folder"

## COMMAND AND OUTPUT
```
rmdir my-folder
```
![Screenshot 2025-05-26 141949](https://github.com/user-attachments/assets/91ce3deb-972b-4ed5-aa7b-a8695dd12803)

Create the file Rose.txt

## COMMAND AND OUTPUT
```
COPY CON Rose.txt
A clock in a office can never get stolen
Too many employees watch it all the time

```
![Screenshot 2025-05-26 142028](https://github.com/user-attachments/assets/6c17d6fd-e28f-4734-b9f1-fd8422c70855)

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
```
echo “hello world” > hello.txt
type hello.txt

```
![Screenshot 2025-05-26 142551](https://github.com/user-attachments/assets/5ae47202-ac90-4c25-86be-cf4131e3a25f)

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
```
copy hello.txt hello1.txt
```
![Screenshot 2025-05-26 142551](https://github.com/user-attachments/assets/9bcc9583-e845-4cc6-b0d4-525d00106598)


Remove the file hello1.txt

## COMMAND AND OUTPUT
```
del hello1.txt
```
![Screenshot 2025-05-26 142635](https://github.com/user-attachments/assets/e23e3b93-1220-4cc2-804e-5ede1abc363d)


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
```
dir hello1.txt
```
![Screenshot 2025-05-26 142635](https://github.com/user-attachments/assets/c041e533-4525-44f1-b5db-4399403f7ace)


List out all the associated file extensions 

## COMMAND AND OUTPUT
```
assoc | more
```
![Screenshot 2025-05-26 142703](https://github.com/user-attachments/assets/f947c263-21ff-4010-8824-473271720267)

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
```
copy hello.txt hello1.txt
```
![Screenshot 2025-05-26 142720](https://github.com/user-attachments/assets/8dc5259d-163c-4994-828d-d25f0daba916)

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

![Screenshot 2025-05-26 142754](https://github.com/user-attachments/assets/cc99b9b4-343e-4f71-a732-ba470f1f4db1)


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

![Screenshot 2025-05-26 142801](https://github.com/user-attachments/assets/7ff07a9d-4661-4b95-805f-0579593413be)



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


![Screenshot 2025-05-26 142813](https://github.com/user-attachments/assets/93ba0183-9d92-4d89-b2de-898ac1e30eb4)


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

![Screenshot 2025-05-26 142826](https://github.com/user-attachments/assets/1f97cb7c-15a5-41cf-9244-5f13ba5deaca)

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

![Screenshot 2025-05-26 142840](https://github.com/user-attachments/assets/8f5ca882-8e5b-4ae7-892a-7b3e2ef11ed7)


# RESULT:
The commands/batch files are executed successfully.

