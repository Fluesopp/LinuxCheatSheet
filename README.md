# LinuxCheatSheet

## Install xbindkeys
```
sudo apt-get install xbindkeys xvkbd
```
  
### Open config in sublime
```
subl ~/.xbindkeysrc
```
  
### Copy paste into file
```
"xvkbd -xsendevent -text '@'"
    Control+Alt + 2

"xvkbd -xsendevent -text '£'"
    Control+Alt + 3

"xvkbd -xsendevent -text '$'"
    Control+Alt + 4

"xvkbd -xsendevent -text '½'"
    Control+Alt + 5

"xvkbd -xsendevent -text '±'"
    Control+Alt + +

"xvkbd -xsendevent -text '{'"
    m:0xc + c:16
    Control+Alt + 7

"xvkbd -xsendevent -text '['"
    m:0xc + c:17
    Control+Alt + 8

"xvkbd -xsendevent -text ']'"
    m:0xc + c:18
    Control+Alt + 9

"xvkbd -xsendevent -text '}'"
    m:0xc + c:19
    Control+Alt + 0

"xvkbd -xsendevent -text '\[backslash]'"
    m:0xc + c:20
    Control+Alt + ssharp

"xvkbd -xsendevent -text '\[asciitilde]'"
    m:0xc + c:35
    Control+Alt + plus
```

### Update xbindkeys
```
xbindkeys -f .xbindkeysrc 
```
