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

5. Create a script that lists environment variables.

	printenv | less

6. Create a script that lists all local variables and environment variables, and functions.

	set | less

7. Create a script that creates a new local variable.

	Name: BEST
	Value: School 


	BEST='School'

8. Create a script that creates a new global variable.

        Name: BEST
        Value: School 

        export BEST='School'

9. Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.

	echo $(($TRUEKNOWLEDGE+128))
