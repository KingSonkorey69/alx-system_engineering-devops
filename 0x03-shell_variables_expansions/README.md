Exercise 0: alias ls="rm *" This is a script that creates an alias.
Exercise 1: echo hello $USER This is a script that prints hello user, where user is the current Linux user.
Exercise 2 : export PATH=$PATH:/action This is a script that adds /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
Exercise 3: echo $PATH | tr -s ':' '\n' | wc -l This is a script that counts the number of directories in the PATH.
Exercise 4: printenv This is a script that lists environment variables.
Exercise 5: set This is a script that lists all local variables and environment variables, and functions.
Exercise 6: BEST="School" This is a script that creates a new local variable.
Exercise 7: export BEST="School" This is a script that creates a new global variable.
Exercise 8: echo $(( 128 + $TRUEKNOWLEDGE )) This is a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
Exercise 9: echo $(( $POWER / $DIVIDE )) This is a script that prints the result of POWER divided by DIVIDE, followed by a new line.
Exercise 10: echo $(( BREATH**LOVE )) This is a script that displays the result of BREATH to the power LOVE.
Exercise 11: echo $(( 2#$BINARY )) This is a script that converts a number from base 2 to base 10.
Exercise 12: echo {a..z}{a..z} | tr ' ' '\n' | grep -v "oo" This is a script that prints all possible combinations of two letters, except oo.
Exercise 13: printf '%.2f\n' $NUM This is a script that prints a number with two decimal places, followed by a new line.

The number will be stored in the environment variable NUM.
Exercise 14: printf '%x\n' $DECIMAL This is a script that converts a number from base 10 to base 16.
Exercise 15: tr 'A-Ma-mN-Zn-z' 'N-Zn-zA-Ma-m' This is a script that encodes and decodes text using the rot13 encryption. Assume ASCII.
Exercise 16: This is a a script that prints every other line from the input, starting with the first line.
Exercise 17: printf '%o\n' $(( 5#$( echo $WATER | tr water 01234) + 5#$( echo $STIR | tr stir. 01234 ) )) | tr 01234567 bestchol This is a  shell script that adds the two numbers stored in the environment variables WATER and STIR and prints the result.
