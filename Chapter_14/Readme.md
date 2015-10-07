Can you remove blah.txt?

    Daniels-MacBook-Pro:tmp $ rm blah.txt

Let's get rid of our development log file.

    Daniels-MacBook-Pro:tmp $ rm development.log

Can you remove everything in the slash temp slash foo directory?

    Daniels-MacBook-Pro:tmp $ rm -rf /tmp/foo/

Why should you never run rm -rf / command

>To understand why this is dangerous we need to look at what is contained in this destination.  
When we view the directories in the slash directory we find 

    Daniels-MacBook-Pro:tmp $ ls /

    Applications              bin                       net
    Library                   cores                     private
    Network                   dev                       sbin
    System                    etc                       tmp
    Users                     home                      usr
    Volumes                   installer.failurerequests var

>if we ran the command rm -rf / it would remove the slash directory and all of its contents and files.  This includes system
files as well as personal files.


Clean up everything in temp from all the exercises so far.

    Daniels-MacBook-Pro:tmp $ ls
    iamcool.txt neat.txt    uncool.txt

    Daniels-MacBook-Pro:tmp $ rm uncool.txt

    Daniels-MacBook-Pro:tmp $ ls
    iamcool.txt neat.txt
