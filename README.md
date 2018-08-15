# coding-for-non-coders

A big list of likely questions from non coders, my answers and some relevant resources.

## Contents

- Coding
- Computing
- Text Editors
- The Web
- Linux
- Git
- Glossary

## Coding

#### What is coding?

Coding is giving instructions to a computer in a programming language.

#### Why do we code?

Computers can communicate with other computers(through the internet), store, process and output information(and graphics and music), run games, move(through robotics), make predictions and create new information(through machine learning). Coding is telling the computer how to do these things.

Some common coding applications are:

- Software development
- Web development
- Mobile app development
- Game development
- Robotics
- Internet of things
- Natural language processing
- Machine learning
- Image processing
- Computer vision
- Big data
- Cryptography
- Hacking

#### What programming languages should I learn?

A language is good to learn if it has a lot of community support(ie. it's popular) and provides career opportunities. Ideally, it should also be easy to use.

Support/popularity is important because more tools are developed by developers of popular languages. For example, Javascript is known mainly for being the language of the web, but because the web is so popular and important, Javascript is also really popular, and tools for Machine Learning are also developed for Javascript.

Below are my picks ranked in order.

1.  To do anything web-related, you need to learn **JavaScript**. It's also very very popular.
2.  For general purpose programming, **Python** is very popular and easy.
3.  For server-side programming, **PHP** is the most [popular](https://w3techs.com/technologies/history_overview/programming_language) language by far.
4.  Other good languages to learn are **Java**, and **C#**, because they are popular.

## Computing

#### What is computing about?

Computing is about two aspects of computations: Speed(time efficiency) and storage efficiency. Computing problems can be solved in many ways, but the field strives towards time- and space-efficient solutions.

## Text Editors

#### Atom

#### What are some useful regex for find and replace?

- ^\s.\*\n selects all lines which start with a whitespace character.
- You can replace selections with an empty string to delete the selections.

## The Web

#### What are some good free resources for learning?

- [Google networking course](https://www.coursera.org/learn/computer-networking)

## Linux

#### How do I delete a folder?

`rm -rf my_folder`

#### What are some common bash commands?

`cd`
`grep`
`export`
`ls`
`mkdir`
`rm`
`mv`
`cp`

#### What is an shell/environment variable?

`$ export` shows all shell variables.
Environment variables also often refers to shell variables, but can also refer to variables used by applications other than a shell.

These can be set with `VAR=value`, `export VAR=value` or `env VAR=value`. `value` should use quotes if it's a string.
`export VAR=value` is most common. It's bash-syntax. `VAR=value` doesn't expose the set variable to other programs like `grep`. `env` works like `export` but is a program in itself. (https://askubuntu.com/questions/205688/whats-the-difference-between-set-export-and-env-and-when-should-i-use-each)

#### Why don't I need quotes for strings when setting shell variables?

In the `VAR=value` syntax, value is taken to be a string _by default_ when there are no spaces in it. If there are spaces, you need to enclose the string in quotes.

## Git

#### What are some common commands?

`git diff HEAD~1 HEAD` - View differences between this commit and the previous.

#### How do I track the history of a file?

`gitk (filename)` or `git log -p (filename)`.

#### How do I overwrite the remote after making a mistake?

`git push --force`

#### How do I reset my local branch to copy the remote?

`git reset --hard origin/(your_branch_name)`

## Glossary

#### What is ...

- **.net?** - A framework needed for running or writing newer windows apps.
- **ajax?** - A way for a webpage to update information without loading a new webpage.
- **algorithm?** - A way to do something.
- **android?** - Google's mobile operating system.
- **angular?** - A front-end javascript framework.
- **app inventor?** - A web-based, simple way to build android apps.
- **applet?** - A (usually)java application meant to sent over the web for in-browser use.
- **atom?** - A text editor.
- **aws?** -
- **babel?** -
- **bash?** - A common shell.
- **binary?** -
- **c#?** - A programming language commonly used writing windows apps.
- **c++?** - A programming language commonly used for computing performance and embedded systems.
- **client-side?** -
- **cms?** -
- **css?** - A way to describe how web content looks in the browser.
- **csv?** - A human-readable file format for data in rows and columns.
- **dynamically-typed?** - [overflow](https://stackoverflow.com/questions/2690544/what-is-the-difference-between-a-strongly-typed-language-and-a-statically-typed)
- **embed?** - Put in.
- **framework?** - A way to do something.
- **front-end?** -
- **ftp?** -
- **github?** -
- **high-level?** -
- **html?** - A markup language to structure web pages, used with css and javascript.
- **http?** -
- **human-readable?** - Something a human can read, as opposed to binary data understood by computers.
- **ios?** - Apple's mobile operating system.
- **java?** -
- **java?** - A programming language that can be easily deployed on many types of computers.
- **javascript?** -
- **jquery?** - A javascript library to work with the DOM, events, animations and ajax.
- **jre?** - Java Runtime Environment. A program which runs java programs.
- **json web token authentication?** -
- **jsp?** - A way for a servlet to create web pages dynamically.
- **library?** - A bunch of code to help do something.
- **low-level?** -
- **manifest file?** - A file with data about some other files that it comes together with.
- **markup?** -
- **paradigm?** - A set of features about a programming language. [wiki](https://en.wikipedia.org/wiki/Programming_paradigm)
- **php?** - A programming language commonly used for server-side programming.
- **render(web)?** - To load and output a template(may be with data) onto a browser.
- **scripting language?** - [wiki](https://en.wikipedia.org/wiki/Scripting_language)
- **server-side?** -
- **servlet?** - A java web backend.
- **shell?** -
- **ssl certificates/root certificates?** -
- **statically-typed?** - [overflow](https://stackoverflow.com/questions/2690544/what-is-the-difference-between-a-strongly-typed-language-and-a-statically-typed)
- **strongly-typed?** - [overflow](https://stackoverflow.com/questions/2690544/what-is-the-difference-between-a-strongly-typed-language-and-a-statically-typed)
- **sublime?** - A light text editor.
- **syntax?** - The grammar for coding something, which needs to be correct for it to work.
- **tls host?** -
- **vim?** - A powerful shell text editor.
- **weakly-typed?** - [overflow](https://stackoverflow.com/questions/2690544/what-is-the-difference-between-a-strongly-typed-language-and-a-statically-typed)
- **xml?** -

beautifulsoup
bokeh
bootstrap
c#
c++
celery
chrome
cmd
connect
css3
csv module
cypress
django
elixir
express
express
fabric
facebook dev
filezilla
filezilla
fontawesome
fusiontables
git
github
go
google maps api
grunt
gulp
gunicorn
handlebars
haskell
html5
html5
https
illustrator
java
java
javascript
javascript es6
jquery
jquery
json / jsonlint
jupyter notebook
laravel
linux
lisp
lua
mongodb
mongoose
mysql
nodejs
objective c
p5.js
pandas
photoshop
php
prolog
pug
PuTTY
python
qt
react
react native
redis
regex
rest api
ruby
ruby on rails
rust
s3direct
sass
scala
scrapy
sentry/raven
socket.io
sql
sqlite
stripe
sublime
swift
tinydb
tkinkter
vba
vps
webpack
wordpress
xampp
xml
youtube
zinnia
