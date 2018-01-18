# Student Reference: Taking Command

1. [Motivation](#motivation)
2. [Find Your Terminal](#find)
3. [Viewing Content](#view)
4. [Moving](#move)
5. [Hidden Treasure Activity](#lab)

#### <a id = "motivation"></a> Why learn command line?
Using the command line is a way for you to directly communicate with your computer. Rather than using something like Finder on Mac, you can talk directly to your machine. Think about it like learning a new language, one that your computer is fluent in.

One way we can use the command line is to navigate through out files. In order to do this we need to be able to tell our computer **where** we want to go, and find out **what** is inside of the folder we're in.

#### <a id = "find"></a> Where is my terminal?
You'll be using what you learn here in your terminal. This is a place where you can speak directly to your computer. If you're using a mac, open your spotlight search and type in terminal.

#### <a id = "view"></a> What is inside of my folders?
Before we start moving around the folders on your computer, let's make sure we know our current location or *working directory*. The text after the "~" and before the "$" will tell you where in your computer you are. We'll use the ls command to **list** all of the files inside our current folder.
```bash
#to get a more detailed description of your working directory, or where you are try the command below.
pwd

#now let's see what's inside of the folder we're in.
ls
```
#### <a id = "move"></a> How do I move?
Movement, an essential part of navigation! But how to accomplish it? Thankfully, we have the cd command, which stands for **c**hange **d**irectory. A directory is just another word for a folder, so we use this command to change our current folder.

```bash
# To move up, or out of our current folder into it's parent folder we use...
cd ..

# To move down, or into a folder that is inside our current folder we use...
cd folder_name
```
You'll know you're moving down if the folder you want to get to is listed when you use the ls command.

***
# <a id = "lab"></a> Hidden Treasure Activity

Now that we've got the basics down, let's have some fun. This repository contains a map of computer land, a magical place full of treasure. Close out your GUI (the visual of the file tree that is most likely up on the side of your page) and get ready to explore through the command line.

#### Getting Started
Before you get started, make sure you're in the correct folder. If you run the command pwd in your terminal, the output should end in "command-line-hidden-treasure".

#### Task
You'll be moving through the folders in this repository using the command line and looking for files called "X.txt". As we all know, X marks the spot. Be sure to use the ls command to see what is inside each folder you enter. Inside each file "X.txt" will be a new command that you can use in the command line, so look carefully! Every file will have a .txt extension, so anything that doesn't end in .txt is a folder and a potential treasure filled location.

There are 5 X's total, so ready, set, and happy treasure hunting....

![](https://media.giphy.com/media/g6ZTtxTm7pYsw/giphy.gif)
