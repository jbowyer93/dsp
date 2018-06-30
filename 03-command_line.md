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

> > Showing the current working directory path: pwd\
> > Creating a directory: mkdir _directoryname_\
> > Deleting a directory: rm -r _directoryname_\
> > Creating a file: touch _filename_\
> > Deleting a file: rm _filename_\
> > Renaming a file: _originalfilename_ > _newfilename_\
> > Listing hidden files: ls -a\
> > Copying a file from one directory to another: cp _filename_ _directorypath_\
> > Find and replace: sed 's/find/replace' _textfile_\
> > Moving a file: mv _filename_ _pathwaytonewplacement_

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

> > `ls`  List files in current working directory\
> > `ls -a`  List all things in current working directory, even hidden ones\
> > `ls -l`  List in long form\
> > `ls -lh`  List in long form in human readable format\
> > `ls -lah`  List  all things in long form and in human readable format\
> > `ls -t`  List all things sorted	by modification	  time\
> > `ls -Glp` List directories with / in long format without owner name

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > I find -R (displaying subdirectories), -u (displaying by file access time), -1 (displaying each entry on a line), -d (displaying only directories), and -F (flagging filenames) all to be particularly useful.

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > xargs is a command that converts input from standard input into arguments to a command. This is useful for commands that can only take input as arguments (echo, rm, and mkdir are examples). This example would create two directories with 'hello' and 'world' as their respective names:

> > echo 'hello world' | xargs mkdir
 




