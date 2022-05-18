#### Simple_shell
****
This is a project created by Obumneme Okoye and Amarachi Ihejiako. This project recreates the shell which is the Linux command line interpreter in its simplest form. It provides an interface between the user and the kernel and executes programs.

#### Start
**1. Git clone this respository to your local directory.
$ git clone https://github.com/Obumbillions/simple_shell.git

**2. Compile the program.
$ gcc -Wall -Werror -Wextra -pedantic *.c -o hsh

**3. Now execute the shell.
$ ./hsh

#### Builtin Commands
**This shell supports the next builtin commands:

cd - change directory

env - list the current environment variables

exit - exit the shell

help - show help for a builtin command

pwd - Print the absolute pathname of the current working directory

unsetenv - Remove an environment variable

#### Delimit and comment commands
; -  The semicolon. command separator that allows to run a command on a single line placing the semicolon between
   each command.

# - The command number. Allows a word beginning with # and all remaining characters on that line to be ignored.

