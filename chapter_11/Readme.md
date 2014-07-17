# Chapter 11

## English Questions

pwd
/Users/wb9753/workspace/davinci_coders_t2_2014/learn_command_line_exercises/chapter_11/
_all following commands are in this directory_

>### Can you rename foo.txt to blah.txt?

#### $ mv foo.txt blah.txt

>### Can you move the production.log file in the log directory to slash temp?

#### mv log/production.log ~/workspace/davinci_coders_t2_2014/learn_command_line_exercises/chapter_11/tmp/

>### Can you zero out that file?

#### $ echo -n > ~/workspace/davinci_coders_t2_2014/learn_command_line_exercises/chapter_11/tmp/production.log

## Do More

>### Move a file in the newplace directory to another directory then move it back.

#### pwd
/Users/wb9753/workspace/davinci_coders_t2_2014/learn_command_line_exercises/chapter_11/tmp

_all following commands are in this directory_

#### $ ls
newplace/   uncool.txt

#### $ mv newplace ..

#### $ ls
uncool.txt

#### $ ls .. tmp/


