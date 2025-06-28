Just like other progaming languages, Bash also has "if" statements. 

In Bash if statements begin with "if" and end with "fi" to close them.

    For example:

        if 
            /your code here
        fi

If this is your first progamming language
then this is a concept present over most if
not all programmin lanugages in some form.


Here is a more elaborate example in bash.
    
    Example:

    #!/bin/bash

        mynum=200

        if [ $mynum -eq 200]
        then
            echo "the condition is true."
        fi

Steps:

    1. First, in our example we wrote the 
    shebang 

    2. Second, we created a variable and set 
    it equal to 200.

    3. Third, we began the if statement
    by typing "if" then proceeded to
    set our if to check and see
    if the variable "mynum" is equal to 200.

    4. Our fourth step we began the
    "then" portion of our if statement by 
    writing "then" followed by the 
    conditions if "mynum" is equal to 200.

    5. The fifth step we made a print/echo statement 
    based on the true conditions of the if statement.

    6. We closed the if statement by ending with "fi"


