---
layout: post
title: Make an alias in bash shell for Mac osx
author: Tan
---
So simple, 

When using macOsx we have many command is powerfull. But that is so long and different to remenber. So.. Would you like to create aslias in bash shell for MacOsx? 

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

That’s it, now the alias will take effec we can injoin the new command so easy and quickly

To add other aliases just start a new line,  and apply the same formatting.


