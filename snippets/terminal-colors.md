Enable color in MAC OS X Terminal
=================================

Edit `.bash_profile`:

```
export PS1='\[\e[1;31m\]\u@\h\[\e[m\]:\[\e[1;34m\]\W\[\e[m\]$ '

export CLICOLOR=1
export LSCOLORS=ExFxBxDxCxegedabagacad
```