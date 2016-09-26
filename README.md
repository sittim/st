#Fork of Simple Terminal

http://st.suckless.org/

$ st - simple terminal

st is a simple terminal emulator for X which sucks less.

#Requirements

In order to build st you need the Xlib header files.

#Installation

Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

```bash
make clean install
```
**Break** - Send a break in the serial line.  Break key is obtained in PC keyboards pressing at the same time control and pause.

**Ctrl-Print Screen** - Toggle if st should print to the iofile.

**Shift-Print Screen** - Print the full screen to the iofile.

**Print Screen** - Print the selection to the iofile.

**Alt-Shift-Page Up** - Increase font size.

**Alt-Shift-Page Down** - Decrease font size.

**Alt-Shift-Home** - Reset to default font size.

**Shift-Insert** - Paste from primary selection (middle mouse button).

**Alt-Shift-Insert** - Paste from clipboard selection.

**Alt-Shift-c** - Copy the selected text to the clipboard selection.

**Alt-Shift-v** - Paste from the clipboard selection.

#Running st

The st terminfo entry with the following command:

    tic -s st.info

See the man page for additional details.

#Credits

Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.
