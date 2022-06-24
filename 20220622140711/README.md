# Boost Day 2

## TODO Summarize

- What is unix and linux?

## Timestamps

## Commands to know

`ls -la` - list all files

`man ls` - manual for ls

`pwd` - print working directory

`shutdown -h now`, `init 0`, `poweroff` - different shutdown commands
`cd -` - change to previous directory
`cd` or `cd ~` - change directory back to home directory
`cd ..` change to parent directory
`cd ../..` change to parent of parent directory
`cd /` change to root directory
`sudo` - do it as root (superuser)
`apt` - use interactively only (use apt-get in scripts)
`apt update`- update all the soruces for packages
`apt upgrade` - upgrade all packages to latest version
`ls` - list fiels in the (current) directory
`man` - show manual info about a command
`ls -al` - list all files including hidden (begin with a .)
`hostname` - display name of host
`pwd` - print working directory
`apt search ^neo` - search all apps that have neo in the name
`sudo apt update` - update all sources for packages
`sudo apt upgrade` - take linux distro to latest level
`sudo apt install neofetch` - install neofetch
`sudo apt remove neofetch` - remove neofetch
`sudo apt autoremove` - remove everything taking up disk space that by thing you just removed

- when to use apt vs apt get?
  - never use APT in a script
    - Always use apt get

## Notes

- Two primary purposes of a mentor.
  - One: help you know what to learn
  - Two: help you know where to learn it
  - Three: Help you when you get stuck
- Command line is super powerful. LEARN TO USE IT!
- What is difference between terminal, cli, and shell

  - Terminal - is what gives you cell based text screen
    - Terminals use "cells"
    - Comes from a original teletype machine
      - TTY - teletype
      - Note that terminal is a terminal emulator
      - A termianls is actually a terminal emulator to replace the teletype machine that was was used before
    - A CLI is aka as a REPL
      - anything that takes in input in a single line and prints it back out
      - Note CLI and terminal are not the same
        - use CLI you need terminal, but you don't need a terminal to use a CLI
      - Type command, computer prints something back, and prompts for more
      - A terminal everything about termianl experience, mapping, etc
    - Shell - interactive program that provides access to a deeper system
      - is a layer that is there to talk to the human
  - Difference between unix and linux
    - Linux came from minux
    - Unix used to cost $3,000 from AT&T
    - Mac is biggest BSD distribution in the world
    - C language was made to create unix by Dennis Richie

- APT is baseline package manager to learn to use

  - Advance Packaging Tool

- Three main distros - Only these matter to get a job

  - Ubuntu Server
  - Redhat
  - Susie Linux

- What is an "inode"

  - An inode is an entry in the directory
  - Why is everything "just a file?"
  - inode is an entry in a table
  - A directory is a table of inodes

- Everytime you execute a command, you are writing code
- Package is something that has been packaged up for installation
- BREW is a command line package manager

  - way to install and remove software on your computer on the command line
    - it is easier
  -

## Linux permissions

## Things to watch

## Readings

[Linux CommandLine](http://linuxcommand.org/index.php)
[Linux Family Tree](https://www.youtube.com/watch?v=2nF-MXeiXzw&ab_channel=brtidwell55)
