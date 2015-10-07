Do More

    Daniels-MacBook-Pro:temp $ mkdir test
    Daniels-MacBook-Pro:temp $ ls
    iamcool.txt test
    Daniels-MacBook-Pro:temp $ touch test/hello.txt
    Daniels-MacBook-Pro:temp $ cd test/
    Daniels-MacBook-Pro:test $ ls
    hello.txt

    Daniels-MacBook-Pro:test $ cd ..
    Daniels-MacBook-Pro:temp $ rmdir test
    rmdir: test: Directory not empty

Can you touch blah.txt?

    Daniels-MacBook-Pro:Chapter_9 $ ls
    Readme.md temp

    Daniels-MacBook-Pro:Chapter_9 $ touch blah.txt
    
    Daniels-MacBook-Pro:Chapter_9 $ ls
    Readme.md blah.txt  temp

Let's create foo.txt

    Daniels-MacBook-Pro:Chapter_9 $ touch foo.txt

    Daniels-MacBook-Pro:Chapter_9 $ ls
    Readme.md blah.txt  foo.txt   temp

What happens if you touch an existing file?

>It will change the time that the file was last modified

    Daniels-MacBook-Pro:Chapter_9 $ ls -l foo.txt
    -rw-r--r--  1 Danny  staff  24 Oct  7 13:47 foo.txt

    Daniels-MacBook-Pro:Chapter_9 $ cat foo.txt
    Hello foo, how are you?

    Daniels-MacBook-Pro:Chapter_9 $ touch foo.txt

    Daniels-MacBook-Pro:Chapter_9 $ ls -l foo.txt
    -rw-r--r--  1 Danny  staff  24 Oct  7 13:52 foo.txt

    Daniels-MacBook-Pro:Chapter_9 $ cat  foo.txt
    Hello foo, how are you?

