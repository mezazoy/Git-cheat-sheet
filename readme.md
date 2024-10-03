#Git cheat sheet
---
###Navigation

* pwd - show me which folder I'm in
* ls - show files and folders in current folder
* ls -a - also show files and folders whose names begin with the symbol "."
* cd first-project - go to the first-project folder
* cd first-project/html - go to the html folder, which is located in the first-project folder
* cd .. - go up one level, to the parent folder
* cd ~ - go to your home directory (/Users/Username)
* cd / - go to the root directory

###Working with files and folders

* touch index.html - create a file index.html in the current folder
* touch index.html style.css script.js - if you need to create several files at once, you can print their names on one line separated by a space
* mkdir second-project - create a folder called second-project in the current folder

###Copy and move

* cp file.txt ~/my-dir - copy the file to another location
* mv file.txt ~/my-dir - move a file or folder to another location

###Reading

* cat file.txt - print the contents of the text file file.txt

###Removal

* rm about.html - delete the about.html file
* rmdir images - delete the images folder
* rm -r second-project - delete the second-project folder and everything it contains

###Useful features

* The commands do not have to be printed and executed one by one. You can specify them as a list - separated by two ampersands (&&)
* The console has its own memory - a buffer with the last few commands. You can navigate through them using the up arrow keys
* To avoid typing the entire file or folder name, you can type the first characters of the name and press Tab twice. If the file or folder is in the current directory, the command line will add the path itself
---