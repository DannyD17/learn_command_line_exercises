> Can you show me the contents of database.yml?

Daniels-MacBook-Pro:tmp $ cat database.yml

This is some random text that I pulled from my blog.

For our class we looked at Git and its 3 main components.  But before we look at that, what is Git?
Git is a revision control system which allows its users to keep track of changes made to files over time.
It keeps logs of changes made and reasons why and allows developers to easily share changes.

> What is in your Gemfile?

Daniels-MacBook-Pro:tmp $ cat Gemfile

This is some random text that I pulled from my blog.

                                      When working with git there are 3 main areas that a file or files may be in.  The working directory, the staging area,
                            and the repository.  The working directory is where a version of the file is worked on or modified.
                              Once work on the file completed it can be placed into the staging area.
                                                          This is where the files are added to the stage to be committed.
                                                                                    Multiple files and changes can be added to the stage.  Once ready you can commit the files to the repository.
                                                            Once committed, git takes the edited files and stores them in the git directory.
                                Changes are logged and files are then available for checkout at a later time.

> Do more

> Make a few more text files and work with cat.

Daniels-MacBook-Pro:tmp $ echo "This is another test of the cat command" > test.txt


Daniels-MacBook-Pro:tmp $ cat test.txt

This is another test of the cat command


Daniels-MacBook-Pro:tmp $ cp test.txt testCopy.txt


Daniels-MacBook-Pro:tmp $ cat testCopy.txt

This is another test of the cat command

> Unix: Try cat ex12.txt ex13.txt and see what it does.

Daniels-MacBook-Pro:tmp $ pwd

/Users/Danny/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_12/tmp


Daniels-MacBook-Pro:tmp $ cat ex12.txt

Hello, this is a test

Hello, yup, still a test

Doing it again

Hello, this is a test

Hello, yup, still a test

Doing it again

Hello, this is a test

Hello, yup, still a test
