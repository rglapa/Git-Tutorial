# Git-Tutorial

## How to install git on Mac

Open up Terminal

Type "git" into command prompt

Press "Install" if git is not installed

Follow these terminal commands:

git config --global user.name "Your Name"

git config --global user.email "Your Github Email"

Git is now installed!

## How to install git on PC

Go to http://git-scm.com/download/win

Download will start

Usual install sequence for Windows

Then open up a Command Prompt

Type git to see if installed

Git is now configured and installed!

## Connect to Github

Create an account on Github.com

Create a repository on the website

Then follow these Terminal commands to create a repository on your computer:

echo "# Name" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/your_username/Name_of_online_repository.git

If in a different repository, use the set-origin command

git push -u origin master
