# Notes repository

This repository contains some notes on using git.

The file [notes.md](notes.md) contains the main notes. It can be converted to pdf using the command:

```sh
pandoc -o notes.pdf notes.md
```

## Dependencies

In order for the command to work, pandoc and pdflatex have to be installed. This can be done on Ubuntu systems using the command:

```sh
# Update the package list
sudo apt-get update
# Install dependencies
sudo apt install texlive-latex-base texlive-latex-extra texlive-fonts-recommended pandoc
```
