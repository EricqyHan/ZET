# Boost Day 4

## Todo Summary

How to reconnect to a saved VM session with SSH
Where are all mu files and why are they there?
How do I remove add and rename files and directories
How Do I edit files?

## Timestamps

00:22:01 - What is a home directory

## Commands to Know

`set -o noclobber` (secure copy)- stop from blowing away files

`scp foo target:foo` - copy foo from host to remote target home dir (def)

`apt update` - grabs down copies of libraries to update your computer

`ls -ld .` - to see permissions of current directory

`stat foo` - see all details about the `foo` inode

`cd` - change into previous directory

`cp foo other` copy file/directory foo name to other

`cp -ar foo other` recursively copy foo to another keeping times

`sudo adduser foo` - interactively add a user name food

`chmod` - Change the premissions on a file.

`chown rando foo` - change ownership of foo to rando

`chown -R jill:jill olddir` - recursively change ownership/group

`sudo passwd foo` - change the password for foo

`sudo passwd - change own password `echo foo`- writes out echo to foo`echo echo 'hello world' > helloworld.txt`creates a line of text of hello world in helloworld.txt`which foo`- prints full file path to the executable foo`sudo chown gilfoyle bar-for-sample.md`- change ownership of foo to bar-for-sample.md to user gilfoyle`

`mv foo other`change filename from foo to other

`rmdir`- remove and empty directory

`rm -rf` - remove an empty foo directory. Note that the f is for when you write scripts and confirms it.

`grep jill /etc/passwd` - list only line containing jill

## Notes

- Console is hardware or simulation of hardware
  - how you call a keyboard and display atached to your server
- Terminal is usually running on a console, or remote terminal running on secure shell
  - software interface with the user
- What is a home directory? - Where all your user files go, where they live
  - You need a home directory because computers traditionally
  - So that a user is separate permissions from everyone else
  - Computers systems started as multi user
- Everything is an inode
- What is CHOMD - change permission
  - CHMOD is a good way to bruteforce into a system
- X on the file means
- echo command and how to learn it
- How do I change user or group file
- Files and directories have users id and group id independent from the system
  - becasue of security

## Things to watch, read, or do

Review the premissions section
