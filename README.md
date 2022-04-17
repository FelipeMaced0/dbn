# dbn
dbn means Directory By Number. This utility is meant to be used as a shortcut when dealing with files with big names, allowing the user to select the desired file and pipe it to commands.

# Usage
On terminal typing [dbn] and [dbn -h] will print the help menu.
[dbn -s] prints directories acompanied by its index.

[dbn -f -l] -> Lists only regular files: Not directories or Symlinks
[dbn -d -l] -> Lists only directories
[dbn -l] 	-> Lists everything inside the direcory besides . and ..
[dbn -f -c 4] -> Copy the name of the file at position 0
[dbn -d -c 2] -> Same as before but with directory's name
[dbn -d -g 5] -> Changes the working directory to the one at position 5    

