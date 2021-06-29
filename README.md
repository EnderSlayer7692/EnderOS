# EnderOS
An operating system written in assembly, C, and C++ designed to be simple and easily modifiable.
# How To Use
## Compiling
##### REQUIRES LINUX TO COMPILE

_Ubuntu is reccomended, but look at the wiki to get info on dependencies to build._

Remember: if your username is root, do not use sudo, or it will not work.


```sudo apt update```: This updates all of your software via apt, so the following commands

```sudo apt-get update```: This command does the same thing, but via apt-get, not apt.

```sudo apt-get install nasm```: This installs NASM, what we will use to turn the code to a OS image

```sudo apt-get install qemu```: This lets us use the OS without installing it to our computer

```sudo apt-get install qemu-system``` This adds the command qemu-system-x86_64, which we will use, (among other things)

```sudo apt-get install gcc``` This allows us to use C and C++.

```sudo apt-get install nano``` This allows us to make, write and edit files.

Once you have ran all of those commands, (supposing you had no errors, but if you did, [fix them here](https://github.com/EnderSlayer6792/EnderOS/wiki/Fixing-Errors))

