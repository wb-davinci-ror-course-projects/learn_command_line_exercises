# Chapter 9

## English Questions

##### $ pwd
##### /Users/wb9753/workspace/davinci_coders_t2_2014/learn_command_line_exercises/chapter_9

>### Can you touch blah.txt?

#### Yes

#### $ touch blah.txt

#### $ ls 

#### It created the file blah.txt

>### Let's create foo.txt

#### $ touch foo.txt

#### $ ls
#### Readme.md  blah.txt   foo.txt

>### What happens if you touch an existing file.

#### All it seems to do is change the updated at time

#### $ ls -lR
#### total 8
testing
#### -rw-r--r--  1 wb9753  staff  584 Jul  7 12:38 Readme.md
#### -rw-r--r--  1 wb9753  staff    0 Jul  7 12:45 blah.txt
#### -rw-r--r--  1 wb9753  staff    0 Jul  7 12:47 foo.txt

#### $ touch foo.txt

#### $ ls -lR
#### total 8
####-rw-r--r--  1 wb9753  staff  584 Jul  7 12:38 Readme.md
#### -rw-r--r--  1 wb9753  staff    0 Jul  7 12:45 blah.txt
#### -rw-r--r--  1 wb9753  staff    0 Jul  7 12:49 foo.txt

#### $ cat foo.txt
#### testing touch same file

#### $ touch foo.txt

#### $ cat foo.txt
#### testing touch same file



## Do More

>### Make a directory, change to it and then make a file in it. Then change one level up and run the rmdir command in this directory.

##### $ pwd
##### /Users/wb9753/workspace/davinci_coders_t2_2014/learn_command_line_exercises/chapter_9

#### $ mkdir fruit 

#### $ cd fruit

#### $ touch apple

#### $ cd ..

#### $ rmdir fruit
rmdir: fruit: Directory not empty

#### The 'rmdir' command will not delete a directory with files in it. Delete 'apple' file and the go up a directory and delete 'fruit' directory.

##### $ pwd
##### /Users/wb9753/workspace/davinci_coders_t2_2014/learn_command_line_exercises/chapter_9

#### $ cd fruit

#### $ rm fruit

#### $ cd ..

#### $ rmdir fruit

