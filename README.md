# BASH

This repo contains everyday usage of bash shell commands, keyboard shortcut keys and more.

# Keyboard Shortcut  
**Working with processes**

Shortcut | Action
---|---
Ctrl-c | Kill current foreground process
Ctrl-z | Suspend current foreground process, Sends a SIGTSTP, use `fg` to bring it back to live
Ctrl-d | Exit bash shell, sends an EOD (End-of-file) marker

**Controlling the screen**

Shortcut | Action
---|---
Ctrl-l | Clear the screen, eqivalent to `clear`
Ctrl-s | Stop all output and pause process
Ctrl-q | Resume output and process

**Working with text on bash**

Shortcut | Action
--- | ---
_Moving Cursor_ |
Ctrl-a / Home | Go to the beginning of the line
Ctrl-e / End | Go to the end of the line
Ctrl-b | Go back one character
Alt-b | Go back one word
Ctrl-f | Go forward one character
Alt-f | Go forward one word
Ctrl-xx | Move between the beginning of the line and the current position of the cursor
_Deleting text_ |
Ctrl-d / Delete | Delete the character under the cursor
Alt-d | delete all characters after the cursor on the current line
Ctrl-h / Backspace | Delete the character before the cursor
_Fixing Typo_ |
Alt-t | Swap current word with previous word
Ctrl-t | Swap the last two characters before the cursor with each other
Ctrl-_ | Undo your last key pressed
_Cut and Pastiong_ |
Ctrl-w | Cut the word before cursor and add to clipboard
Ctrl-k | Cut everything after cursor and add to clipboard
Ctrl-u | Cut everything before cursor and add to clipboard
Ctrl-y | Paste last added
_Capitalizing Characters_ |
Alt-u | Uppercase every character from cursor to the end of current word
Alt-l | Lowercase every character from cursor to the end of current word
Alt-c | Capitalize/Uppercase a character under the cursor and jump to the end of word

**Working with command history**

Shortcut | Action
---|---
Ctrl-p / Up-arrow | Go to the previous command in history
Ctrl-n / Down-arrow | Go to the next command in history
Ctrl-r | Search for a command in history
Ctrl-o / Enter | Run a command, similar to 'Enter'
Ctrl-g | Leave searching mode without running command
Alt-r | Revert changes to a command found in history if you've edited

**Switching between tabs (recommend using tmux)**

Shortcut | Action
---|---
Ctrl-Alt-t | New tab
Alt-1 | Switch to tab 1, change 1 with the corresponding tab number you wish to visit

# Reference  
[link1](https://www.howtogeek.com/howto/ubuntu/keyboard-shortcuts-for-bash-command-shell-for-ubuntu-debian-suse-redhat-linux-etc/)  
