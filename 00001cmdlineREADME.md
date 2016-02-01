# learnjavascript
<h2> Command line arguments for developers</h2>


#Exercises 3

1. Become comfortable navigating your filesystem using only the CLI. Change directories to your filesystem’s “root”
directory ( / on Mac and C/ on Windows). Navigate back to your $HOME directory. Use the [TAB] key to autocomplete
directory names.
2. Try creating an empty directory in your $HOME directory, then delete the empty directory. Repeat this process for
an empty file..
3. List all of the files in your $HOME directory. Sort the listing of these files by file size. Try listing all of the files in your
root (/) directory using your $HOME as your present working directory, using the long format listing. Sort these files
by file size as well.
4. Change directories to a folder where you keep photos or other images. Try listing only the images of a certain file
type, such as JPEGs or PNGs. Use the wildcard character to list only the images with filenames that contain the
letter “s.”
5. Try learning about commands not covered in this section. For instance, use man pages to read about
the find command used for finding files on your computer. Use the find command to find all files with the “.jpg”
file extension on your entire hard drive.

exercise3--(2)

bash-4.3$ $home                                                                                                                                                                              
bash-4.3$ pwd                                                                                                                                                                                
/home/cg/root                                                                                                                                                                                
bash-4.3$ mkdir mydirectory                                                                                                                                                                  
bash-4.3$ ls                                                                                                                                                                                 
README.txt  mydirectory                                                                                                                                                                      
bash-4.3$ rmdir mydirectory                                                                                                                                                                  
bash-4.3$ pwd                                                                                                                                                                                
/home/cg/root                                                                                                                                                                                
bash-4.3$ ls                                                                                                                                                                                 
README.txt                                                                                                                                                                                   
bash-4.3$ touch myfile                                                                                                                                                                       
bash-4.3$ ls                                                                                                                                                                                 
README.txt  myfile                                                                                                                                                                           
bash-4.3$ rm myfile                                                                                                                                                                          
bash-4.3$ ls                                                                                                                                                                                 
README.txt                                                                                                                                                                                   
bash-4.3$                                                                                                                                                                                    
    
exercise 3 ---(3)    
bash-4.3$ ls -s                                                                                                                                                                              
total 4                                                                                                                                                                                      
4 README.txt  0 mydirectory1       

<h6>long format listing</h6>
bash-4.3$ ls -l                                                                                                                                                                              
total 4                                                                                                                                                                                      
-rw-r--r-- 1 7949 7949 978 Jan 31 21:42 README.txt                                                                                                                                           
drwxr-xr-x 2 7949 7949   6 Jan 31 21:47 mydirectory1   

exercise3--(4)

bash-4.3$ ls *.jpg ---all files with jpg format will be listed.

bash-4.3$ ls *.s ---all files with word "s" will be listed.

exercise3--(5)

man is the interface used to view the system's reference manuals.

$man man 

