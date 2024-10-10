# COMPREHENDING COMMANDS
## cat, not the pet but the command!
### description
In this challenge, we're tasked with directly reading a file using the `cat` command. We found the file named "flag" by executing `ls`. Therefore, we use `cat flag` to retrieve and display the flag stored in that file.

###Approach 
i listed the files in the directory using the ls command, which gave me the file where flag is located, i then used 'cat' command to achieve the flag

flag: pwn.college{QmSh47TgxxrmrGQt5YnUzU_F9y6.dFzN1QDLzczN0czW}

## catting absolute path
### description
Since we're required to use an absolute path to reference the flag file, we need to use cat /flag. Previously, we used a relative path, which means we were looking for the file in the current directory. By using the absolute path, we're searching for the "flag" file starting from the root directory, indicated by the /.

### approach
referenced the flag using its absolute path 

## more catting practice
