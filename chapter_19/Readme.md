## English Questions

>### What option to ls tells it to output file size in human readable form?

####

>### Is there a case insensitive option to grep?

####

>### What does the -r and -f options to rm do exactly?

####

>### What does the ifconfig command do?

####

## Do More

>### Use man or help to look at every one of the commands you have in your list to memorize.

$ man pwd
$ man hostname
	$ hostname
	Wendys-MacBook-Pro.local
	$ hostname -s
	Wendys-MacBook-Pro
$ man mkdir
	$ mkdir -v new_dir
	mkdir: created directory 'new_dir'
$ man cd
$ man ls
	$ pwd
	/Users/wb9753/workspace/davinci_coders_t2_2014/	       
	learn_command_line_exercises

	$ ls -cl
	total 8
	-rw-r--r--   1 wb9753  staff   193 Jul  7 12:24 README.md
	drwxr-xr-x   4 wb9753  staff   136 Jul  3 23:00 chapter_1/
	drwxr-xr-x   8 wb9753  staff   272 Jul 13 10:37 chapter_10/
	drwxr-xr-x   7 wb9753  staff   238 Jul 13 16:25 chapter_11/
	drwxr-xr-x   4 wb9753  staff   136 Jul 10 08:42 chapter_12/
	drwxr-xr-x   5 wb9753  staff   170 Jul 11 10:29 chapter_13/
	drwxr-xr-x   4 wb9753  staff   136 Jul 11 11:29 chapter_14/
	drwxr-xr-x   6 wb9753  staff   204 Jul 11 13:21 chapter_15/
	drwxr-xr-x   9 wb9753  staff   306 Jul 14 14:50 chapter_16/
	drwxr-xr-x   5 wb9753  staff   170 Jul 11 16:50 chapter_17/
	drwxr-xr-x   8 wb9753  staff   272 Jul 15 22:34 chapter_18/
	drwxr-xr-x   5 wb9753  staff   170 Jul 15 22:55 chapter_19/
	drwxr-xr-x   4 wb9753  staff   136 Jul  6 19:29 chapter_2/
	drwxr-xr-x   3 wb9753  staff   102 Jul 11 11:01 chapter_3/
	drwxr-xr-x  45 wb9753  staff  1530 Jul  6 20:18 chapter_4/
	drwxr-xr-x   4 wb9753  staff   136 Jul  7 12:16 chapter_5/
	drwxr-xr-x   5 wb9753  staff   170 Jul 13 10:23 chapter_6/
	drwxr-xr-x   3 wb9753  staff   102 Jul  6 16:07 chapter_7/
	drwxr-xr-x   4 wb9753  staff   136 Jul  6 16:25 chapter_8/
	drwxr-xr-x   6 wb9753  staff   204 Jul  7 15:30 chapter_9/

	$ ls -ct
	chapter_19/ chapter_10/ chapter_14/ chapter_9/  chapter_2/
	chapter_18/ chapter_6/  chapter_3/  README.md   chapter_8/
	chapter_16/ chapter_17/ chapter_13/ chapter_5/  chapter_7/
	chapter_11/ chapter_15/ chapter_12/ chapter_4/  chapter_1/

	note(above): chapter_19 was updated most recently, then chapter_18...

	$ ls -ctr
	chapter_1/  chapter_4/  chapter_12/ chapter_15/ chapter_11/
	chapter_7/  chapter_5/  chapter_13/ chapter_17/ chapter_16/
	chapter_8/  README.md   chapter_3/  chapter_6/  chapter_18/
	chapter_2/  chapter_9/  chapter_14/ chapter_10/ chapter_19/

$ man rmdir
$ man pushd
$ man popd
$ man cp
$ man mv
	$ mv -v file_2 ..
	file_2 -> ../file_2
$ man less
	$ less Readme.md
	note: by typing 'v' before exiting invokes vim to edit file
$ man cat
$ man xargs
$ man find
$ man grep
$ man man
$ man apropos
$ man env
$ man echo
$ man export
$ man exit
$ man sudo
$ man chmod
$ man chown

