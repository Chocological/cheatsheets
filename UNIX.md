```sh
*** some useful UNIX commands from @girishadurrel ***
-----------------------------

1) prints the current working directory

-bash-3.00$ pwd 

2) list the files in the directory

-bash-3.00$ ls

( gives you just the file names in the directory )

-bash-3.00$ ls -l 

( gives you just the file names plus more information about the files, -l option means long list ) 

3) change directory

-bash-3.00$ cd directory-name

( changes the directory to the given directory name. suppose you are in /home/g/girisha. now you want to go to p1-sample directory. you type in cd p1-sample )

-bash-3.00$ cd .. 

( goes one level up in the directory hierarchy. eg. suppose you are in /home/g/girisha/p1-sample. if you type in cd .. you will change directory to /home/g/girisha. )

4) copy files/directory

-bash-3.00$ cp file-current-path file-destination-path

( if you want to copy the file /home/g/girisha/p1-sample/sample-readLine.java to /home/g/girisha/mycode directory, you can do the following. cp /home/g/girisha/p1-sample/sample-readLine.java /home/g/girisha/mycode/ )

( you always don't have to specify the whole path as mentioned above [in other words we have given the absolute paths for the files]. you can do the following as well. suppose you are in /home/g/girisha already [ I mean your current working directory /home/g/girisha/ ]. then to do what we did above you can just say cp p1-sample/sample-readLine.java mycode/ . we have given the paths relatively to our current working directory. )

if you want to copy a directory to some place just use 

-bash-3.00$ cp -r directory-current-path directory-destination-path

( nore the -r option. -r means you are doing a recursive copy )

5) man command

( man is a very useful command. suppose you want to know more information on the cp command or the cd command. you just type in )

-bash-3.00$ man cp

( gives you all the information about the cp command and the options that can be used )

-bash-3.00$ man cd
 
( gives you all the information about the cd command and the options that can be used )

-bash-3.00$ man man

( if you feel you don't know how to use the man pages ( the man command ) you can say man man :P it will explain how to use the man command. )

( man actually means manual. for and example if you type man cp you are looking at the manual page for the cp command. )

6) more command

-bash-3.00$ more file-name

if you want to quickly see what a text file contain you can just type more file-name and it will list down the contents of the file. if the file is too large it will show only a portion of the file. by typing the enter button you can traverse the file

-----------------------------------------------------------------------------------------------------------------------------------------

there are a lot of commands that you can use. you can learn about them using the man pages or by searching online. this is just a small guide I just complied for you all to get started.

```