# Chapter 18

## English Questions

>### Does your log file have any GET requests?

#### $ grep -i 'GET ' *.log

>### Can you show me the gem lines from your Gemfile?

#### $ grep 'gem ' Gemfile

>### Can you print all the lines in text files that have your first and last name in them?

#### $ grep -i 'Wendy Brannon' *.txt

>### Use cat > newfile.txt to write some content to newfile.txt.

#### $ cat > newfile.txt
new content inside the newfile.txt file
('control C' to exit and save)

>### Add a comment to the Readme.md that explains what the -i option to grep accomplishes.

#### $ cat >> Readme.md
The -i option will make the search not case sensitive


## Do More

>### Use quotes to find "new file" and "old file" and "This is".

$ pwd
/Users/wb9753/workspace/davinci_coders_t2_2014/learn_command_line_exercises/chapter_18

#### $ grep 'new file' *.txt

#### $ grep 'old file' *.txt

#### $ grep 'This is' *.txt

>### Take the list of videos you created (or any other list) and use it to find some videos you want to find.
Unix:
 
#### The following command is using grep to find the files I used 'Do More' as a section title and any other time it shows up in a Readme.md file within the chapter directories

#### $ grep 'Do More' chapter_\*/\*.md
chapter_10/Readme.md:## Do More
chapter_11/Readme.md:## Do More
chapter_12/Readme.md:## Do More
chapter_13/Readme.md:## Do More
chapter_14/Readme.md:## Do More
chapter_15/Readme.md:## Do More
chapter_15/Readme.md:#### I made Anki cards for all the commands listed in Do More
chapter_16/Readme.md:## Do More
chapter_17/Readme.md:## Do More
chapter_17/Readme.md:##### note: I ran into permission denied at this point. The above above output was inserted in this file by the command used to complete this Do More exercise
chapter_18/Readme.md:## Do More
chapter_5/Readme.md:## Do More
chapter_6/Readme.md:## Do More
chapter_6/Readme.md:>### Describe what ls -lR does in the Readme.md (Do More section)
chapter_6/Readme.md:#### The ls ~/L(tab) command is much quicker than then using cd as the Do More question asks. For example answering the question using cd ...
chapter_7/Readme.md:## Do More
chapter_8/Readme.md:## Do More
chapter_9/Readme.md:## Do More

>### You can use -i to ignore case with grep. Try grep -i new *.txt

#### $ grep -i 'NEW' *.txt
newfile.txt:This is a new file.
newfile.txt:This is a new file.
newfile.txt:This is a new file.


