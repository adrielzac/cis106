Commands

## Description
Description
## Syntax
Syntax
## Example:
------

# date
## Description
Displays the system date and time

## Syntax
date + option + format

## Examples
* Display the system date
* 'date'
* Display the date in GMT
* 'date -u'
* Display the date from the past
* date --date="1 year ago"


# uname
## Description
Gives various information about the system

## Syntax
uname + option

## Examples
* Display the kernel version
* 'uname -r'
* Display the kernel name
* 'uname -s'
* Display the hardware name
* 'uname -m'


# du
## Description
Displays disk usage of a certain file or directory

## Syntax
du + option + name

## Examples
* Display the space usage of a directory
* 'du ~/Documents'
* Display the usage of all files in a given directory
* 'du -a ~/Documents'
* Display the size of a directory in human readable format
* 'du -h ~/Documents'


# free
## Description
Displays information about the system's memory usage

## Syntax
free + option
zcd
## Examples
* Display the amount of free memory and swap memory
* 'free'
* Display the amount of free memory and swap memory in human readable format
* 'free -h'
* Display the amount of free memory and swap memory in bytes
* 'free -b'


# echo
## Description
Prints specified output

## Syntax
echo + option + argument

## Examples
* Print "hello"
* 'echo hello'
* Print "hello" in double quotations
* 'echo \"hello"\

# apt
## Description
Command used to manage packages and programs

## Syntax
apt + option + name (use with sudo for root privileges)

## Examples
* Install firefox 
* 'sudo apt install firefox'
* Install multiple packages at once
* 'sudo apt install package1 package2'
* Remove firefox
* sudo apt remove package

# pwd
## Description
Prints current working directory


# cd
## Description
Changes current working directory to a specific location


## Syntax
cd + option + directory

## Examples
* Navigate to Downloads using relative path
* 'cd Downloads'
* Navigate to Downloads using absolute path
* 'cd /home/name/Downloads'
* Navigate to the parent direcotry
* 'cd../'


# ls
## Description
Lists files and directories

## Syntax
ls + options + name

## Examples
* Print all files in the current directory
* 'ls'
* Print all files in the Downloads folder
* 'ls Downloads'
* Prints all files in a long list
* 'ls -l Downloads'


# tree
## Description
Similar to ls, lists files in a tree format


# man
## Description
Displays the manual of a given command


# mkdir
## Description
Creates directories

## Syntax
mkdir + option + name

## Examples
* Create a directory in the current working directory
* 'mkdir foldername'
* Create a parent directory
* 'mkdir /home/foldername'
* Create a parent directory and all missing parent directories
* 'mkdir -p /home/foldername'


# touch
## Description
Creates empty files

## Syntax
touch + option + name

## Examples
* Create a file
* 'touch filename'
* Create a file 


# rm
## Description
Removes files

## Syntax
rm + option + name

## Examples
* Remove a file
* 'rm filename'
* Remove a directory
* 'rm -d directoryname'
* Remove non empty directory
* 'rm -r directoryname'


# cp
## Description
Copies files

## Syntax
cp + option + source + destination

## Examples
* Copy a file
* 'cp file newfile'
* Copy a directory
* 'cp -r directory newdirectory'
* Copy multiple files and directories
* 'cp file.txt directory file2.txt directory2'


# mv
## Description
Moves files in between directories

## Syntax
mv + option + starting point + destination

## Examples
* Move a file 
* 'mv file Documents'
* Rename a file
* 'mv file file2'
* Move multiple files
* 'mv file1 file2 Documents'


# stat
## Description
Displays information about files

## Syntax
stat + option + name

## Examples
* Show info about a file
* 'stat file.txt'
* Show info about the file's location
* 'stat -f file.txt'


# Wildcards
## Description
Stand in representations for characters (*?[])

## Examples
* List all files that end in a .txt extension
* 'ls *.txt'
* List all files that have a character in between b and c in their name
* 'ls b?c'
* List all files that have a letter followed by a vowel
* 'ls *[aeiou]'


# Brace expansion
## Description
Allows you to use multiple strings in a command

## Examples
* Create multiple files
* 'touch file{1..5}.txt'
* Create directory structure in one command
* 'mkdir -p files/{folder1,folder2}/{subfolder1,subfolder2}'


# cat
## Description
Concatenates and/or reads files

## Syntax
cat + option + name

## Examples
* Read and display the content of a single file
* 'cat file.txt'
* Remove empty output lines
* 'cat -s file.txt'
* Concatenate a file
* 'cat file.txt file2.txt'
  

# head
## Description
Prints the first lines of a file

## Syntax
head + option + name

## Examples
* Print the first 10 lines of a file
* 'head file.txt'
* Print 4 lines starting from the top
* 'head -n 4 file.txt'
* Print multiple files
* 'head file1.txt file2.txt'


# tail
## Description
Prints the last lines of a file

## Syntax
tail + option + name

## Examples
* Pritn the last 10 lines of a file
* 'tail file.txt'
* Print 4 lines starting from the bottom
* 'tail -n 4 file.txt'
* Print multiple files from the bottom
* 'tail file1.txt file2.txt'


# cut
## Description
Used to cut text files

## Syntax
cut + option + name

## Examples
* Print the first and second field of a file
* 'cut file.txt -f 1,2'
* Print all fields besides the first and second field
* 'cut file.txt -f 1,2 --complement'
* Use _ for output delimitter
* 'cut file.txt -f 1,2 --output-delimiter='_''


# tr
## Description
Manipulates characters in various ways

## Syntax
tr + option + string1 + string2

## Examples
* Swap the characters 'fi' with 'ba'
* echo 'file' | tr 'fi' 'ba'


# paste
## Description
Conjoins lines

## Syntax
paste + option + name


# wc
## Description
Displays the amount of lines, characters, and words

## Syntax
wc + option + name

## Examples
* Display the number of lines, words, and characters in a file
* 'wc file.txt'
* Print just the number of lines
* 'wc -l file.txt'
* Print just the number of words
* 'wc -w file.txt'


# grep
## Description
Can match patterns and print them 

## Syntax
grep + option + pattern + file

## Examples
* Print all the lines that has the word car in a file
* 'grep car file.txt'
* Print all the lines that do not contain the word car in a file
* 'grep -v car file.txt'
* Print all the lines that contain the word car in a file following symbolic links in a directory recursively
* 'grep -R car /Documents'
* 
# output redirection
## Description
Allows storing of a command output to be used in other commands or to be saved in files.

## Syntax
">" - allows redirection to a file
"|" - redirects output of one command to the input of another command


# vim
## Description
Allows you to edit text in a file

## Syntax
vim + options + name

## Examples


# tar
## Description
Groups files into archives. Can extract archives as well

## Syntax
tar + option + archive name + file name

## Examples
* Create an archive of 3 files
* 'tar -cf archive.tar file1 file2 file3'
* Create a gz archive
* 'tar -czf archive.tar.gz file1 file2'
* List files inside of an archive
* 'tar -tf archive.tar'

# gz, bzip2, xz
## Description
Commands that allow you to compress files to make them smaller
