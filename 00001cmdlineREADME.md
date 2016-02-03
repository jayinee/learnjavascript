
<h2> Command line arguments for developers</h2>

##Project Assignment
#Project Assignment 1: Beginner
1. Write the command that will allow you to navigate to two directories above your current directory. Study
these examples:
<br>
Current directory or path:
<br>
Ryan@RyansLaptop ~/Coursework/Fall 2015/BIOL13/
<br>
The directory or path that is two directorie above the “current” one shown above:
<br>
Ryan@RyansLaptop ~/Coursework/
<br>
<h6>command used:</h6>
$ cd /..

2. Write the command and flag that will list the files and directories inside of your current directory.
<br>
<h6>command used:</h6>
$ ls
<br>
output:
<br>
about-me     clean_code_examples/  dog_photos/       family_photos/  flag   list_of_best_cat_pictures.html  profile.md  resume.md     

3. Write the command and flag that will list all of the files and directories in your current directory in longformat.
<br>
<h6>command used:</h6>
$ ls -l
<br>
output:
<br>
total 2 ----(showing only noumber of files and not directories)
<br>
-rw-r--r-- 1 desja01 1049089   0 Feb  3 12:26 about-me
<br>
-rw-r--r-- 1 desja01 1049089  17 Feb  3 12:26 about-me.md
<br>
drwxr-xr-x 1 desja01 1049089   0 Feb  2 10:56 clean_code_examples/
<br>
drwxr-xr-x 1 desja01 1049089   0 Feb  2 10:58 cooking_recepies/
<br>
drwxr-xr-x 1 desja01 1049089   0 Feb  2 10:58 dog_photos/

4. Write the command and flag that will list all of the files and directories in your current
directory, including hidden files.
<br>
<h6>command used:</h6>
$ ls -a
<br>
output:
<br>
./  ../  fie1.txt  mydirectory2/

5. Write the command that will create a folder in your current working directory and name
it clean_code_examples .
<br>
<h6>command used:</h6>
$ mkdir clean_code_examples
<br>
output:
<br>
$ ls
<br>
clean_code_examples  mydirectory2

6. Write the command to create a new file. Give the file a name and use the .txt extension.
<br>
<h6>command used:</h6>
$ touch file1.txt
<br>
output:
<br>
$ ls
<br>
clean_code_examples  cooking_recepies  dog_photos  family_photos  file1.txt  mydirectory2

7. Write the command that will output the contents of the file socks to buy.txt , located in your current
working directory, to the terminal.Assume that either socks to buy.txt already exists, or create it yourself.
<br>
<h6>command used:</h6>
$ cat socks_to_buy.txt
<br>
output:
<br>
i should wait to buy socks until next Fall.
