# Boost Day 3

## TODO Summarize

- How to connect to our vm? - A VM
- What is NAT and Bridged
- What is an ip address - It is an address to your house
- What is git-bash and why would I need it?
- What about putty for ssh access?
- Difference between which and type
- How can you test SSH connection to loacl host?
- What is a USER and USERID?
- How can I see stuff scrolling off screen?
- What is correct SSH connection address
- How to get a VM on the Internet
  - Digital Ocean
  - Linode
  - Vultur

## Timestamps

02:47:44 - Windows Terminal Settings

## Commands to know

`ip a` show all ip addresses

`ipconfig /all`

`clear` clears the screen

`which ssh` display full path to ssh program

`type ssh` display what type of thing it is

`who` display who is logged in and how

`w` displays logger version of who is logged in

`user` short name of all name of logged in user

`last` summary of last logged in users

`whoami` print effective user name/ID

`exit` exit the current program or login or shell

`| less` or `| more` - see scrolling off screen

`apt search ssh | less` - look through all ssh

`service sshd status` - tell you how long something has been running for

`ssh user@ip` - headless start

## Notes

- Difference between console and terminal?
  - A physical console or equivalent of a console that is digital
    - a console is physical thing you would see
- We can connect to our VM with secure shell
  - telnet is not secure... so don't use it because everything is plain text
- If you are a hacker, first thing you do when you hack into somewhere is install a reverse shell
  - like SSHD
- NAT vs Vridged
  - NAT - Network Address Translation: Means taking all connections and go out, and when it comes back it knows who to give it to
  - Bridged - We will pretend that this vm is not inside the host and that it is next to it. VM is now just like any other computer next to you. Basically adding another computer to your household
    - Gets a brand new ip address
    - You need to be bridged to SSH
    - NOTE: Bridged interface will use same physical inerface with a different IP and MAC address
- IP Address - A way to get to a computer.
- Difference between which and type
  - type will tell you if it is command or if it is something else you can run
- Loopback and ENP0S3
- If you are having problems SSHing into your computer try to ssh into your computer from local host
- What is a user and userID
  - Everyone has a user and everyone has an ID
  - UserID is uid
- TTY - is Teletype
  - there 7 console ttys
- pts/0 - is ssh connection
- Learn how to take a snapshot in a VM
- Putty - can be installed on any windows system.
  - Remember a PORT "a number on the door of the build and IP is address of the building"
  - A host fingerprint can change on something we are trying to connect to when an IP address changes
- Windows Terminal
  - F11 to fullscreen
  - `CTRL + ,` to get to settings
  - `CTRL + SHIFT + W` to go back
- What is JSON? - Javascript Object Notation
  - Key value pairs
- Setting up a cloud server and what we need to think about
  - Security
  - Need to know how to harden your server
- Headless systems
  -

## Things to watch or do

- Create a Digital Ocean Account and create a VM on there
-

## Readings
