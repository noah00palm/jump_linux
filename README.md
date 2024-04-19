# jump_linux
A shell script utility that lets you type the name of a directory and jump 
directly to it without executing the "cd ../" command repeatedly.

## How to use jump.sh:
1. Copy the code and save it as "__jump.sh__"
2. Before you can execute the script you need to make it executable by typing the following:

```no-highlight  
$ chmod +x path/to/our/file/jumps.sh  
``` 

3. To make this available on every terminal session, we have to put this in the “__.bashrc__” file.

“__.bashrc__” is a shell script that Bash shell runs whenever it is started interactively. The purpose of a .bashrc file is to provide a place where you can set up variables, functions, and aliases, define our prompt, and define other settings that we want to use whenever we open a new terminal window.

Now inside the terminal type the following command:  

```  
$ echo "source ~/path/to/our/file/jump.sh">> ~/.bashrc  
```  

4. Open the terminal and try the new "jump" functionality by typing the following command:

``` 
$ jump dir_name  
```  
[geeksforgeeks - Introduction to Linux Shell and Shell Scripting](https://www.geeksforgeeks.org/introduction-linux-shell-shell-scripting/?ref=shm)  
