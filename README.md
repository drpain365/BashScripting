# BashScripting


_**Quick Nutshell:**__

Bash is the language of the terminal and programming it basically means executing a bunch of terminal commands.

A .sh (bash) file with the contents:
```
  cat /etc/passwd
  ls
  clear
```
will execute those commands in that exact order. And will yield nothing because of the ```clear``` command at the end.

but a file with the contents:
```
  cat /etc/passwd
  ls
```
will print the contents of the ```/etc/passwd``` file and the results of ```ls```

What you should take away from this:

**Bash will show you the results of your commands executed top to bottom.**
