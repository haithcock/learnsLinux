


    Previously I learned that within a bash terminal/shell/etc
    you can declare variables just like any other programming
    language. In this How_to I will demonstrate how to declare 
    and reference variables within a Bash script.


    1. 
        Lets open up that previous script from the last How_to.
    Mine was called "jesusChrist.sh". Lets add new lines and 
    add some new variables under our previous code where I 
    wrote "Hallowed be thy name."

        1.1  
            We open this script up by typeing
        "nano jesusChrist.sh" and pressing enter
        in our bash terminal.

        1.2
            After we open up the bash terminal 
        and open our script in nano we press enter
        3-5 times after our previous strinng of data.

    2.
        We will create a two new variables and store data in them.

        2.1
            In my jesusChrist.sh script I wrote my 
            first new variable as "theFirstBook".
            I set this ="Genesis".

            If you are following along your nano script
            should look like this:

                    #!/bin/bash
                    echo "Hallowed be thy name."

                    theFirstBook="Genesis"

        2.2
            Lets make our second one and call it "firstEntry"
            If you are following along your nano script
            should look like this:

                    #!/bin/bash
                    echo "Hallowed be thy name."

                    theFirstBook="Genesis"
                    firstEntry="1"

    3.      
        Now lets add a echo/print statement.

            If you are following along your nano script
            should look like this:

                    #!/bin/bash
                    echo "Hallowed be thy name."

                    theFirstBook="Genesis"
                    firstEntry="1"
                    echo "Hello, this is entry number $firstEntry which is the book of $theFirstBook"



