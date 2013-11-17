# [Bill Xiong's](http://billxiong.com) [Sublime Text 3](http://www.sublimetext.com/3) Settings
---------------------
[Sublime Text](http://www.sublimetext.com/) is my main editor. This is just a backup of my settings, so I can sync across multiple machines. I have fine-tuned these to fit best with my workflow, so feel free to use whatever you find in here.

This is the folder `~/Library/Application Support/Sublime Text 3/Packages/User` on my Mac OS X machine.

## Installation
* [Download][1] and install Sublime Text 3 (dev channel)
* [Install Package Control][2]
* Clone this repository into the Sublime User settings directory:

```sh
git clone git@github.com:bxio/sublime-settings.git ~/Library/Application Support/Sublime Text 3/Packages/User
```

* Restart Sublime Text.

## Environment
I primarily run Sublime on Mac OS X, so most settings are tailored for that environment.
Most of my coding is done in Colemak, however, I use Sublime Text on Qwerty as well, so the keybindings are done in such a way to help me work more optimally in both keyboard layouts.
Don't forget to disable the Mission Control Keyboard Shortcuts under System Preferences!

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
- CTRL+W: Move cursor to Beginning of line
- CTRL+E: Move cursor to End of line
- CTRL+S: Move cursor one word forward
- CTRL+A: Move cursor one word back
- CTRL+P: Move cursor up one line
- CTRL+L: Move cursor down one line

Use SHIFT + any of the above keys to select as well as move.

Scrolling and Editing
_________
- ALT+B: Move one page up
- CTRL+B: Move one page down
- ALT+Up: Scroll screen three lines up
- ALT+Down: Scroll screen three lines down
- SUPER+ALT+UP: Add to the selection the line above at the same position
- SUPER+ALT+DOWN: Add to the selection the line below at the same position
- SUPER+D: select word. Invoke again to select the next instance of the word.
- CTRL+ALT+[1-9]: Change to Focus Group 1-9.
- F1: Fold Selection
- F2: Expand Selection
- F3: Add

Jump and Select
_________
- SUPER+;: Go to Definition
- SUPER+F: Incremental Search

Comments
_________
- SUPER+/: Toggle line Comment/Uncomment (Single line // comments)
- SUPER+SHIFT+/: Toggle line Comment/Uncomment, (/*Block comments*/)
- CTRL+SHIFT+X: Insert small comment block
- CTRL+SHIFT+C: Insert small comment block
- CTRL+SHIFT+B: Insert small comment block

Case-changing
_________
- SUPER+K+U: uppercase
- SUPER+K+L: lowercase

###Windows
Mainly just a port from the python IDE workspace. It's not customized as much because I don't code in Windows that often.

###Linux
More to come.

## Custom Icons
I found some lovely replacement icons from [gpopper](http://gpopper.deviantart.com/art/Sublime-Text-Replacement-372504046).
Place these under `Sublime Text.app/Contents/Resources` to see them take effect. Every time you update Sublime Text, you'll have to reimport the icons.

Don't forget to rename the icon you want to take the place of the ugly default icon to `Sublime Text.icns`!



[1]: http://www.sublimetext.com/dev "Sublimte Text 3 - Dev Builds"
[2]: http://wbond.net/sublime_packages/package_control/installation "Package Control Installation"
