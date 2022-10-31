# Introduction
dbn means Directory By Number. This utility is meant to be used as a shortcut when dealing with files with big names, allowing the user to select the desired file.

## Usage

|  Code        |                Stands For                               |
| ------------ | ------------------------------------------------------- |
| `dbn -h`     |  Print the help menu and                                |
| `dbn -f -l`  |  Lists only regular files: Not directories or Symlinks  |
| `dbn -d -l`  |  Lists only directories                                 |
| `dbn -l` 	   |  Lists everything inside the direcory besides . and ..  |
| `dbn -f -c 4`|  Copy the name of the file at position 4                |
| `dbn -d -c 2`|  Same as before but with directory's name               | 
| `dbn -d -g 5`|  Changes the working directory to the one at position 5 |

## Copy
 For copying to work, it is necessary to the have xclip installed on the machine. If you doesn't have it, no problem. Just run on the terminal the following command.
 
 `sudo apt install xclip`
