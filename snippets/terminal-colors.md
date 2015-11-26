Enable color in MAC OS X Terminal
=================================

Edit `.bash_profile`:

```
export PS1='\e[31;1m\u@\h\e[0m:\e[34;1m\W\e[0m$ '

export CLICOLOR=1
export LSCOLORS=ExFxBxDxCxegedabagacad
```