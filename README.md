# install-setup

This script installs my work environment on Debian.

## Usage

```
Argument can be :
        -h : Display usage.
        -d : Setup Debian desktop.
        -v : Setup vim.
        -z : Setup zsh.
        -t : Setup tmux.
        -g : Setup golang env.
```

## Install

```bash
$ ./setup.sh
```

## Todo

- better display
- clossing zsh sesssion :   
       - tilix theme not set when use "su - $user" but after close and open session yes   

- autocompletion ansible :     
       - sudo apt install python3-argcomplete   
       - sudo activate-global-python-argcomplete3   
