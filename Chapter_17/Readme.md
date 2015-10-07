Can you show me all the files in slash temp slash foo?

    (master) Danny Debevec
    Daniels-MacBook-Pro:log $ find /tmp/foo
    /tmp/foo
    /tmp/foo/foo.log
    /tmp/foo/foo.txt
    /tmp/foo/test.txt

What log files are in your log directory?

    (master) Danny Debevec
    Daniels-MacBook-Pro:Chapter_17 $ find . -name '*.log' -print
    ./log/hello.log
    ./log/log.log
    ./log/random.log
    ./log/test.log
    ./log/wood.log
