# Git config

To use the aliases, you can copy the aliases to one of the git config files (global, user, repository). You can also 'include' the `aliases.gitconfig` file in one of the other configs.


```
; Add this file to git config by adding 
[include]
    path = d:/dir/to/this/file/aliases.gitconfig
```

## Custom commands

To use the custom commands, you have to make sure this directory is included in the PATH environment variable.


## Linux
```
PATH=$PATH:$HOME/bin
```

## Windows
```
set PATH=%PATH%;C:\your\path\here\
set PATH=%PATH%;%CD%
```