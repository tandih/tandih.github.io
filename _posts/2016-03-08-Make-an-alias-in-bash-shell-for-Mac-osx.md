---
layout: post
title: Make an alias in bash shell for Mac osx
author: Tan
---
So simple, when using mac-osx and Linux we have alot of powerful command line. But sometimes it is too long and difficult to remember. So.. Would you like to create an alias in the bash shell for MacOsx? 


Ok, let's go

## How to make a alias ? 
-----
Launch Terminal from the /Application/Utilities folder or type Command and search Terminal and type the below command:
That will redirect to home 

- cd ~ 
- ls -a -l 

Create the .bash_profile(If it is not exit) file using the command line program called ‘vi’ or any text editor if it doesn’t exist:

- echo '' > .bash_profile

And type the content in profile, example we need to alias ls -lah by ll

 - alias ll='ls -lah'

save the .bash_profile and exit the text editor
Refresh the bash shell environment by command:

- source ~/.bash_profile

That’s it, now the alias will take effect we can enjoin the new command so easily and quickly

To add other aliases just start a new line,  and apply the same formatting.
