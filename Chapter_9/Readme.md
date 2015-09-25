> Do More

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


> Can you touch blah.txt?

Daniels-MacBook-Pro:Chapter_9 $ ls

Readme.md temp

Daniels-MacBook-Pro:Chapter_9 $ touch blah.txt

Daniels-MacBook-Pro:Chapter_9 $ ls

Readme.md blah.txt  temp

> Let's create foo.txt

Daniels-MacBook-Pro:Chapter_9 $ touch foo.txt

Daniels-MacBook-Pro:Chapter_9 $ ls

Readme.md blah.txt  foo.txt   temp

> What happens if you touch an existing file?

The file already exists and nothing will happen.  Here is an example of using touch foo.txt when it already exists.

Daniels-MacBook-Pro:Chapter_9 $ ls

Readme.md blah.txt  foo.txt   temp

Daniels-MacBook-Pro:Chapter_9 $ touch foo.txt

Daniels-MacBook-Pro:Chapter_9 $ ls

Readme.md blah.txt  foo.txt   temp
