A script that displays "Hello World":
#!/bin/bash
echo "Hello, World"

A script that displays the confused smiley("(Ôo)'):
#!/bin/bash
echo "\"(Ôo)'"

A script that displays the content of a given file:
#!/bin/bash
cat <file-path>

A script that displays the contents of two files:
#!/bin/bash
cat <file1-path> <file2-path>

A script that displays the last 10 lines of a given file:
#!/bin/bash
tail -n 10 <file-path>

A script that displays the first 10 lines of a given file:
#!/bin/bash
head -n 10 <file-path>

A script that displays the third line in a given file:
#!/bin/bash
head -n 10 <file-name> | tail -n 1 <file-name>

A script that writes into the file <file-name> the result of the command ls -la:
ls -la | <file-name>

A script that duplicates the last line of a file:
#!/bin/bash
tail -n 1 <file-name> | echo >> <file-name>

A script that deletes  regular JavaScript files only from the current directory and all it's subfolders:
#!/bin/bash
find . -type f -name ("*.js") -exec  rm {} + 

A script that counts the number of directories and subdirectories in the current directory(Excluding the parent and current directories):
find . -mindepth 1 -type d -name("*") | wc -l

A script that displays the 10 newest lines in the current directory:
#!/bin/bash
ls -1t | head

A script that takes a list of words as input and prints only words that appear exactly once(sorted):
#!/bin/bash
sort  | uniq -u

A script that displays lines containing a “pattern” from the file:
#!/bin/bash
grep -w "pattern" <file-path>

A script that displays lines containing the  word “pattern” from the file:
#!/bin/bash
grep -c "pattern" <file-path>

A script that displays the next 3 lines after matching the word "pattern" in file:
#!/bin/bash
grep -A 3 "pattern" <file-name>

A script that displays all lines in a file that do not contain a particular "pattern":
#!/bin/bash
grep -v "pattern" <file-path>

A script that displays only lines in a file that begin with letters(Including Uppercase):
#!/bin/bash
grep '^[[:alpha:]]' <file-path> 

A script that replaces all characters A and c from input to Z and e respectively:
tr 'Ac' 'Ze'

A script that  removes all letters c and C from input.:
#!/bin/bash
tr -d 'Cc' <piped from standard input>

A script that that reverses its input.:
#!/bin/bash
rev <input text - piped from standard input>
