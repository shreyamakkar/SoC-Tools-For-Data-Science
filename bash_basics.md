# Basic Bash Commands for Git Bash
### To change the directory/ folder you are in
cd refers to change directory
```
cd [folder]
cd [path_of_the_folder]
```
Example:  
``` cd test ``` is used to go to the test folder inside the current folder  
``` cd c: ``` is used go to the C drive in Windows  
``` cd c:\test ``` is used go to the test flder in C drive in Windows

### To know the current working directory
pwd stands for print working directory
```
pwd
```
### To know the contents of the directory
ls is to list all files and folders in the current working directory
```
ls [options]
```
Example:
```
ls
ls -a
ls -al
ls -l
```
```-a``` and ```-l``` are options. ```-a``` means all the files including hidden files and ```-l``` means shows the details in the long format. [More here](https://www.rapidtables.com/code/linux/ls.html)
### To make a new directory
mkdir stands for nake directory
```
mkdir [directory_name]
```
### To make a new file
touch creates a file without any content
```
touch [options] [filename]
```
Example:
```
touch test.txt
```
Note include the file extension in the filename
### To delete a file
rm stands for remove
```
rm [options] [filename]
```
Example:
``` 
rm test.txt
```
Note: include the file extension in the filename
### To delete a directory
```
rm -r [directory_name]
```
-r is an option which means recursive. [More here](https://www.geeksforgeeks.org/rm-command-linux-examples/)
### To copy a file/ directory
cp stands for copy
```
cp [options] [source] [destination]
```
Example:
```
cp test.txt test1.txt
```
[More here](https://www.geeksforgeeks.org/cp-command-linux-examples/#:~:text=cp%20stands%20for%20copy.,two%20filenames%20in%20its%20arguments.)
### To move a file/ directory
mv stand for move
```

mv [options] [source] [destination]
```
Example:  
``` 
mv test.txt test1.txt
```
The command renames the file name from test to test1. [More here](https://www.geeksforgeeks.org/mv-command-linux-examples/)
### Other commands
* [echo](https://www.geeksforgeeks.org/echo-command-in-linux-with-examples/)
* [cat](https://www.tecmint.com/13-basic-cat-command-examples-in-linux/)
