
# Cheat sheet compilation of some useful terminal commands

## touch newfile
creates new file
## rm newfile
deletes the file
## rm -i
remove interactive. will prompt you to confirm each file
## rm -f
force removes file. this will delete it even if write-protected
## mkdir newfolder
creates new folder
## rmdir newfolder
removes the folder, only works on empty directories
## rm -r
recursively removes the directory and all contents


## cp somefile newfile
copies file, takes two parameters 
## mv somefile ../somefile 
moves file to the directory above. takes two parameters; old location and new location
## mv somefile newfile 
can change name of the file like this


## cat somefile
views file and prints contents to console

## cat > somefile
creates file and allows to write its content from terminal

## cat somefile otherfile > combined
combines both files into a new one

## less somefile
will allow you to see contents in cmd and scroll

## head -3 somefile
displays X amount of lines from top of document in CMD

## tail -3 somefile
displays X amount of lines from bottom document

## tail -f log.txt 
displays what's happening with doc

## tail -f /private/var/log/system.log
peek at what computer is doing

## man ls 
manual of what the 'ls' command does



## streams #
Pipes || allow you to redirect streams

## cat somefile | less
"less" will take the input of cat somefile

## cat somefile > newfile
will create a new file and type the output of "somefile"

## ls *.txt 

will list all files that end with a ".txt"



## find . -name "*.txt" -print 

will print to terminal all files with names ending in ".txt" starting from current directory

## find . -name *.mp3 -print > myMusic.txt

will create a new file (myMusic.txt) with all the files ending in "mp3"

## grep binary *.txt

prints to terminal all files that have the word "binary" in the content, that end in ".txt"
takes two parameters, what to look for and where to look for

## find ~ -name "*.txt" -print | grep README

finds all files in the home directory with name ending in ".txt", finds those that contain "README" and prints them to the terminal






