# Basic Gnu/Linux Commands👍️

<img title="" src="/home/leapfrog/Documents/Github/Very Basic commands/assets/bash bash.png" alt="bash logo" width="369">

Hello Guys👋️👋️, today I've made a  very simple tutorial talking about some of the very fundamental Linux commands that will help beginners who are jumping ship🦘️🦘️.

In this tutorial we are going to talk about bash, a bourne-again shell that comes pre-installed on many Linux distro and if by chance your system does not have bash shell and want to follow along with this tutorial, you can download it using 

`sudo apt install bash` for debian systems.



- Listing files

To begin with we will start with `ls command`

It's a command that is used for listing files and directories on your system. To run the command type ls on your terminal and it will output the files and directories, like shown in the screenshot below.

![ls command.png](/home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/terminal_images/ls%20command.png)

`ls command` has arguments that you can use in order to manipulate the output, for example you can use -l argument for long listing or you can use -a for listing all the files even the hidden ones, like in the screenshot below.

![ls command-.png](/home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/ls%20command-.png)

When using **Linux** its all about your imagination and how far you can go, so don't be afraid to experiment some thing but make sure you're not root. A regular user command line prompt has a dollar sign `$` while a root user is a pound sign `#`.

But if you want a command that can display the username, use `whoami` command like in the screenshot below.

![whoami-regular.png](/home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/whoami-regular.png)

and when your root;

![whoami-root.png](/home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/terminal_images/whoami-root.png)

- Changing Directories

To change directory, you will use `cd` command.

![changing directory.png](/home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/changing%20directory.png)

Like example above we have moved from Document folder to Github folder which is inside the Document folder still, but your not limited to move inside a folder.

To move back to where you were, use `cd ..` command,

![cd back.png](/home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/cd%20back.png)

A short for going back again is `cd -`,

![cd shortcut.png](/home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/cd%20shortcut.png)

To move to a different folder outside the folder you are, use `cd ~/name-of-Directory`, 

![cd caret.png](/home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/cd%20caret.png)

You will start with `cd `, then a tilde symbol ~, then forward slash(/), the name of the folder. The hotkey for typing tilde symbol is hit` SHIFT `then `` `on the keyboard,



<img src="file:///home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/terminal_images/keyboard.png" title="" alt="keyboard.png" width="505">



- Creating files.

The command for creating files on Linux system is `touch` command. You can create as many files at a go,you just have to separate then by leaving a space in between files, for example let us create files called file1 and file2.

![touch files.png](/home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/touch%20files.png)

We can list our files using `ls` command;

![files.png](/home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/terminal_images/files.png)

`Touch` command can also be used to change files time stamp, let us change the time stamp of file1;

![time stamps.png](/home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/terminal_images/time%20stamps.png)

You can see the time stamp of file1 has changed.



- Copying Files.

To copy file, the command to use is `cp`,  the `cp` command has two arguments a source file and a destination file.

The command convention is `cp [source_file] [destination_file]`.

First let us insert data in file1 so we can see the power of `cp `command;

![file size.png](/home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/terminal_images/file%20size.png)

Using` ls -l` command we can see that file1 and file2 are empty, so lets add something in file1. Now file1 has data in it.

![file1 data.png](/home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/file1%20data.png)

So we can use the` cp` command to move our data from file1 to file2, the command is

`cp file1 file2.`

![file2.png](/home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/terminal_images/file2.png)

To display what is inside the files, we are going to use `cat` command, cat command spits out output on the terminal, let us use it so you can see;

![cat command.png](/home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/cat%20command.png)

- Moving files.

To move files we use `mv command`. The convention is the same for `cp command`, it is `mv [source...] [destination...]`.

![mv.png](/home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/terminal_images/mv.png)



- Creating Folder/Directory.

The command for creating directory on Linux is `mkdir command` , the convention for creating a folder is `mkdir name-of-the-folder`;

![creating files.png](/home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/terminal_images/creating%20files.png)



- Deleting a folder/Directory.

To delete an empty directory, we use `rmdir `command;

![deleting folders.png](/home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/deleting%20folders.png)

Another way to delete is to use `rm command `with  a `-r` argument, the` -r `argument is for recursive.

![recursive rm.png](/home/leapfrog/Documents/Github/Very%20Basic%20commands/assets/recursive%20rm.png)

To shortlist the commands we have learnt today are:

1. `ls command`.

2. `cd command`.

3. `touch command`.

4. `cp command`.

5. `mv command`. 

6. `mkdir command`.

7. `rmdir command`.

8. `rm -r command`.



---



My name is Godfrey 🧍️and this has been fun. To follow us 

     https://twitter.com/GodfreyAtima  



    https://www.youtube.com/c/LtipsInit 




