# [Bill Xiong's](http://billxiong.com) [Sublime Text 3](http://www.sublimetext.com/3) Settings
---------------------

[Sublime Text](http://www.sublimetext.com/) is my main editor.

This is the repository for the folder `~/Library/Application Support/Sublime Text 3/Packages/User` on my Mac OS X machine.

## Installation
* [Download][1] and install Sublime Text 3 (dev channel)
* [Install Package Control][2]
* Clone this repository into the Sublime User settings directory:

```sh
git clone git@github.com:bxio/sublime-settings.git ~/Library/Application Support/Sublime Text 3/Packages/User
```

* Restart Sublime Text.

## Environment
I primarily run Sublime on Mac OS X, so most settings are
tailored for that environment. Don't forget to disable the Mission Control Keyboard Shortcuts under System Preferences!

##Keyboard shortcuts based on settings in this repository

###Mac OS X
*Tested in Mac OS X: super == command*

Open/Goto
_________
- SUPER+.: Opens Default (OSX) Keybindings.
- SUPER+SHIFT+P: command panel
- SUPER+P: open project (package: Goto Folder)
- SUPER+O: Clone file (opens a new view of the file)
- SUPER+V: paste and indent

Editing
_________
- SUPER+SHIFT+R: Reindent document
- SUPER+SHIFT+A: Alignment
- SUPER+ENTER: new line (below)
- SUPER+SHIFT+ENTER: new line (above)
- SUPER+SHIFT+T: Reopen last closed tab
- SUPER+Q: duplicate line
- SUPER+J: join lines
- SUPER+L: select entire line
- SUPER+K: Change Quote
- SUPER+V: Paste and Indent

- CTRL+/: soft undo (Jumps to the place you made the edit. Invoke it again to undo the change.)
- CTRL+SHIFT+/: soft redo
- SUPER+SHIFT+Z: redo

- SUPER+R: goto symbol
- SUPER+G: goto line number
- SUPER+M: jump to matching brackets

Selection
_________
- CTRL+W: Move to Beginning of line
- CTRL+E: Move to End of line
- CTRL+S: Move one word forward
- CTRL+A: Move one word back
- CTRL+P: Move up one line
- CTRL+L: Move down one line
- ALT+V: Move one page up
- CTRL+V: Move one page down
Use SHIFT with any of the above to select as well as move.
- SUPER+D: select word. Invoke again to select the next instance of the word.
- CTRL+ALT+[1-9]: Change to Focus Group 1-9.

Comments
_________
- SUPER+/: Toggle line Comment/Uncomment (Single line // comments)
- SUPER+SHIFT+/: Toggle line Comment/Uncomment, (/*Block comments*/)
- CTRL+SHIFT+X: Insert small comment block
- CTRL+SHIFT+C: Insert small comment block
- CTRL+SHIFT+B: Insert small comment block

Behaviour
_________
- SUPER+K+U: uppercase
- SUPER+K+L: lowercase

###Windows
None so far. I don't use Windows.

###Linux
More to come.

[1]: http://www.sublimetext.com/dev "Sublimte Text 3 - Dev Builds"
[2]: http://wbond.net/sublime_packages/package_control/installation "Package Control Installation"
