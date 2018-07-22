# CS 193 Lab 2 - Unix Commands
The purpose of this lab is to teach the basics of using the terminal. After you finish this lab, you will be able to manipulate files on any UNIX-like machine (including your Purdue CS account)!

Before starting the lab, you might want to check out the [Cheat Sheet](https://github.com/ssagheer532/CS193_Fall18_Lab2/blob/master/cheat-sheet.md) to review all the common commands. 

### Getting Started
In order to start working on this lab, you're going to first clone this repo. Cloning a git repository essentially means you're create a local copy of all the code. If you want to learn more about cloning, go [here!](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-clone).

Here are the steps in order to get your local repo set up: 

1. Open up the terminal and go to the folder where you want to save this repository (it can be any folder including your home directory) 
2. Go to the main repo page on github and find the green button called "clone or download" on the right side. Click it and copy the url. Now go back to the terminal and run 'git clone INSERT_URL_HERE'. Now if you type 'ls' and press enter you should see a new folder called "CS193_Fall18_Lab2"
3. Go to the "CS193_Fall18_Lab2" folder by running 'cd CS193_Fall18_Lab2' 
4. Run 'bash lab2init' in order to generate the files and folders for the rest of the lab. Note, a new folder called cs193lab2 will be generated in your home directory. Run 'cd ~' to go to your home directory and 'cd' into "cs193lab2" 

### Folder Structure 
Below is the folder structure that is generated from running the script command. As you can see, there are some problems. For example, ma261 is in the computer science folder instead of the math folder. Throughout this lab, you will write terminal commands that fix these mistakes.

        cs193lab2/
        ├── purdue buildings/
        │   ├── Lawson
        │   ├── Hicks
        │   ├── Rawls
        |   ├── Professor Dunsmore
        |   ├── Professor Comer
        │   ├── Krannert
        |
        ├── purdue classes/
        |   ├── computer science/
        |   |   ├──cs180
        |   |   ├──cs182
        |   |   ├──ma261
        |
        |   ├──math/ 
        |   |   ├──maa162
        |   |   ├──ma153
        |   |   ├──pol341
       
 ## Rules and Example Task 
There are 6 tasks, and you will write 6 **one line** terminal commands that fulfill that task. Each command may only contain **ONE BASE COMMAND** (`mv`, `ls`, `cp`, `rm`, etc). You may not combine different base commands (`cd`, `mv`) into one response, and you may not combine two of the same base commands (`mv`, `mv`) into one response. Examples of this are below in the *Task 0 Example*.

**All commands should be recorded in answers.txt. This file is located in your cloned repo!** 

> NOTE: Do not save this file within `~/cs193lab2` because that folder and all of its contents will be erased each time you run the bash init script


#### Example: Task 0 

    Working Directory:  ~/cs193lab2/

    Desired Action:     print out only the contents of the folder "purdue buildings"

    Write the answer under the Task 0 block. Make sure not to put '#' before your answer.

#### Example: Task 0 Sample Answer 
    # -----------------
    # Task 0 Answer
    # -----------------
    ls "purdue buildings"

This above answer is allowed because it is on one line and only contains one base command, which in this case, is a single `ls`.  


## Assigned Tasks 
Solve all 6 of these tasks, and record your answers in the `answers.txt` file. 

    
 #### Task 1

    Working Directory:  ~/cs193lab2/

    Desired Action:    rename the file maa162 located in ~/cs193lab2/purdue classes/math to ma162 

    Write the answer under the Task 1 block.
  #### Task 2

    Working Directory:  ~/cs193lab2/

    Desired Action:    remove the file pol334 located in ~/cs193lab2/"purdue classes"/math to ma162 

    Write the answer under the Task 2 block.
    
   #### Task 3

    Working Directory:  ~/cs193lab2/

    Desired Action:    move the file ma261 located in ~/cs193lab2/"purdue classes"/"computer science" to the math folder located in ~/cs193lab2/"purdue classes"

    Write the answer under the Task 3 block.
#### Task 4

    Working Directory:  ~/cs193lab2/

    Desired Action:     make a folder called "purdue professors" with a folder inside called "computer science professors" in the working directory

    Write the answer under the Task 4 block.
#### Task 5 

    Working Directory:  ~/cs193lab2/

    Desired Action:     move "Professor Dunsmore" and Professor Comer" to the newly created folder called "computer science professors"

    Write the answer under the Task 5 block.
#### Task 6 

    Working Directory:  ~/cs193lab2/

    Desired Action:     print out  the contents of all folders and subfolders in the working directory
    
    Write the answer under the Task 6 block.
        
Here is how the folder structure should look at the end of all tasks. 

    cs193lab2/
        ├── purdue buildings/
        │   ├── Lawson
        │   ├── Hicks
        │   ├── Rawls
        │   ├── Krannert
        |
        ├── purdue classes/
        |   ├── computer science/
        |   |   ├──cs180
        |   |   ├──cs182
        |
        |   ├──math/ 
        |   |   ├──ma162
        |   |   ├──ma153
        |   |   ├──ma261
        |
        ├── purdue professors/
        |   ├── computer science professors/
        |   |  ├── Professor Dunsmore
        |   |  ├── Professor Comer
        
       
#### How to Submit: 
