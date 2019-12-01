# Homework0
Homework 0 of ECE 231: Intermediate Programming. Assigned 1/15/2020. Due 1/22/2020, 11:59 pm.
The goal for this homework is the get acquainted with the software that you are going to be using for the rest of the semester. By the end of this assignment you will achieve two things:

    Get a Linux system working
    Create a GitHub account & have Git working on your linux system
  
  
## Getting a Linux system
There are few ways of doing this:
### Linux
If you have a Linux machine (Ubuntu, Pop!OS, Redhat, Linux Mint, etc), please take a look at setting up your Github account and getting Git working on your machine.
### All operating systems (except Linux)
You can download a virtual machine that can host a different operating system. I like to use VM Virtual Box (because its free) and the link to download the software is here:

[VM Virtual Box](https://www.virtualbox.org/wiki/Downloads)

Once you have downloaded Virtual Box feel free to download your favorite Linux OS, for first timers I recommend Ubuntu:
[Ubuntu OS](https://ubuntu.com/download)

Some notes about the configuration of the VM, please allocate (if possible) about 20 GB of storage space (at minimum 10 GB), and dedicate half or a quarter of your RAM to the VM.
### MacOS
You either can download Virtual Box from the section above or download Xcode to run C/C++ software. If you download Xcode you will be programming in your MacOS terminal.

### Windows
You either can dowload Virtual Box from the section above or activate and use the Linux system for Windows 10. You can follow the tutorial [here](https://www.maketecheasier.com/install-linux-subsystem-for-windows10/)

## Updating and downloading packages for your terminal
(If you have MacOS skip this step)
Once you have set up your Linux (not MacOS) system and have your terminal up and running type the following commands:

        sudo apt-get update -y
        sudo apt-get upgrade -y
        sudo apt-get dist-upgrade -y

This should update all current packages installed (and is needed before installing additional packages). After all the packages have been updated, type these commands:

        sudo apt-get install gcc
        sudo apt-get install make
        sudo apt-get install git

## Using Git and GitHub
[Here](https://www.youtube.com/watch?v=w3jLJU7DT5E) is a quick video on what GitHub is
