
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


#Project Assignment 2:Intermediate

1.Use only the command line to create 5 files (one at a time) and add full sentences to each, as illustrated below:
<br>Create the file myname.md and write your name in it.
<br>Create the file myfavoritefoods.md and write your three favorite foods.
<br>Create the file dreamproject.md and write about a project that you would like to build after Modern
Developer.
<br>Create the file music.md and write the genre of music, song, or artist, that you feel most comfortable
listening to.
<br>Create the file colors.md and write your favorite color, or colors.

<h6>command used:</h6>
<br>$ mkdir commandline-practice
<br>$ cd commandline-practice
<br>$ touch myname.md
<br>$ vi myname.md
<br>$ touch myfavoritefoods.md
<br>$ vi myfavoritefoods.md
<br>$ touch dreamproject.md
<br>$ vi dreamproject.md
<br>$ touch music.md
<br>$ vi music.md
<br>$ touch colors.md
<br>$ vi colors.md
<br>$ ls
<br>colors.md  dreamproject.md  music.md  myfavoritefoods.md  myname.md

2.Find out which of the files that you wrote in the previous step had the largest file size.
Write the command and the correct flags to list the files and their file size in human readable and long format. Then add the
output to this file: filesizes.txt.

<h6>command used:</h6>
$ ls -lSh > filesize.txt
<br>l- long listing
<br>S-sorting
<br>h-human readable format
<br>$ cat filesize.txt
<br>total 8.4M
<br>-rw-r--r-- 1 desja01 1049089 8.4M Dec  8 14:36 orientation Pages 1 to 5.pdf
<br>-rw-r--r-- 1 desja01 1049089  468 Feb  4 10:51 filesizes.txt
<br>-rw-r--r-- 1 desja01 1049089   32 Feb  4 10:26 myfavoritefoods.md
<br>-rw-r--r-- 1 desja01 1049089   27 Feb  4 10:27 dreamproject.md
<br>-rw-r--r-- 1 desja01 1049089   20 Feb  4 10:29 music.md
<br>-rw-r--r-- 1 desja01 1049089    8 Feb  4 10:25 myname.md
<br>-rw-r--r-- 1 desja01 1049089    5 Feb  4 10:30 colors.md
<br>-rw-r--r-- 1 desja01 1049089    0 Feb  4 11:08 filesize.txt

3.Let’s create a backups folder and backup the files we’ve written so far. Create a new directory and
name it backups . Use the tar command to archive the contents of your commandlinepractice
folder. Name your archived file backup1.tar , and save it inside your backups folder.

<h6>command used:</h6>
$ mkdir backups
<br>$ cd ..
<br>$ tar -czf backup1.tar commandline-practice
<br>$ mv backup1.tar backups

4.Create a file sites.txt and add to it a list of your favorite websites, each on its own line.
<br>You’ll need to type the newline character ( \n ), and the echo flag that enables interpretation of backslash
escapes.
<h6>command used:</h6>
$ echo -e "google\nyahoo\nmicrosoft" > sites.txt
<br>$ cat sites.txt
<br>google
<br>yahoo
<br>microsoft

5.Use curl to get the contents of study.moderndeveloper.com and store the contents inside a file,
study.html. <br>When you request the file, it will retrieve the web page of the first web server that
responds, which, in this case, is a server that indicates when the web page has been relocated. <br>This
routine occurrence is called aredirection. <br> You will learn more about server redirects in an upcoming
course. Use the -L flag to follow the redirection and receive the correct page.

<h6>command used:</h6>
<br>$ curl study.moderndeveloper.com > study.html
<br>$ cat study.html
<br><!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
<br><html><head>
<br><title>301 Moved Permanently</title>
<br></head><body>
<br><h1>Moved Permanently</h1>
<br><p>The document has moved <a href="https://study.moderndeveloper.com/">here</a>.</p>
<br><hr>
<br><address>Apache/2.2.31 (Unix) mod_ssl/2.2.31 OpenSSL/1.0.1e-fips mod_bwlimited/1.4 Server at study.moderndeveloper.com Port 80</address>
<br></body></html>
<br>using -L:
<br>$ curl -L study.moderndeveloper.com ----this gives huge output ,a whole structure of the page
<br>using -l:
<br>$ curl -l study.moderndeveloper.com
<br>% Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
  <br>                               Dload  Upload   Total   Spent    Left  Speed
<br>100   384  100   384    0     0    664      0 --:--:-- --:--:-- --:--:--   664<!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
<br><html><head>
<br><title>301 Moved Permanently</title>
<br></head><body>
<br><h1>Moved Permanently</h1>
<br><p>The document has moved <a href="https://study.moderndeveloper.com/">here</a>.</p>
<br><hr>
<br><address>Apache/2.2.31 (Unix) mod_ssl/2.2.31 OpenSSL/1.0.1e-fips mod_bwlimited/1.4 Server at study.moderndeveloper.com Port 80</address>
<br></body></html>

6.Use the mv command and Command Escaping to rename your backup archive.Navigate to the backups directory and rename your backup1.tar archive to output of the date command.
<br>That is, whatever the output (the text) of the date command is, use that text as the new name for your backup1.tar file.

<h6>command used:</h6>

7.Use the wc command and the correct flag to determine how many words you wrote inside
your dreamproject.md file. If the file contains fewer than 20 words, append another two sentences
to the file.<br>Use those two sentences to describe your dream project.

<h6>command used:</h6>

<br>$ wc -w dreamproject.md
<br>5 dreamproject.md

<br>$ echo hello this is sentence 1.and this is sentence 2. >> dreamproject.md
<br>$ wc -w dreamproject.md
<br>14 dreamproject.md


8. Use the grep command to find all JavaScript files located inside your study.html file by searching
for “ \.js “. Save the result to a new file, javascripts.html .

$ grep \.js study.html > javascript.html
$ cat javascript.html
hirva.js
jayinee.js
ggg.js

9. Let’s find out the total number of words inside of the text files ( .txt ) that you created. Use
the cat command to list all of the contents of the text files inside of your commandlinepractice
folder; then pipe ( | ) the output of the cat command to the word count program ( wc ).

$ cat *.txt |wc -w *.txt
78 filesize.txt
69 filesizes.txt
0 textfile1.txt
0 textfile2.txt
147 total
