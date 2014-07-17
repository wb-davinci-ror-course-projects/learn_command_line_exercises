# Chapter 7

## English Questions (include commands)

>### Can you remove the tmp directory?

#### $ rmdir t(tab)

#### Yes, I was able to remove the tmp directory.

>### Let's clear out your log directory.

#### $ rmdir log

## Do More

>### Make 20 directories and remove them all.

$ mkdir -p dir_01/dir_02/dir_03/dir_04/dir_05/dir_06/dir_07/dir_08/dir_09/dir_10/dir_11/dir_12/dir_13/dir_14/dir_15/dir_16/dir_17/dir_18/dir_19/dir_10

$ cd dir_01/dir_02/dir_03/dir_04/dir_05/dir_06/dir_07/dir_08/dir_09/dir_10/dir_11/dir_12/dir_13/dir_14/dir_15/dir_16/dir_17/dir_18/dir_19/

$ rmdir dir_20

$ cd ..

$ rmdir dir_19

$ cd ..

$ rmdir dir_18

and so on ...

$ ls

$ Readme.md  dir_01/

$ rm d(tab)

>### Make a single path of directories that is 10 deep and remove them one at a time just like I did above.

$ mkdir -p first/second/third/fourth/fifth/sixth/seventh/eigth/ninth/tenth

$ cd first/second/third/fourth/fifth/sixth/seventh/eigth/ninth/

$ rmdir tenth

$ cd ..

$ rmdir ninth

$ cd ..

and so on ...

$ ls

$ Readme.md  first/

$ rm f(tab)

$ ls

$ Readme.md



