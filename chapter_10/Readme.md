# Chapter 10

## English Questions

>### Can you copy the foo.txt file to slash temp? (Create foo.txt first...)

$ pwd
/Users/wb9753/workspace/davinci_coders_t2_2014/learn_command_line_exercises/chapter_10

_all following commands start in this directory_

#### $ cp foo.txt tmp/

#### $ ls tmp/
awesome.txt  iamcool.txt  newplace/
foo.txt      neat.txt     something/

>### Can you copy .bash_profile in your home directory to the current directory?

#### Yes

#### $ cp ~/.bash_profile ~/workspace/davinci_coders_t2_2014/learn_command_line_exercises/chapter_10

#### $ cat .bash_profile

[[ -s "$HOME/.profile" ]] && source "$HOME/.profile" # Load the default .profile

if [ -f ~/.bashrc ]; then
  source ~/.bashrc
fi

[[ -s "$HOME/.rvm/scripts/rvm" ]] && source "$HOME/.rvm/scripts/rvm" # Load RVM into a shell session *as a function*

if [ -f $(brew --prefix)/etc/bash_completion ]; then
  . $(brew --prefix)/etc/bash_completion
fi

>### What is Robocopy

#### It copies files and directories, used with Windows._http://en.wikipedia.org/wiki/Robocopy_

## Do More

$ pwd
/Users/wb9753/workspace/davinci_coders_t2_2014/learn_command_line_exercises/chapter_10/tmp/

_all following commands start in this directory_

>### Use the cp -r command to copy more directories with files in them.

#### $ cp -r something ~/workspace/davinci_coders_t2_2014/learn_command_line_exercises/chapter_10/new_dir

#### _I copied the something directory to the chapter_10 directory and named it new_dir in the process

#### $ ls ~/workspace/davinci_coders_t2_2014/learn_command_line_exercises/chapter_10
#### Readme.md  foo.txt    new_dir/   tmp/

>### Copy a file to your home directory or desktop.

#### $ cp awesome.txt ~/workspace

#### $ ls ~/workspace
Icon?
Pivotal-Preferences-RubyMine/
awesome.txt
davinci_coders_t2_2014/
tmp/


>### Find these files in your graphical user interface and open them in a text editor.

#### Finder, home directory, workpace folder, davinci_coders_t2_2014 folder, learn_command_line_exercises folder, chapter_10 folder, awesome.txt, option key + right click, open with, other, in App. folder, RubyMine.app, open

