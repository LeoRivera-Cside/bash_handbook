# Bash Scripting Anatomy
## Create a script
### Start by creating directory for you new script. Then move into it. 
> mkdir scripts 
> cd scripts

### Inside, Create a new file -the script's name:
> cat > hello.sh

### Insert the following line in the script using your favorite text editor. Save it. 
> echo 'Hello, World!'

### Make your 'hello.sh' file an executable:
> chmod u+x hello.sh

### Run your 'hello.sh' script within bash shell:
> bash hello.sh

### Emphasize the use of bash as your script interpreter entering the following at the start of your script file:
> #! /bin/bash

### Add your shell script to the PATH to run it from any directory:
> pwd (to get the location of your script's directory)
> export PATH=$PATH:/home/user/scripts    (add scripts directory to the PATH directory)

### Alternatively; you can run your script with source (running it within the main processes. This as opposed to creating a subprocess from running your script through Bash):
> source ./hello.sh 

### You can add single line comments in Bash using "#" at the start of the line. Bash does not feature multiline comments. 
> \# This is a Bash comment.
