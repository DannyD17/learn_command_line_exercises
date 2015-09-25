The commands pushd and popd and another way of navigating through directories, though they do it in a slightly
different mannor then the cd command.  pushd "pushes" or stores the current working directory into a list to be 
used later and temperally changes your working directory.  An example of this would be

> pushd /tmp/stuff/things/frank/joe/alex

This will store the current directory (In this example I am working in Chapter_8 directory) and move you to alex.

The command popd will take the last directory that was pushed and moves pops it off the list and changes to that directory.
