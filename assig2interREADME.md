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
<br>
<br>
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

8.Use the grep command to find all JavaScript files located inside your study.html file by searching
for “ \.js “. Save the result to a new file, javascripts.html .
<h6>command used:</h6>
<br>$ grep \.js study.html > javascript.html
<br>$ cat javascript.html
<br>hirva.js
<br>jayinee.js
<br>ggg.js

9.Let’s find out the total number of words inside of the text files ( .txt ) that you created. Use
the cat command to list all of the contents of the text files inside of your commandlinepractice
folder; then pipe ( | ) the output of the cat command to the word count program ( wc ).
<h6>command used:</h6>
<br>$ cat *.txt |wc -w *.txt
<br>78 filesize.txt
<br>69 filesizes.txt
<br>0 textfile1.txt
<br>0 textfile2.txt
<br>147 total


10.Your workspace has undergone many changes since your last backup. Create another backup file
using tar and the directions in exercise 3; name your backup backup2.tar . Let’s clear out the
workspace. find all Markdown files, html files, and text files, and remove them by passing the -
delete flag to your find command. Be careful to not delete your backups folder.
<h6>command used</h6>
<br>$ tar -czf backup2.tar commandline-practice
<br>$ mv backup2.tar backups
<br>$ find ./*md ./*txt ./*html -delete
<br>$ ls
<br>orientation Pages 1 to 5.pdf  study.js
