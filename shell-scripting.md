
# Shell Scripting

## 1) How to create a file?
    touch file_name     -> using this command

## 2) How to list the files & folders?
    ls                  -> will show all files 
    ls -ltr             -> show files with timestamp

## 3) man command in Linux: 
- man is stands for manual 
- Just suffix any command with man and simply type the command.
- It will give you the detail information of that perticular command
- ex. man touch , man ls

## 4) How to write a file in Linux?
    vi file_name        -> will open the file for writing the content

## 5) Difference between vi & touch command: 

- touch command we use in automation.
- vi command we use for write inside the file or in case file dosen't exists then it create and open for write inside the file.

## 6) What is the purpose of --> #!/bin/bash
    #!/                  -> shebang
- bash or sh or ksh or dash this are differnt executables of your shell script 
- executables that run the program 

## 7) Difference between sh , bash , dash and ksh:

- sh --> Original Unix shell, basic and portable.
- bash --> Advanced, user-friendly, and feature-rich shell.
- dash --> Minimal, fast, and optimized for system scripts.
- ksh --> Powerful shell with advanced scripting for enterprises.

## 8) How to use insert command in linux?

- once you use vi command to open the file then you have to do next steps:
    - press 'esc' key then 'i' for insert
    - after this you can write somthing in your file.
    - after writing the file you need to save the file using 'esc' + ':wq!' for saving the file
    - for reading the content of the file you need to use 

        ```cat file_name```  ---> will show all the content of file.
## 9) How to execute a shell Script?
- for any executables file we can use 
    
    ```./file_name or sh file_name```

## 10) How to grant permissions in linux?
- using chmod command you can change permissions access mode 
 
 ```chmod 777 file_name```
 -  this each 7 is stands for :
    - 4 -> read
    - 2 -> write 
    - 1 -> execute

## 11) How to check the history of commands?
 - using command  ```history```

## 12) How to create folders?
- using ```mkdir folder_name```

## 13) How to change the directory in linux? 

- using ```cd``` command 
- ```cd``` is stands for change directory
- if you want to go out from the current directory you can use ```cd .. or cd ../..```

## 14) How to check CPU and RAM of a linux machine?

- for RAM you can use ```free``` command
- for CPU you can use ```nproc``` command
- using ```top``` command you can easily identify the processes that are running on your machine

## 15) What is the purpose of shell scripting in devops?
- shell scripting languages, such as bash, are used for automating tasks in devops workflow.
- They provide a command-line interface for interacting with the operating system and executing commands.
- shell scripts use variables to store and manipulate data.
