Do more steps

> Daniels-MacBook-Pro:Chapter_7 $ mkdir -p tmp/stuff/things/frank/joe/alex/john

> Daniels-MacBook-Pro:Chapter_7 $ cd tmp/stuff/things/frank/joe/alex/john/

> Daniels-MacBook-Pro:john $ ls

> Daniels-MacBook-Pro:john $ cd ..

> Daniels-MacBook-Pro:alex $ rmdir john/

> Daniels-MacBook-Pro:alex $ ls

> Daniels-MacBook-Pro:alex $ cd ..

> Daniels-MacBook-Pro:joe $ ls
\nalex

> Daniels-MacBook-Pro:joe $ rmdir alex/

> Daniels-MacBook-Pro:joe $ cd ..

> Daniels-MacBook-Pro:frank $ ls
joe

> Daniels-MacBook-Pro:frank $ rmdir joe/

> Daniels-MacBook-Pro:frank $ ls

> Daniels-MacBook-Pro:frank $ cd ..

> Daniels-MacBook-Pro:things $ ls
frank

> Daniels-MacBook-Pro:things $ rmdir frank/

> Daniels-MacBook-Pro:things $ ls

> Daniels-MacBook-Pro:things $ cd ..

> Daniels-MacBook-Pro:stuff $ ls
things

> Daniels-MacBook-Pro:stuff $ rmdir things/

> Daniels-MacBook-Pro:stuff $ ls

> Daniels-MacBook-Pro:stuff $ ls

> Daniels-MacBook-Pro:stuff $ cd ..

> Daniels-MacBook-Pro:tmp $ ls
stuff

> Daniels-MacBook-Pro:tmp $ rmdir stuff

> Daniels-MacBook-Pro:tmp $ ls

> Daniels-MacBook-Pro:tmp $ pwd
/Users/Danny/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_7/tmp

Can you remove the tmp directory?

> Daniels-MacBook-Pro:Chapter_7 $ pwd
  /Users/Danny/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_7
> Daniels-MacBook-Pro:Chapter_7 $ ls
  Readme.md tmp
> Daniels-MacBook-Pro:Chapter_7 $ rmdir tmp
> Daniels-MacBook-Pro:Chapter_7 $ ls
> Daniels-MacBook-Pro:Chapter_7 $ ls
  Readme.md 
  
Let's remove the tmp directory.

> Daniels-MacBook-Pro:Chapter_7 $ rmdir tmp

