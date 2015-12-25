# tweet-shellgei
Tweet your command line with hashtag "#シェル芸".
(from STDIN)

To get your current command line, you can use below allias:
    alias current-cmdline='history 2 | head -1 | sed "s/^[ ]*[0-9]*[ ]*//g"'

Usage   : current-cmdline | tweet-shellgei
