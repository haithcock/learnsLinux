    Like other programming languages
  we can also declare variables in 
  Bash.

  1. In bash to create a simple variable we use:
   
    myFirstVariable="This is an example of declaring myFirstVariable as a string."

  2. Boom, we just declared a variable named myFirstVariable. Its a string of text that will return "This is an example of declaring myFirstVariable as a string." if we run the following in our bash shell terminal:

        echo $myFirstVariable

  3. You need to write the "$" symbol when calling your variables otherwise
  you'll just end up printing the string of text after "echo".

    Example:
        echo myFirstVariable 
    Returns:
        myFirstVariable

    Using "$"
        echo $myFirstVariable
    Returns:
        This is an example of declaring myFirstVariable as a string.
