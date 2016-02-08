
<h2> Command line arguments for developers</h2>
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

8. Write the command to display your Present Working Directory.
<br>
<h6>command used:</h6>
$ pwd
<br>
output:
<br>
/c/Users/desja01/mydirectory1

9. Write the command to output the current user to the terminal. Thecurrent user is generally the account that
is logged into the operating system and currently using the terminal.
<br>
<h6>command used:</h6>
$ whoami

10. Write the command to list the files and folders of the folder two above your current directory. For example,
if you are in C:/Users/John Wayne/My Documents/Tax Forms/ , display all files and folders within the directory C:/Users/John Wayne/ .
<br>
<h6>command used:</h6>
desja01@SSIBRD10 MINGW64 ~/mydirectory1/mydirectory2/mydirectory3
<br>
$ ls -l ../..
<br>
output:
<br>
total 1
<br>
drwxr-xr-x 1 desja01 1049089  0 Feb  2 10:56 clean_code_examples
<br>
drwxr-xr-x 1 desja01 1049089  0 Feb  2 10:58 cooking_recepies
<br>
drwxr-xr-x 1 desja01 1049089  0 Feb  2 10:58 dog_photos
<br>
<h6>OR command used:</h6>
desja01@SSIBRD10 MINGW64 ~/mydirectory1/mydirectory2/mydirectory3
<br>
$ ls ../..
<br>
output:
<br>
clean_code_examples  cooking_recepies  dog_photos  family_photos  file1.txt  mydirectory2  socks_to_buy.txt

11. Write the command to create the file list of best cat pictures.html .
<br>
<h6>command used:</h6>
$touch list_of_best_cat_pictures.html

12. Write the command that will change your current directory to C:/Users/Default User/My Documents .
Note: the directory C:/Users/Default User/My Documents may not exist on your computer; if that is the
case, you’ll see the error bash: cd: C:/Users/Default User/My Documents: No such file or
directory
<br>
<h6>command used:</h6>
current directory :desja01@SSIBRD10 MINGW64 ~/mydirectory1
<br>
from this you have to go C:/Users/Default User/My Documents
<br>
$ cd C:/Users/Default User/My Documents
<br>
$ pwd
<br>
/c/Users/Default

13. Write the command that will ping the ip address 8.8.8.8.
<br>
<h6>command used:</h6>
$ ping 8.8.8.8

14.Write the command to change your current directory to the folder <HOME>/documents/ , where <HOME> is
the single character shortcut for $HOME .
<br>
<h6>command used:</h6>
$grgrfgf

15.Use the echo command to display the text “My name is ” followed by your first name. View the help
or man pages for echo to learn the command’s arguments man echo , help echo or echo --help .
<br>
<h6>command used:</h6>
$ echo My name is jayinee
<br>
$ echo "My name is jayinee"


16.Write the command that will show the output of two files, one after another: tylers favorite songs.txt and sarahs favorite songs.txt .
<br>
<h6>command used:</h6>
$ cat tylers_favorite_songs.txt           sarahs_favorite_songs.txt

17.Write the command to show the help, or manual, for the echo command, and add it to a file
called echo_options.txt
<br>
<h6>command used:</h6>
$ help echo > echo_options.txt

18.Write the command, flag, and flag option to ping 127.0.0.1 two times. A flag option is an option passed
immediately after a flag.
<br>
<h6>command used:</h6>
two answers possible:
<br>
1st)
<br>
vi flag
<br>
insert mode
<br>
write in the file:
<br>
ping 127.0.0.1
<br>
ping 127.0.0.1
<br>
save file using esc shift :wq
<br>
view file using : ./flag or sh flag
<br>
<br>
2nd)
<br>
vi flag
<br>
insert mode
<br>
write in the file:
<br>
CNT=0
<br>
    re='^-?[0-9]+$'
    <br>
        if ! [[ $1 =~ $re ]];
        <br>
            then
            <br>
              echo "error:Not a number. Give +ve number"
              <br>
                  else
                  <br>
                   if [ "$1" -lt 1 ];
                   <br>
                      then
                      <br>
                           echo "Give +ve number"
                           <br>
                            else
                            <br>
                                     while [ $CNT -lt "$1" ];
                                     <br>
                                              do
                                              <br>
                                                       ping 127.0.0.1
                                                       <br>
                                                                let CNT+=1
                                                                <br>
                                                                         done
                                                                         <br>
                                                                          fi
                                                                          <br>
                                                                              fi
                                                                              <br>
save file using esc shift :wq
view file using : ./flag 2 or sh flag 2 (any number in place of 2 will do,but it should be positive number)

19.Write a single command to display the contents of all Markdown files (that have the extension .md )
to the console.
<br>
<h6>command used:</h6>
$ cat *.md
<br>
this is about me
<br>
this is my profile.
<br>
this is my resume.

20.Write the command to remove the file yesterdays_todo_list.md from the directory you are presently working in.
<br>
<h6>command used:</h6>
$ rm yesterdays_todo_list.md



