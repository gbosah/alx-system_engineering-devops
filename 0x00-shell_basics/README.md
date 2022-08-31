pwd - printing current directory

ls - listing directory contents

cd - change directory

ls -l - list directory content in long form

ls -la - list directory contents in long form, including hidden files

ls -na - list directory in long form and numerically

mkdir - creating directory

mv - moving file and directory

rm - deleting files

rmdir deleting directory

cd -  - changing diretory to previous directory

ls -al . .. /boot lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

file - prints the type of file

ln -s - create a symbolic link

cp -u* .html - copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

 mv [[:upper:]]* - Move all files that begin with a capital letter

rm *~  - deletes all files in the current directory that end with a ~

mkdir -p  - creating a directory with sub-directories an files

ls- map  - lists all the files and directories of the current directory, separated by commas (,).

0 string SCHOOL School data
!:mime School
                - Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
And compile with  file -C -m school
