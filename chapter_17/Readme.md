# Chapter 17

## English Questions

>### Can you show me all the files in slash temp slash foo?

#### $ find tmp/foo/ -name "*" -print

>### What log files are in your log directory?

#### $ find log/ -name "*.log" -print

>### Run find in the class directory, pipe the output to pbcopy and create a gist with the content.  Paste the Gist URL as a comment on this story.


#### $ find /Users/wb9753/workspace/davinci_coders_t2_2014/ -print | pbcopy

#### https://gist.github.com/be2bd3faba7c935e2160

## Do More

>### Unix: Get your find index card and add this to the description side: "find STARTDIR -name WILDCARD -print". Next time you drill make sure you can say that phrase so you remember how find is formatted.

#### Anki card created

>### You can put any directory where the . (dot) is. Try another directory to start your search there.

#### find ~ -name "*.rb" - print

#### this prints the ruby files from the home directory and the subdirectories


>### Look for all the video files on your computer starting at the home drive and use the > to save the list to a file. Remember how you can do SOMECOMMAND > SOMEFILE.txt and it will write the output of SOMECOMMAND to the file SOMEFILE.txt?

$ pwd
/Users/wb9753/workspace/davinci_coders_t2_2014/learn_command_line_exercises/chapter_17

#### find ~ -name "*.mov" -print >> Readme.md

/Users/wb9753/Downloads/IMG_02522.mov
/Users/wb9753/workspace/davinci_coders_t2_2014/ScreenCasts/.SyncArchive/Hi-Def/Moom Configuration.mov
/Users/wb9753/workspace/davinci_coders_t2_2014/ScreenCasts/Hi-Def/Build your brand.mov
/Users/wb9753/workspace/davinci_coders_t2_2014/ScreenCasts/Hi-Def/Learn Ruby the Hard Way Chapters 3-6.mov
/Users/wb9753/workspace/davinci_coders_t2_2014/ScreenCasts/Hi-Def/Learn Ruby the Hard Way Day 2.mov
/Users/wb9753/workspace/davinci_coders_t2_2014/ScreenCasts/Hi-Def/Moom Configuration.mov
/Users/wb9753/workspace/davinci_coders_t2_2014/ScreenCasts/Hi-Def/number_of_seconds_warmup.mov
/Users/wb9753/workspace/davinci_coders_t2_2014/ScreenCasts/Hi-Def/numbers_letters_and_variables.mov
/Users/wb9753/workspace/davinci_coders_t2_2014/ScreenCasts/Hi-Def/Pair Programming.mov

##### note: I ran into permission denied at this point. The above above output was inserted in this file by the command used to complete this Do More exercise
