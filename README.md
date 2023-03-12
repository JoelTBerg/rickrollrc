# rickrollrc

Bash script which [rickrolls](http://en.wikipedia.org/wiki/Rickrolling) your
terminal by playing Rick Astley’s “Never Gonna Give You Up” with ANSI 256-color
coded UTF-8 characters + audio (if available).

## How to Roll
To start rickrollin’ immediately:

    curl -s -L https://raw.githubusercontent.com/JoelTBerg/rickrollrc/master/roll.sh | bash

Here is the clandestine command you can give to your friends 😈

    curl -s -L https://bit.ly/3J93OL6 | bash

![rickroll in xterm](http://i.imgur.com/ZAsQWtP.png)
![rickroll in mac](http://i.imgur.com/yDLaZna.png)

## Misc.

This has been tested on Debian.

Since this is a colorful hobby, you need to ensure 256-color mode is enabled or
Astley will look sad.

For example, if you use GNU screen, ensure your ~/.screenrc contains something
like:

    termcapinfo xterm 'Co#256:AB=\E[48;5;%dm:AF=\E[38;5;%dm'
    defbce "on"

