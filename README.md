# coding-for-non-coders
A big list of likely questions from non coders, my answers and some relevant resources.

## Contents
* Coding
* Computing
* Programming Languages
* Git
* Text Editors
* The Web
* Linux
* Lingo

## Coding

## Computing

## Programming Languages

## Git

### What are some common commands?
`git diff HEAD~1 HEAD` - View differences between this commit and the previous.

### How do I track the history of a file?
`gitk (filename)` or `git log -p (filename)`.

### How do I overwrite the remote after making a mistake?
`git push --force`

### How do I reset my local branch to copy the remote?
`git reset --hard origin/(your_branch_name)`

## Text Editors

## The Web

### What are some good free resources for learning?
* [Google networking course](https://www.coursera.org/learn/computer-networking)
     
## Linux

### How do I delete a folder?
`rm -rf my_folder`

### What is a shell?

### What is bash?

### What are some common bash commands?
`cd`
`grep`
`export`
`ls`
`mkdir`
`rm`
`mv`
`cp`

### What is an shell/environment variable?
`$ export` shows all shell variables.
Environment variables also often refers to shell variables, but can also refer
to variables used by applications other than a shell.

These can be set with `VAR=value`, `export VAR=value` or `env VAR=value`. `value` should use quotes if it's a string.
`export VAR=value` is most common. It's bash-syntax. `VAR=value` doesn't expose
the set variable to other programs like `grep`. `env` works like `export` but is a program in itself.
https://askubuntu.com/questions/205688/whats-the-difference-between-set-export-and-env-and-when-should-i-use-each

### Why don't I need quotes for strings when setting shell variables?
In the `VAR=value` syntax, value is taken to be a string *by default* when there are no spaces in it. If there are spaces, you need to enclose the string in quotes.

## Lingo

### What is a framework?
A way of doing something.


