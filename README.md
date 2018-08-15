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
* Glossary

## Coding

### What is coding?
Coding is giving instructions to a computer in a programming language.

### Why do we code?
Computers can communicate with other computers(through the internet), store, process and output information(and graphics and music), run games, move(through robotics), make predictions and create new information(through machine learning). Coding is telling the computer how to do these things.

Some common coding applications are:
* Software development
* Web development
* Mobile app development
* Game development
* Robotics
* Internet of things
* Natural language processing
* Machine learning
* Image processing
* Computer vision
* Big data 
* Cryptography
* Hacking

### What programming languages should I learn?
A language is good to learn if it has a lot of community support(ie. it's popular) and provides career opportunities. Ideally, it should also be easy to use. 

Support/popularity is important because more tools are developed by developers of popular languages. For example, Javascript is known mainly for being the language of the web, but because the web is so popular and important, Javascript is also really popular, and tools for Machine Learning are also developed for Javascript.

Below are my picks ranked in order. 

1. To do anything web-related, you need to learn **JavaScript**. It's also very very popular.
2. For general purpose programming, **Python** is very popular and easy.
3. Other good languages to learn are **Java**, **PHP** and **C#**, because they are popular.


## Computing

### What is computing about?
Computing is about two aspects of computations: Speed(time efficiency) and storage efficiency. Computing problems can be solved in many ways, but the field strives towards time- and space-efficient solutions.


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

### Atom

### What are some useful regex for find and replace?
* ^\s.\*\n selects all lines which start with a whitespace character.
* You can replace selections with an empty string to delete the selections.


## The Web

### What are SSL certificates/root certificates?


### What are TLS hosts?


### What is JSON Web Token Authentication?


### What are some good free resources for learning?
* [Google networking course](https://www.coursera.org/learn/computer-networking)

     
## Linux

### How do I delete a folder?
`rm -rf my_folder`

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
Environment variables also often refers to shell variables, but can also refer to variables used by applications other than a shell.

These can be set with `VAR=value`, `export VAR=value` or `env VAR=value`. `value` should use quotes if it's a string.
`export VAR=value` is most common. It's bash-syntax. `VAR=value` doesn't expose the set variable to other programs like `grep`. `env` works like `export` but is a program in itself. (https://askubuntu.com/questions/205688/whats-the-difference-between-set-export-and-env-and-when-should-i-use-each)

### Why don't I need quotes for strings when setting shell variables?
In the `VAR=value` syntax, value is taken to be a string *by default* when there are no spaces in it. If there are spaces, you need to enclose the string in quotes.

## Glossary

* Algorithm - A way to do something.
* Bash - 
* Framework - A way to do something.
* Manifest file - A file with data about some other files that it comes together with.
* Shell - 

