> Can you rename foo.txt to blah.txt?

Daniels-MacBook-Pro:log $ ls

foo.txt        newplace       production.log uncool.txt


Daniels-MacBook-Pro:log $ mv foo.txt blah.txt


Daniels-MacBook-Pro:log $ ls

blah.txt       newplace       production.log uncool.txt


> Can you move the production.log file in the log directory to slash temp?

Daniels-MacBook-Pro:log $ ls

blah.txt       newplace       production.log uncool.txt


Daniels-MacBook-Pro:log $ mv production.log /tmp/production.log


Daniels-MacBook-Pro:log $ ls /tmp

KSDownloadAction.o7ZhlfzX5r

KSOutOfProcessFetcher.501.HVXI9pQwBk_bgiVJaTNhiQNhqxc=

KSOutOfProcessFetcher.501.I5ci1K_TwCwqo1sKvc0siaBbJTw=

com.apple.launchd.Gf5gmGoD6u

com.apple.launchd.lFoOHh6HPz

production.log


> Move a file in the newplace directory to another directory then move it back.


Daniels-MacBook-Pro:newplace $ ls

a_random_file.txt


Daniels-MacBook-Pro:newplace $ mv a_random_file.txt ../../


Daniels-MacBook-Pro:newplace $ ls ../..

Readme.md         a_random_file.txt log


Daniels-MacBook-Pro:newplace $ mv ../../a_random_file.txt ../


Daniels-MacBook-Pro:newplace $ ls ..

a_random_file.txt blah.txt          newplace          production.log    uncool.txt
