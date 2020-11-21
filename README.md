# Fork of st

Find the original sources [here](https://git.suckless.org/st)

Includes the following patches:
- st-alpha-0.8.2.diff
- st-anysize-20201003-407a3d0.diff
- st-clipboard-0.8.3.diff
- st-desktopentry-0.8.2.diff
- st-ligatures-alpha-scrollback-20200430-0.8.3.diff
- st-netwmicon-0.8.4.diff
- st-scrollback-20200419-72e3f6c.diff

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

