# st

My fork of st

## patches

-   alpha osc11
-   anysize
-   blinking cursor
-   bold is not bright
-   boxdraw
-   csi 22 23
-   delkey
-   dynamic cursor
-   fix keyboard input
-   font2
-   glyph wide support boxdraw
-   selectionbg alpha
-   selectioncolors
-   title parsing fix
-   undercurl
-   xclearwin
-   live reload of xresources

## Install

        git clone https://github.com/gomfol12/st3.git
        cd st3
        sudo make install

## Live reload

        kill -SIGUSR1 pid_of_st_process

### Live reload all instances of st

        pidof st | xargs -r kill -SIGUSR1

## Configuration and Keybinds

        see config.h

## Thanks

-   [suckless project](https://suckless.org/)
