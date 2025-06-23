In some cases you might want to capture the output of a command. 
Previously I wrote about how to declare variables. In this write-up
I will explain how to capture output and store it in a variable.


consider how running "ls" in the bash terminal returns a list of 
the current directory you are in. Well if we create a variable and
declare it equal to ls that will capture the return of ls and store
it in our variable. For example lets create a variable named "files"
and set it capture the output of the command "ls":

    files=$(ls)

Pressing enter now stores the return of ls inside a new variable
named "files". If we now run "echo $files" it returns the list of 
the current working directory we are in.