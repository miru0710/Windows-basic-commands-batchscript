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

Remove the directory "my-folder"
~~~
>mkdir my-folder
>rmdir my-folder
~~~
<img width="516" height="97" alt="image" src="https://github.com/user-attachments/assets/8c07959e-a626-49f9-a1a4-396b31e87c01" />


## COMMAND AND OUTPUT

Create the file Rose.txt
~~~
COPY CON Rose.txt
A clock in a office can never get stolen
Too many employees watch it all the time
^Z
1 file(s) copied
dir Rose.txt
~~~
<img width="787" height="402" alt="image" src="https://github.com/user-attachments/assets/94ffda31-9ca3-4b2a-95cf-390d278ccaaf" />


## COMMAND AND OUTPUT

Create the file hello.txt using echo and redirection
~~~
echo “hello world” > hello.txt
type hello.txt
~~~
<img width="677" height="122" alt="image" src="https://github.com/user-attachments/assets/62434592-82bb-4fb8-ac51-d5a122f297cf" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
~~~
copy hello.txt hello1.txt
~~~
<img width="612" height="72" alt="image" src="https://github.com/user-attachments/assets/7ae06418-eed2-41fa-9549-de007e5a6c54" />


## COMMAND AND OUTPUT

Remove the file hello1.txt
~~~
del hello1.txt
~~~
<img width="460" height="47" alt="image" src="https://github.com/user-attachments/assets/e542807d-cf4f-4ebf-bf10-32bf35b95a82" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory
~~~
dir hello1.txt
~~~
<img width="612" height="167" alt="image" src="https://github.com/user-attachments/assets/1e1e60cf-fa43-4828-8af9-2cb6ca5d6e65" />

## COMMAND AND OUTPUT

List out all the associated file extensions 
~~~
assoc | more
~~~
<img width="732" height="892" alt="image" src="https://github.com/user-attachments/assets/021e2515-97fc-46c9-b1b1-894417b51669" />

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT



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

