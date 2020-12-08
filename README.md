# st
Hello I am Josh Wright and you are currently browsing
my build of suckless st from https://st.suckless.org
which is a simple terminal

If you're Arch-based, you can install this from the AUR
as [st-wrightjjw-git](https://aur.archlinux.org/packages/st-wrightjjw-git/)

## Patches
- [rightclickpaste-0.8.2](https://st.suckless.org/patches/rightclickpaste/)
- [scrollback-20200419](https://st.suckless.org/patches/scrollback/)
- [newterm-0.8.2](https://st.suckless.org/patches/newterm/)

## Original Suckless Readme
```
st - simple terminal
--------------------
st is a simple terminal emulator for X which sucks less.


Requirements
------------
In order to build st you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install


Running st
----------
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

Credits
-------
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.
```

