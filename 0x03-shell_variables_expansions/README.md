--- SHELL EXPANSIONS ---

1. Create a script that creates an alias.

	Name: ls
	Value: rm *

	alias ls='rm *'

2. Create a script that prints hello user, where user is the current Linux user

	hello $USER

3. Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program

	export PATH=$PATH:/action

4. Create a script that counts the number of directories in the PATH

	echo $PATH | tr ":" "\n" | wc -l
