# Lab Report 1
_Jerry Ko_

## 1. Visual Studio Code
* Use this [link](https://code.visualstudio.com/) to download visual studio code.
* After installing VS code, you should get this interface.![screenshot1](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/screenshot.png?raw=true)
* Then you will be able to create new files.


## 2. Remote Connecting
* To access remote connecting, [download](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse) OpenSSH first and [find](https://sdacs.ucsd.edu/~icc/index.php) the course account username.
* To connect to the remote machine, open the terminal and type in **ssh username@ieng6.ucsd.edu**
* To successfully set up the login process, you can follow what I have done in this screenshot of terminal.
![image](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Screenshot2.png?raw=true)


## 3. Try Some Commands
* There are several commands for the terminal, in the screenshot I demonstrated how the command "ls" works. It prints out all the files in current directory. While the command "cd" is used to change directory and "cat" is to concatenate.
![screenshot3](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Screenshot4.png?raw=true)

## 4. Move Files With ___scp___
* The command __scp__ means secure copy, in the following screenshot, it shows how to copy the file into the remote terminal. And using the __ls__ command, we can see the file is already in the directory.
![screenshot4](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Screenshot5.png?raw=true)
* Also, the code below should print the information of the computer it is in. As shown, the code has different output on the two terminals.
![screenshot5](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Screenshot3.png?raw=true)

## 5. Setting SSH Key
![screenshot6](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/TaScreenshot.png?raw=true)
> Source from CSE15L [lab1](https://docs.google.com/document/d/1AO6RDoJnaWxMui-UFjEa_2bbQ4qcANpbIpPuV-awsOg/edit) write-up.
* Typing __ssh-keygen__ into the terminal and we could follow the screenshot above to complete using the key.
* Then login to the remote terminal and type in __mkdir__ __.ssh__. Then __scp__ the key for the terminal to the according directory.

## Optimizing Remote Running
* To simplify the steps for the command, we could do the following:
1. **ssh cs15lsp22zz@ieng6.ucsd.edu "ls"**
2. **cp WhereAmI.java OtherMain.java; javac OtherMain.java; java WhereAmI**
In these ways we could simplify the process and merge multiple lines into one.

