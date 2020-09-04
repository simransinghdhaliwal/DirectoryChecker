# DirectoryChecker

The primary goal of this program is to ensure that file names are properly named. The program can either 
test the current directory, or a target directory.

Ex. `./poornames` or `./poornames Desktop`

Additionally, the program has the ability to recursively check each directory from the target directory to the root
through using the "-r" option. 

Ex. `./poornames -r` or `./poornames -r target`

## Error Codes
0 ~ The program ran successfully

2 ~ Invalid amount of operands, directories cannot start with "-", targett directory is a symbolic link, invalid persmissions
