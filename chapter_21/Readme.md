# Chapter 21

## English Questions

>### What is your shell set to?

#### $ env | grep SHELL
     SHELL=/bin/bash

>### What directory are you in (don't use pwd this time)?

#### $ env | grep PWD
     PWD=/Users/wb9753	

>### What is your home directory set to?

#### $ env
     HOME=/Users/wb9753

>### Can you set your environment to have DEBUG set to true?

#### $ export DEBUG=true


## Do More

>### I want you to go online and research how you change your PATH for your computer. Try to do it entirely from the CLI. From PivotalTracker story: Create a bin directory in your home directory and add it as the first item in your path.  After you get it working in your current terminal, make it permanent.



#### $ vim .bash_profile
	add to file:

	export PATH=/bin/Users/wb9753/.rvm/gems/ruby-2.1.2/bin:/Users/wb9753/
	.rvm/gems/ruby-2.1.2@global/bin:/Users/wb9753/.rvm/rubies/ruby-2.1.2/
	bin:/usr/local/heroku/bin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbi
	n:/Users/wb9753/.rvm/bin
      :wq

