# Commandbase Patch
A user might have many commands that they wish to execute but the list of "necessary" commands might grow to be too large at some point or even the command itself might be too large to type out everytime

This patch allows the user to bake several commands of any length, along with an alias, and make it searchable in dmenu directly

A sample file has been given (commands.conf) to show how new commands can be defined

In the following example
name=NMTUI
cmds=xterm -e nmtui

This is the output once dmenu_path has been reloaded
![[./nmtui.png]]
