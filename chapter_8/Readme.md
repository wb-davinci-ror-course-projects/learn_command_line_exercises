## Pivital Task

>### 'mkdir -p' command will make the entire path even if all the firectories don't exist

#### _mkdir -p tmp/stuff/things/frank/joe/alex/john_  

$ pwd
/Users/wb9753/workspace/davinci_coders_t2_2014/learn_command_line_exercises/chapter_8/tmp/stuff/things/frank/joe/alex/john

>### Explain what the 'pushd' command does.

#### _It keeps track on the present working directory so you can come back to it from another directory with one one command_

>### Explain what the 'popd' command does.

#### _It is the command used once, after a pushd was used in a previous directory, to go back to that directory._

## Do More

>### Explain what directories you visited.

#### _Using a pushd command things/frank/joe/alex/john while in the stuff directory. It put me in the john directory. I used the popd command and it took me back into the stuff directory. It seems popd only works once, when I changed back into the john directory by using cd instead of pushd it gave the error 'directory stack empty'_

#### _While in the john directory I used pushd ../../.. and it put me in the frank directory. When I used popd it took me back to the john directory.

>### Explain the output that pushd and popd print out to you.

#### _The first line of output is the directory path that you are going to be in and the next line of output is the path you will return to if you use the command 'popd'_

