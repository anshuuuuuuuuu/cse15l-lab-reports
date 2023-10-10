# Lab Report 1 - Remote Access and FileSystem (Week 1)

In this lab report, we will explore basic filesystem commands, including `cd`, `ls`, and `cat`.

## `cd` Command

### Example 1: Using `cd` with No Arguments
```bash
$ cd

# Working Directory: This command does not change the working directory.
# Output Explanation: When 'cd' is used without arguments, it takes you to your home directory.

$ cd /path/to/directory

# Working Directory: The working directory changes to /path/to/directory.
# Output Explanation: Using cd with a path as an argument navigates you to the specified directory.

$ cd /nonexistent/directory

# Working Directory: The working directory remains unchanged.
# Output Explanation: This results in an error because /nonexistent/directory does not exist.


$ ls

# Working Directory: This command lists files and directories in the current working directory.
# Output Explanation: The output will display the files and directories in the current directory.

$ ls /path/to/directory

# Working Directory: The working directory remains unchanged.
# Output Explanation: This command lists the contents of the specified directory.

$ ls /nonexistent/directory

# Working Directory: The working directory remains unchanged.
# Output Explanation: This results in an error because /nonexistent/directory does not exist.


$ cat

# Working Directory: This command does not change the working directory.
# Output Explanation: When cat is used without arguments, it waits for user input, and the behavior depends on user input.

$ cat /path/to/file.txt

# Working Directory: The working directory remains unchanged.
# Output Explanation: This command displays the contents of the specified file.

$ cat /nonexistent/file.txt

# Working Directory: The working directory remains unchanged.
# Output Explanation: This results in an error because /nonexistent/file.txt does not exist.

