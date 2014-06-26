ls				list files in current directory
ls -a	 		list all hidden files as well
ls file path 	list of all files in given path...complete path must be given	
ls ~/folder name	list all the files inside this folder.. ~ provides path from start to that folder own it's own
cd 				get back to home directory
cd .			current directory
cd .. 			parent directory
pwd				print working directory
cp file1 file2  copies the file1 from it's path to current directory with name file2
cp file1 . 		this copies file1 in current working directory with same name
mv file1 file2	this moves file1 from i's location to file2 the new location. it is not coping...only 1 copy is left
rm file1 		removes the file1
rmdir  diretory	removes the directory
clear			clears the screen
cat file1 		displays the contents of the file on the screen
less file1		same function as that as of cat...but prints once page at a time
grep keyword file1 		searches for the keyword or phrase in the file
grep -i keyword file1 	searches for the keyword or phrase in the file without considering cases
grep 'keywords here' file1 searches for keywords.. this allows searcing multiple words in single quotes
wc -l file1		number of lines in the given file
wc file1		number of words in given file
command > file 	redirect standard output to a file
command >> file append standard output to a file
command < file 	redirect standard input from a file
command1 | command2 	pipe the output of command1 to the input of command2
cat file1 file2 > file0 concatenate file1 and file2 to file0
sort 			sort data
who 			list users currently logged in
*				matches one or more charaters in a file
?				matches one charaters
ls list*		list all which start with list
ls ?list		list all with any first charater  bt end in list