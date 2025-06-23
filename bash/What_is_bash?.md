
What is bash?

    Bash is an interpreter and command programming language made for UNIX-like operating systems.
    Within the industry bash is refered to as a "Shell". Anytime we open a terminal and run commands we
    are using the shell. The shell lets us enter commands return results of oour actions within the terminal.

    To know what interpreter you are using you can run the following:
        echo $SHELL
    My return was the following:
        /usr/bin/bash
    This confirms I am using bash.

    If I was not using bash I would type the following:
        which bash
    Which in my case returned:
        /usr/bin/bash
              *NOTE this is the default location of where bash is located on my device.
               Most people should have gotten the same return but if not that
               is okay. You most likely moved it somewhere else.
    