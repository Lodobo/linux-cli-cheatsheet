# linux-help-pages
Linux Command line Cheatsheet

## PREVIEW
```sh
curl -sL 'https://raw.githubusercontent.com/Lodobo/linux-help-pages/main/files/help.man' | man -l -
```

## How to use
Download the man page
```sh 
wget -P ~/.local/share https://raw.githubusercontent.com/Lodobo/linux-help-pages/main/files/help.man
```

Create alias in ~/.bashrc
```sh
## Using a local file:
alias h="man ~/.local/share/help.man"

## or fetch from repo:
alias h="curl -sL 'https://raw.githubusercontent.com/Lodobo/linux-help-pages/main/files/help.man' | man -l -"
```
