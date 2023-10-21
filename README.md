# linux-help-pages
Linux Cheatsheets

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

## How to contribute or modify.
Use the mandoc command to preview the .mdoc file or to convert it to other formats. Documentation for mandoc cam be found [here](https://mandoc.bsd.lv/man/mandoc.1.html). mdoc files use the mdoc syntax, which is a subset of roff. mdoc is easier to work with compared to roff. Documentation for mdoc syntax can be found [here](https://mandoc.bsd.lv/man/mdoc.7.html).

Preview the mdoc file
```sh
# With mandoc
mandoc help.mdoc

# with man
man ./help.mdoc
```

Convert the mdoc file to a regular manpage
```sh
mandoc -T man help.mdoc > help.man
```


