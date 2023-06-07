A script to display the content of the current directory:
#!/bin/bash
pwd

A script that displays the contents list of the working directory:
#!/bin/bash
ls

A script that changes the current  working directory to a users home directory:
#!/bin/bash
cd ~  OR
#!/bin/bash
cd $HOME

A script that displays the current directory contents in long format:
#!/bin/bash
ls -l

A script that displays the contents of the current directory in long format including the hidden files(files with names beginning with a .):
#!/bin/bash
ls -la

A script that displays the contents of a current directory in long format(including hidden files), displaying user and group IDs in number format:
#!/bin/bash
ls -lan

A script to create a directory(my_first_directory)in a parent directory (/tmp/):
#!/bin/bash
mkdir /tmp/my_first_directory

A script that moves a file from a parent directory to a child directory:
#!/bin/bash
mv /tmp/betty /tmp/my_first_directory

A script that deletes a file from a directory:
#!/bin/bash
rm <file-name or file-relative-path>

A script that deletes a directory:
#!/bin/bash
rmdir <directory name or relative path>

