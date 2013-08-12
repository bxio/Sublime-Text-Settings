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
- COMMAND+.: Opens Default (OSX) Keybindings.
- COMMAND+SHIFT+P: command panel
- COMMAND+P: open project (package: Goto Folder)
- COMMAND+O: Clone file (opens a new view of the file)
- COMMAND+V: paste and indent
- COMMAND+ENTER: new line (below)
- COMMAND+SHIFT+ENTER: new line (above)
- COMMAND+Q: duplicate line
- COMMAND+J: join lines
- COMMAND+L: select entire line

Comments
_________
- COMMAND+/: Toggle line Comment/Uncomment (Single line // comments)
- COMMAND+SHIFT+/: Toggle line Comment/Uncomment, (/*Block comments*/)

Selection
_________
- COMMAND+D: select word. Invoke again to select the next instance of the word.

Behaviour
_________
- COMMAND+SHIFT+Z: redo

- CTRL+/: soft undo (Jumps to the place you made the edit. Invoke it again to undo the change.)
- CTRL+SHIFT+/: soft redo

- COMMAND+R: goto symbol
- COMMAND+G: goto line number
- COMMAND+M: jump to matching brackets

- ALT+UP: goto previous bracket
- ALT+DOWN: goto next bracket
- ALT+SHIFT+UP: select text in bracket
- ALT+SHIFT+DOWN: select text in bracket

- COMMAND+K+U: uppercase
- COMMAND+K+L: lowercase

- COMMAND+F: find in file (F3: jump to next occurence)
- COMMAND+SHIFT+F: find in project (F4: jump to next occurence)

###Windows
None so far. I don't use Windows.

###Linux
More to come.

[1]: http://www.sublimetext.com/dev "Sublimte Text 3 - Dev Builds"
[2]: http://wbond.net/sublime_packages/package_control/installation "Package Control Installation"
