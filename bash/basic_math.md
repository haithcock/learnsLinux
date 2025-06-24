To enable math functions within bash you need to use the
evaluate expressions command. This is abbreviated as "expr"

    For example:
        running this:
            "30 + 10"
        results in a return of the following:
        "30: command not found"
    
    However
        running this:
            "expr 30+10" 
        results in a return of the following:
             "40"

SUBTRACTION 
    Subtraction works in a similar fashion to addition within bash.

    Just use expr followed by your subtraction equation like so:

        "expr 30-10"
    
    Returns the following:

        "20"

DIVISION
    Division works the same way.

    Use "/" for your division symbol like so:

        "expr 30/3"

    Returns the following:

        "10"


MULTIPLICATION 

    Multiplication is a little different.
    You probably thought "Just use an asterisk (*)"

    You're close. Use "\*" for multiplication like so:

        "expr 30\* 10"

    Returns the following:

        "300"
        