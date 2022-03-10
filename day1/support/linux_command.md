# Quick start for linux commands

## File Commands:
 - ls – directory listing
 - ls -al – formatted listing with hidden files
 - cd dir - change directory to dir
 - cd – change to home
 - pwd – show current directory
 - mkdir dir – create a directory dir
 - rm file – delete file
 - rm -r dir – delete directory dir
 - rm -f file – force remove file
 - rm -rf dir – force remove directory dir *
 - cp file1 file2 – copy file1 to file2
 - cp -r dir1 dir2 – copy dir1 to dir2; create dir2 if it doesn't exist
 - mv file1 file2 – rename or move file1 to file2 if file2 is an existing directory, moves file1 into directory file2
 - ln -s file link – create symbolic link link to file
 - touch file – create or update file
 - cat > file – places standard input into file
 - more file – output the contents of file
 - head file – output the first 10 lines of file
 - tail file – output the last 10 lines of file
 - tail -f file – output the contents of file as it grows, starting with the last 10 lines 

## Searching:
 - grep pattern files – search for pattern in files
 - grep -r pattern dir – search recursively for pattern in dir
 - command | grep pattern – search for pattern in the output of command
 - locate file – find all instances of file
 
## System Info:
 - date – show the current date and time
 - cal – show this month's calendar
 - uptime – show current uptime
 - w – display who is online
 - whoami – who you are logged in as
 - finger user – display information about user
 - uname -a – show kernel information
 - cat /proc/cpuinfo – cpu information
 - cat /proc/meminfo – memory information
 - man command – show the manual for command
 - df – show disk usage
 - du – show directory space usage
 - free – show memory and swap usage
 - whereis app – show possible locations of app
 - which app – show which app will be run by default

## Shortcuts:
 - Ctrl+C – halts the current command
 - Ctrl+Z – stops the current command, resume with
 - Ctrl+D – log out of current session, similar to exit
 - Ctrl+W – erases one word in the current line
 - Ctrl+U – erases the whole line
 - Ctrl+R – type to bring up a recent command
 - !! - repeats the last command
 - exit – log out of current session
