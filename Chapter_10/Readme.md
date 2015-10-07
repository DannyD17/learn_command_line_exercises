What is robocopy?

>Robocopy is robust file copy, a windows command that copys files but offers additional functionality, including the ability
to tolerate network interuptions, skip files that appear in a destination, etc.

Can you copy the foo.txt file to slash temp?  (Create foo.txt first...)

    Daniels-MacBook-Pro:tmp $ touch foo.txt


    Daniels-MacBook-Pro:tmp $ ls

    awesome.txt       iamcool.txt       newplace          something         thefourthfile.txt
    foo.txt           neat.txt          newplace2         something_else


    Daniels-MacBook-Pro:tmp $ cp foo.txt /tmp


    Daniels-MacBook-Pro:tmp $ ls /tmp

    KSDownloadAction.o7ZhlfzX5r
    KSOutOfProcessFetcher.501.HVXI9pQwBk_bgiVJaTNhiQNhqxc=
    KSOutOfProcessFetcher.501.I5ci1K_TwCwqo1sKvc0siaBbJTw=
    com.apple.launchd.Gf5gmGoD6u
    com.apple.launchd.lFoOHh6HPz
    foo.txt


Can you copy .bash_profile in your home directory to the current directory?

    Daniels-MacBook-Pro:~ $ cp .bash_profile workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_10/.bash_profile


    Daniels-MacBook-Pro:~ $ cd workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_10

    Daniels-MacBook-Pro:Chapter_10 $ ls -a
    .             .DS_Store     Readme.md
    ..            .bash_profile tmp

Use the cp -r command to copy more directories with files in them.

    Daniels-MacBook-Pro:tmp $ cp -r newplace newplace2


    Daniels-MacBook-Pro:tmp $ ls

    awesome.txt       neat.txt          newplace2         thefourthfile.txt
    iamcool.txt       newplace          something


    Daniels-MacBook-Pro:tmp $ cp -r something something_else

    Daniels-MacBook-Pro:tmp $ ls

    awesome.txt       neat.txt          newplace2         something_else
    iamcool.txt       newplace          something         thefourthfile.txt


Copy a file to your home directory or desktop.

    Daniels-MacBook-Pro:tmp $ pwd

    /Users/Danny/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/Chapter_10/tmp


    Daniels-MacBook-Pro:tmp $ cp awesome.txt ../../../../../..


    Daniels-MacBook-Pro:tmp $ ls ../../../../../..

    Applications     Downloads        Music            RubymineProjects workspace
    Desktop          Library          Pictures         awesome.txt
    Documents        Movies           Public           gitignore_global


Find these files in your graphical user interface and open them in a text editor.

>Open finder and work through the folder path until files are reached.
