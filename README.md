sublimetext
===========

### Ubuntu install
https://launchpad.net/~webupd8team/+archive/sublime-text-2

https://launchpad.net/~webupd8team/+archive/sublime-text-3

```bash
$ sudo add-apt-repository ppa:webupd8team/sublime-text-2
$ sudo aptitude update
$ sudo aptitude install sublime-text
```

###Configuration steps:
* install Sublime Package Control
* install using PackControl: http://wbond.net/sublime_packages/package_control
 * Soda theme Dark: CTRL+Shift+P (cmd+shift+p (OS X)), install, **Theme Soda** (https://github.com/buymeasoda/soda-theme/)
 * Tomorrow Night color scheme: CTRL+Shift+P, install, **Tomorrow color Schemes** (https://github.com/chriskempson/tomorrow-theme/tree/master/textmate)
 * copy/replace config file: 
 
```bash
$ cd $HOME/.config/sublime-text-2/Packages/User
$ curl -O https://raw.github.com/irakasleibiltaria/sublimetext/master/Preferences.sublime-settings
(mac osx: $HOME/Library/Application\ Support/Sublime\ Text\ 2/Packages/User/)
```

###Shortcuts
https://gist.github.com/eteanga/1736542

http://docs.sublimetext.info/en/latest/reference/keyboard_shortcuts_win.html
```bash
Shift + Command + P: Command Palette
Shift + Command + P, side : toggle side bar

layout: (view->layout)
Shift + alt + 1 : single layout
Shift + alt + 2 : two columns layout
Shift + alt + 8 : two rows layout

crtl + 1: switch to 1 panel 
ctrl + 2: switch to 2 panel
ctrl + shift + 1 : move the current tab to 1 panel
ctrl + shift + 2 : move the current tab to 2 panel
alt + 1 : switch to 1 tab (in the same panel)
alt + 1 : switch to 2 tab

key bindings list:
Preferences->Key Bindings - Default

Command + T: Go to File
Command + R: Go to Symbol
Command + P: Go to Anything
```

###more info
https://medium.com/kr-projects/4f06541322a8

http://robdodson.me/blog/2012/06/23/sublime-text-2-tips-and-shortcuts/

###REPL
https://github.com/wuub/SublimeREPL


###Plugins

Package Control

Sublime Linter

Sublime CodeIntel

kCode and More

Print
https://github.com/n1k0/SublimeHighlight
