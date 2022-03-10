### Exercise 1:

- Create a file called z that returns "Z", followed by a new line, whenever the command
cat is used on it.

example:

```
?>cat z
Z
?>
```

### Exercise 2:

- Create a file called foo in your current directory.
- Figure out a way for the output to look like this (except for the “total 1” line):
- Don’t worry about what you’ve got instead of "XX".

```
%> ls -l
total 1
-r--r-xr-x 1 XX XX 40 Jun 1 23:42 foo
%>
```

### Exercise 3:

- Create the following files and directories. Do what’s necessary so that when you
use the ls -l command in your directory, the output will looks like this :
- Don’t worry about what you’ve got instead of "XX".

```
%> ls -l
total XX
drwx--xr-x 2 XX XX XX Jun 1 20:47 test0
-rwx--xr-- 1 XX XX 4 Jun 1 21:46 test1
dr-x---r-- 2 XX XX XX Jun 1 22:45 test2
-r-----r-- 2 XX XX 1 Jun 1 23:44 test3
-rw-r----x 1 XX XX 2 Jun 1 23:43 test4
-r-----r-- 2 XX XX 1 Jun 1 23:44 test5
lrwxr-xr-x 1 XX XX 5 Jun 1 22:20 test6 -> test0
%>
```

### Exercise 4:

- Write a command line that will list all files and directories in your
current directory, separated by a comma, by order of creation date. Make sure
directories’ names are followed by a slash character

### Exercise 5:

- Write a command line that searches for all file names that end with ".sh" (without
quotation marks) in the current directory and all its sub-directories. It should
display only the file names without the .sh.

Example of the output:

```
$>"the command" | cat -e
find_sh$
file1$
file2$
file3$
$>
```

 ### Exercise 5:
 
 - Write a command line that counts and displays the number of regular files and
directories in the current directory and all its sub-directories. It should include ".",
the starting directory.

Example of the output:

```
$>"the command" | cat -e
42$
$>
```