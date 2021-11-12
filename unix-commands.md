# List of commands

* whoami
* date
* pwd (present working directory)
* ls (show content of folder you are in)
* cd Desktop (change directory to the desktop)
* pwd (confirm desktop is directory)
* ls (show stuff on desktop)
* mkdir 2021-11-11-ubimotif (make a folder on the desktop)
* ls (show your new folder you made)
* cd 2021-11-11-ubimotif (to move to this directory)
* cd - (moves you back to Desktop)
* cd - (two times, moves you back to your old folder, a way to jump between two folders)
* cd .. (moves you back a folder)
* ls -F (shows folder files via / symbol)
* ls -a (shows hidden files)
* man ls (opens ls manual; can also google online if it is unclear)
* ls
* cd Desktop/shell-lesson-data (go to the shell lesson data directory)
* if you are ALREADY in the Desktop, then type cd shell-lesson-data
* ls (check whats in there)
* ls -a
* ls -F
* less notes.txt (we want to look at this file)
* Q (quit the file)
* less numbers.txt
* less (command to read a file, but not using all your memory to open the entire thing)
* pwd (/Users/msharan/Desktop/shell-lesson-data -- this an absolute path)
* ls -tlr (all items on desktop, sorted by time, with long name, in reverse order)
* pwd
* mkdir (make a folder)
* mkdir 'notes and stuff' (quotations enable use of spaces)
* cd ../.. (go back up two levels up)
* ls / (list all folders)
* ls /Users/fredastaire/Desktop/shell-lesson-data (list all items in that folder)
* ls -art (all files, in reverse, according to time)
* nano blabla.txt (command to create a file i.e. blabla.txt)
* ctrl + O (to save the file)
* ctrl + X (to exit file)
* mv blabla.txt DONTOPEN.txt (function one of mv -- to rename something)
* mv DONTOPEN.txt ../trash (function two of mv -- move something to the trash folder above)
* cp (copy command ONLY FOR FILES)
* rm (remove command)
* always ls to check whats in there
* touch EMPTY.txt (to create an empty file)
* cp -r trash (copy command FOR FOLDERS)
* rm -ir trash/
* mv data 2021-11-11-ubimotif

## Unix commands that we planned to teach

1. pwd
2. whoami
3. date
4. ls
5. ls -F
6. pwd
7. root directory
1. Meaning of /, @
1. cd
1. ls
1. cd Desktop
1. clear
1. ls -F
1. ls --help (windows)
1. man ls (mac/linux)
1. unsupported flags (lf)
1. ls -r
1. ls shell-lesson-data
1. mkdir 2021-11-11-ubimotif
1. cd 2021-11-11-ubimotif
1. ls
1. cd ..
1. pwd
1. ls -F -a
1. cd -
1. cd ~
1. absolute vs relative path: ., .., ~
1. ls ~/Desktop/shell-lesson-data
1. prompt $ + command (ls) + option (-F) + argument/filepath (.)
1. cd Desktop
1. mv shell-lesson-data 2021-11-11-ubimotif
1. mv data 2021-11-11-ubimotif
1. ls 2021-11-11-ubimotif
1. cd 2021-11-11-ubimotif/shell-lesson-data
1. cd creature
1. Tab completion
1. mkdir thesis
1. mkdir thesis/input thesis/output
1. naming convention
1. Creating a text file: touch, less, nano, less, upper Tab
1. cp notes.txt thesis
1. ls
1. cp vs mv
1. less numbers.txt
1. cp numbers.txt thesis/input/numbers-data1.txt
1. less thesis/input/numbers-data1.txt
1. mv thesis/input/numbers-data1.txt thesis/input/numbers-data.txt
1. cp vs mv
1. rm thesis/input/numbers-data.txt
1. rm -i thesis/input/numbers-data.txt
1. cp data/amino-acids.txt data/planets.txt thesis/input
1. cp data/pdb/* thesis/input
1. cp -r data/* thesis/input
1. cd thesis/input
1. ls *.pdb
1. ls *ane.pdb
1. less cubane.pdb
1. wc cubane.pdb (lines, words, and characters)
1. wc *.pdb
1. wc *.pdb > file_lengths.txt
1. less file_lengths.txt
1. cat file_lengths.txt
1. sort numbers.txt
1. sort -n numbers.txt
1. sort -n file_lengths.txt
1. sort -n file_lengths.txt > sorted_file_lengths.txt
1. head -n 1 sorted_file_lengths.txt
1. head -n 5 sorted_file_lengths.txt
1. head -n 5 sorted_file_lengths.txt > saving_output.txt
1. less saving_output.txt
1. head -n 1 sorted_file_lengths.txt > saving_output.txt
1. less saving_output.txt
1. head -n 5 sorted_file_lengths.txt >> saving_output.txt
1. less saving_output.txt
1. echo "appending more lines"  >> saving_output.txt
1. less saving_output.txt
1. head -n 5 sorted_file_lengths.txt | sort -r | head -n 1
1. head -n 5 sorted_file_lengths.txt | tail -n 1
1. cat animals.txt
1. cut -d , -f1 animals.txt
1. cut -d , -f2 animals.txt | sort
1. cut -d , -f2 animals.txt | sort > sorted-animals.txt
