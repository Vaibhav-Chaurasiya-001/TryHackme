# Linux Fundamentals (P-1) :


## Task-1 (Introduction) 

* Linux is a popular open-source operating system kernel originally created by Linus Torvalds in 1991.
* Linux is just another operating system and one of the most popular in the world powering smart cars, android devices, supercomputers, home appliances, enterprise servers, and more.
* Common Terms : 

    1. **Unix-like**: Based on Unix principles, providing stability, security, and multi-user support.

    2. **Shell**: Command-line interface like Bash; powerful for scripting and automation.

    3. **Distributions (Distros)**: Common ones are Ubuntu, Fedora, Debian, CentOS, Arch Linux—each,etc.

## Task-2 (A Bit of Background of Linux)
**Answer the questions below**  
Research: What year was the first release of a Linux operating system?

```
1991
```

## Task-3 (Interacting With Our First Linux-Machinge)
**Answer the questions below**

I've deployed my first Linux machine!
```
No Answer needed
```
## Task-4 (Running The First Few Commands)

Command	Description
 1. echo - Output any text that we provide.
 2. whoami - Find out what user we're currently logged in as!.

Answer the questions below - 

* If we wanted to output the text "TryHackMe", what would our command be?

    ```
    echo TryHackMe
    ```
* What is the username of who you're logged in as on your deployed Linux machine?
    ```
    tryhackme
    ```

## Task-5 (Interacting With The Filesystem)
### Interacting With the Filesystem

    1. ls - listing
    2. cd - change directory
    3. cat - concatenate
    4. pwd - print working directory
 
**Answer the questions below -**

* On the Linux machine that you deploy, how many folders are there?
    ```
    4
    ```
* Which directory contains a file?
    ```
    folder4
    ```

* Use the cd command to navigate to this file and find out the new current working directory. What is the path?
    ```
    /home/tryhackme/folder4
    ```

## Task-6 (Searching For Files)
Some Other Commands :
```
    Find - To Find something inside the system.
         - (-name pass.txt) to find file, when name is known.
         - (-name *.txt) to find file, when name is not known.
    
    Grep - searching plain-text data for lines that match a specific pattern. 
         - (-R) for recursive searching


```

**Answer the questions below**

* Use grep on "access.log" to find the flag that has a prefix of "THM". What is the flag? Note: The "access.log" file is located in the "/home/tryhackme/" directory.
```
THM{ACCESS}
```

* And I still haven't found what I'm looking for!
```
No Answer needed
```

## Task-7 (Introduction To Shell Operators)
Linux operators are a fantastic way to power up your knowledge of working with Linux. 
```
    & - This operator allows you to run commands in the background of your terminal.
    && - This operator allows you to combine multiple commands together in one line of your terminal.
    > - This operator is a redirector - meaning that we can take the output from a command (such as using cat to output a file) and direct it elsewhere.
    >> - This operator does the same function of the > operator but appends the output rather than replacing (meaning nothing is overwritten).
```

**Answer the questions below**
* If we wanted to run a command in the background, what operator would we want to use?
```
    &
```
* If I wanted to replace the contents of a file named "passwords" with the word "password123", what would my command be?
```
echo password123 > passwords
```
* Now if I wanted to add "tryhackme" to this file named "passwords" but also keep "passwords123", what would my command be
```
echo tryhackme >> passwords
```
* Now use the deployed Linux machine to put these into practice
```
No Answer needed
```


## Task-8 (Conclusion & Summaries)
To quickly recap, we've covered the following:

* Understanding why Linux is so commonplace today  
* Interacting with your first-ever Linux machine!  
* Ran some of the most fundamental commands  
* Had an introduction to navigating around the filesystem & how we can use commands like find and grep to make finding data even more efficient!  
* Power up your commands by learning about some of the important shell operators. 

**Answer the questions below**  

I'll have a play around!
```
No Answer needed
```
<hr>