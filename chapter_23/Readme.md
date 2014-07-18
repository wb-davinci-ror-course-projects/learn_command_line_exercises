# Chapter 23

## English Questions & Tasks

>### Let's close this terminal and open a new one.

#### $ exit

#### click the iTerm icon or in Finder click the iTerm application

>### Can you reload your terminal?

#### $ source ~/.bash_profile

>### Can you logout?

#### Command + Option + Shift + Q

## Do More

>### For your last set of exercises I'm going to have you use the help system to look up a set of commands you should research and learn how to use on your own. From PivotalTracker: Explain the commands he lists for Unix in Readme.md.

I couldn't find by typing help and those commands
from: http://ss64.com/osx/ and http://www.computerhope.com/unix/uchown.htm

>### xargs

#### Execute utility - passing arguments

#### The following command finds files named Readme.md~ and deletes them, that are in or below the home '~' directory

#### find /~ -name Readme.md~ -type f -print | xargs /bin/rm -f

>### sudo

#### Execute a command as another user.

>### chmod

#### Change access permissions, make files executable

#### chmod 755 some_file 

>### chown

##### Set or change the owner of file to my user name,since there is only one user name for this computer it is the only one that can be set
 
#### $ chown wb9753 some_file.txt 

