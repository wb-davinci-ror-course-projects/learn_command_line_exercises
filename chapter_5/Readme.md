## English Questions

>### Can you cd into the temp directory?

#### Yes
#### cd tmp

>### Why we do not go into the temp directory?

#### The temp directory is automatically set up in each directory by the system to keep track of the visual aspects of the folder. It is a hidden directory and is created with the intention of the user not needing to edit it. http://www.westwind.com/reference/OS-X/invisibles.html

>### Can you go to the slash temp directory?

#### Yes

$ cd /tmp
/tmp$ ls
launch-pIKssZ/       launchd-3363.TqcIrh/
launch-rkSBp6/       launchd-787.DTDH8t/
launchd-1232.MFwqyp/ log/
launchd-253.u9K9qa/

>### Can you go to the slash temp slash log directory

#### cd /tmp/log

>### What does the .. argument to cd do? Explain it in the Readme.md

#### It takes you back / up one in the directory tree.

$ cd ..

## Do More

>### cd to the joe directory with one command

#### $ cd tmp/stuff/things/frank/joe

>### cd back to temp with one command, but not further above that

#### cd ../../../..

>### Find out how to cd to your "home directory" with one command.

#### cd ~

>### cd to your Documents directory

#### cd ~/Doc(tab)

>### cd to your Downloads directory

#### cd ~/Dow(tab)

>### Find another directory with your file browser, then cd to it

#### cd ~/d(tab)/Gra(tab)

_~/danelec_photos/Grand Canyon$_

>### $ cd ~/workspace/davinci_coders_t2_2014/learn_command_line_exercises/chapter_4/"I Have Fun"

#### ~/workspace/davinci_coders_t2_2014/learn_command_line_exercises/chapter_4/I Have Fun$
