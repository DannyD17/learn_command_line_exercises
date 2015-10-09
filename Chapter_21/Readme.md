#Do More

I want you to go online and research how you change your PATH for your computer. Try to do it entirely from the CLI.

> In order to change your path you need to export the desired path location with the following comman

    export PATH=$PATH:/path/to/directory

>where the `path/to/directory` is whatever path you are trying to use

#English Questions

What is your shell set to?

    Daniels-MacBook-Pro:Chapter_21 $ env | grep -i shell
    SHELL=/bin/bash

What directory are you in (don't use pwd this time)?

>There are a couple of ways to do this

    Daniels-MacBook-Pro:Chapter_21 $ env | grep PWD
    OLDPWD=/Users/Danny/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises
    PWD=/Users/Danny/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_21
    
    Daniels-MacBook-Pro:Chapter_21 $ echo $PWD
    /Users/Danny/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_21

What is your home directory set to?

    Daniels-MacBook-Pro:Chapter_21 $ env | grep HOME
    HOME=/Users/Danny

Can you set your environment to have DEBUG set to true?

    export DEBUG=true
