[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [Session Notes](../sessions/README.md) 

# Session 7

## Topics covered
⇛ History of Linux

⇛ Kernel and user code

⇛ Package management

⇛ Basic commands

⇛ Installing Apache2 web server



## Personal Notes and research following this session
[A page overview of the history of Linux](https://linuxsimply.com/linux-basics/introduction/history-of-linux/)

Linux was created by Linus Torvalds in 1991 

Linux is an  free open-sourced software meaning its free to anyone and allows other developers to modify it to their preferences 

The very first linux distribution was released in 1992 following its licensing under the GNU GPL

in the present day Linux now has more than 600 distributions 

Linux distributions are operating systems that use the Linux kernal for their kernal functions 

Today around 85% of smartphones are running Linux 

[Linux is a combination of two software - Linux kernal and GNU software](https://dev.to/selma_caliskan/gnu-and-linux-joined-forces-57l)


[Orgin story of Linux and its widespread adoption thoughtout the years across different industries](https://thelinuxcode.com/history-of-linux/)

[A cheatsheet on Linux commands](https://www.geeksforgeeks.org/linux-unix/linux-commands-cheat-sheet/)

[Another clear cheat sheet for bash commands](https://www.fosslinux.com/132925/50-bash-commands-cheat-sheet.htm) 




## Exercises and results
We installed Apache2 onto a Raspberry Pi using the Command "sudo apt install apache2".

when we ran the Apache server we used the commands to initiate the services in the background

- sudo systemctl start apache2.service ## starts the web server

- sudo systemctl stop apache2.service  ## stop the web server

- sudo systemctl enable apache2.service # makes the web server start every time the pi is booted

- sudo systemctl disable apache2.service # prevents the web server starting automatically on reboot

to ensure the services are still running we used 
- sudo systemctl status apache2.service
which gave us an output allowing us to see what services are still running


## Summary of learning
- We learnt about package management and how essential it is to an OS 

- We learnt how to install Apache2 webserver which carries out package management within an OS

- we learnt some basic Shell commands "pwd" for example which shows the current directory

- We learnt about the boot system structure of a computer which i found reaaly interesting - learning about the role of the BIOS and such 
