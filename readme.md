#Basics
Getting started with github and git

#Create a new repository
create a readme.md(dummy) file as this or some example.txt

#Install Git in your system
In order to clone a repository you need git in your system. Git will install gitbash where you can execute cmd commands

#Cloning a git repository into local system
You can clone repositories with https or ssh protocols into your local system
I cloned repository using ssh protocol

#Cloning with SSH Protocol and adding SSH Key in Github
In gitbash or any code editors switch to a folder you want to clone your repository
Create a SSH Key Pair using following commands and copy the ssh key:
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"[Just press enter when asked for additional details]
ls ~/.ssh
cat ~/.ssh/id_rsa.pub
In github setting section which mention SSH and GPG keys copy add a new ssh key with the one you generated

#Commit changes to repository
Once done just execute git clone [REPOSITORY SSH LINK GOES HERE] to have a clone in your system
Now you can make modifications locally and commit file changes in the github

