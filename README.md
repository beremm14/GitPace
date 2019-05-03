# GitPace
Faster way to use Git

## What it does
ADD, COMMIT & PUSH of your current directory to a remote.

## How to use
Type `git pace <message>` into your terminal, the message is optional.

## Installation
  You have to copy the `git-pace`-File to your `$PATH`. Probably your `$PATH` is `/usr/bin`, check with `echo $PATH`.  
  The file has to be executable: `chmod +x git-pace`.  
  Look at the `install.sh`...  
### Problems on macOS:
  In macOS the permission to this directory is denied. You have to enable it.  
  Reboot and hold the Keys command + R  
  In the Terminal run: `csrutil disable` and reboot.  
  Then it works.  
