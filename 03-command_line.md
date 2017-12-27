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

> > 
Command | Action
------- | ------
ls | lists the files in your current directory. 
pwd | shows your working directory. 
cd | changes your working directory. 
mkdir | creates a new directory in your working directory. 
touch | creates a new file within your working directory. 
ls -a | lists files, including hidden ones, in your current directory 
cp a b | copies contents of "a" into "b"
mv | moves a file to a new folder, or can be used to rename
rm | remove files
rm -r | remove directories
cat | outputs contents of a file
cat > | redirect content
cat >> | *add* content
wc | outputs number of lines, words, characters
sort | alphabetically sorts content 
uniq | shows unique lines in file
grep -i x | lists lines with x in it, -i makes it case insensitive
sed s | find and replace strings
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

> > 
*long format* displays file mode, number of links, owner name, group name, byte size, month, day, year the file was last modified, and the pathname

Command | Action
------- | ------
ls | lists the files in your current directory
ls -a | lists all files, including hidden ones, in your current directory
ls -l | lists files in long format in your current directory
ls -lh | lists files in long format and uses unit suffixes for Byte, Kilobyte, Megabyte, etc in your current directory
ls -lah | lists all files, including hidden ones, in long format and uses unit suffixes to reduce digits
ls -t | lists all files sorted by time modified.  Most recent modified file will be first
ls -Glp | Enables colorized output and lists all files in long format while writing a slash after directories
---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > REPLACE THIS TEXT WITH YOUR RESPONSE

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > REPLACE THIS TEXT WITH YOUR RESPONSE

 

