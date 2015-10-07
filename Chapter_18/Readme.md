#English ways of asking

Show me the lines in foo.txt that have "ERROR" in them.

    Daniels-MacBook-Pro:Chapter_18 $ grep ERROR foo.txt
    ERROR.  This line contain s an ERROR.
    
    Daniels-MacBook-Pro:Chapter_18 $ grep -i ERROR foo.txt
    there may be an error or two, but this is just filler text.
    error in line 3.
    ERROR.  This line contain s an ERROR.

Show me the lines in bar.txt that have "davinci" in them.

    Daniels-MacBook-Pro:Chapter_18 $ grep davinci bar.txt
    and even more text.  This is all for my davinci ruby on rails class.
    davinci instatute ruby class
    
    Daniels-MacBook-Pro:Chapter_18 $ grep -i davinci bar.txt
    and even more text.  This is all for my davinci ruby on rails class.
    davinci instatute ruby class

Can you print all the lines in text files that have your first and last name in them?

    Daniels-MacBook-Pro:Chapter_18 $ grep -i "Danny Debevec" *.txt
    name.txt:Danny Debevec
    random_file.txt:Danny Debevec
    somefile.txt:danny debevec

#Do More

Use quotes to find "new file" and "old file" and "This is".

    Daniels-MacBook-Pro:Chapter_18 $ grep "new file" *.txt
    newfile.txt:This is a new file
    newfile.txt:This is a new file
    newfile.txt:This is a new file
    
    Daniels-MacBook-Pro:Chapter_18 $ grep "old file" *.txt
    outfile.txt:This is a old file
    outfile.txt:This is a old file
    outfile.txt:This is a old file
    
    Daniels-MacBook-Pro:Chapter_18 $ grep "This is" *.txt
    newfile.txt:This is a new file
    newfile.txt:This is a new file
    newfile.txt:This is a new file
    outfile.txt:This is a old file
    outfile.txt:This is a old file
    outfile.txt:This is a old file

Take the list of videos you created (or any other list) and use it to find some videos you want to find.

>I created a list of all the markdown files on my computer

    (master) Danny Debevec
    Daniels-MacBook-Pro:Chapter_18 $ grep learn_command all_md_files.txt
    ./workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_1/Readme.md
    ./workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_10/Readme.md
    ./workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_11/Readme.md
    ./workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_12/Readme.md
    ./workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_13/Readme.md
    ./workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_14/Readme.md
    ./workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_15/Readme.md
    ./workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_16/Readme.md
    ./workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_17/Readme.md
    ./workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_18/Readme.md
    ./workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_2/Readme.md
    ./workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_3/Readme.md
    ./workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_4/Readme.md
    ./workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_5/Readme.md
    ./workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_6/Readme.md
    ./workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_7/Readme.md
    ./workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_8/Readme.md
    ./workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_9/Readme.md
    ./workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/README.md

Unix: You can use -i to ignore case with grep. Try grep -i new *.txt

>The -i in grep is used to ignore the case sensitivity of the search.  As an example, when we look
at the commands below we see that `grep NEW` does not render any results.  When we ignore the case and
use `grep -i NEW` we will see the lines in the file that contain new

    Daniels-MacBook-Pro:Chapter_18 $ grep NEW *.txt
    
    Daniels-MacBook-Pro:Chapter_18 $ grep -i NEW *.txt
    newfile.txt:This is a new file
    newfile.txt:This is a new file
    newfile.txt:This is a new file
