# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > Command | Description
> > ------- | -----------
> > pwd | show current working directoty path
> > mkdir | creating a directoty
> > rm -r | deleating a directory
> > touch | creating a file
> > rm <filename> | deleting a file
> > mv <old file name> <new file name> | renaming a file
> > ls - | lists all files (including hidden files)
> > cp <filename> <new directory> | coping a file from one directory to another
> > cd | switches you into the directory you specify
> > sort | sorts the output
> > grep | searches files for lines that match a pattern and returns the results
---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > ls lists all files and directories in the working directory, la -a lists all contents in the working directory 
including hidden files and directories, ls -lh displays all files and directories in long list format with readable 
file size, ls -lah displays all files and directories in long list formatincluding hidden files with readable file 
size, ls -t lists all files sorted by time and date, ls -Glp lists all files in long list format including 
directories with / while excluding group names

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > ls -l, la -a, la -lh, ls -alt, ls -g

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > The 'xargs' command allows certain commands to accept standard inputs as arguments. For example, if you used 
the command echo 'one two three' with the command xargs mkdir, three folders would be created. 

 

