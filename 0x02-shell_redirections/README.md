Exercis 1: echo Hello, World This script that prints “Hello, World”, followed by a new line to the standard output.
Exercise 2: echo "\"(Ôo)'" This script that displays a confused smiley.
Exercise 3 : cat /etc/passwd This will Display the content of the /etc/passwd file.
Exercise 4: cat /etc/passwd /etc/hosts This will Display the content of /etc/passwd and /etc/hosts.
Exercise 5: tail -n 10 /etc/passwd This will Display the last 10 lines of /etc/passwd.
Exercise 6: head -n 10 /etc/passwd This will Display the first 10 lines of /etc/passwd.
Exercise 7: head --lines=3 iacta | tail --lines=1 This will displays the third line of the file iacta.
Exercise 8: echo "Holberton School" > "\*\\\'\"Holberton School\"\'\\\*$\?\*\*\*\*\*:)" This script will create a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
Exercise 9: ls -la > ls_cwd_content This is a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
Exercise 10: #!/bin/bash
echo -en "" | tail --lines=1 iacta >> iacta This is a script that duplicates the last line of the file iacta.
Exercise 11: find . -name '*.js' -type f -delete This is script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
Exercise 12: find -mindepth 1 -type d | wc -l This is a a script that counts the number of directories and sub-directories in the current directory.

    The current and parent directories should not be taken into account
    Hidden directories should be counted
Exercise 13: ls -t | head This is a script that displays the 10 newest files in the current directory.

Requirements:

    One file per line
    Sorted from the newest to the oldest
Exercise 14: sort | uniq -u This is a script that takes a list of words as input and prints only words that appear exactly once.

    Input format: One line, one word
    Output format: One line, one word
    Words should be sorted
Exercise 15: grep root /etc/passwd This is a script that Display lines containing the pattern “root” from the file /etc/passwd.
Exercise 16: grep -i bin /etc/passwd | wc -l This is a script that Display the number of lines that contain the pattern “bin” in the file /etc/passroExercise 17: grep -C 3 root /etc/passwd This is a script that Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
Exercise 18: grep -v 'bin' /etc/passwd This is a script that Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
Exercise 19: grep '^[[:alpha:]]' /etc/ssh/sshd_config This is a script that Display all lines of the file /etc/ssh/sshd_config starting with a letter.
Exercise 20: tr Ac Ze This is a script that Replace all characters A and c from input to Z and e respectively.
Exercise 21: tr -d cC This is a script that removes all letters c and C from input.
Exercise 22: rev This is a script that reverses its input.
Exercise 23: cat /etc/passwd | cut -d: -f1,6 | sort This is a script that displays all users and their home directories, sorted by users.
Exercise 24: find . -empty -printf "%f\n" This is a command that finds all empty files and directories in the current directory and all sub-directories.

    Only the names of the files and directories should be displayed (not the entire path)
    Hidden files should be listed.
Exercise 25: find . -type f -name \*.gif -printf "%f\n" | LC_ALL=C sort -f | rev | cut -b 5- | rev This is a script that ists all the files with a .gif extension in the current directory and all its sub-directories.

    Hidden files should be listed
    Only regular files (not directories) should be listed
    The names of the files should be displayed without their extensions
    The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)
    One file name per line
    The listing should end with a new line.
