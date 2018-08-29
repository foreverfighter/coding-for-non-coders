# coding-for-non-coders

A big list of likely questions from non coders, my answers and some relevant resources.

## Contents

- Coding
- Python
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

## Python

#### How do I write a docstring?

[overflow](https://stackoverflow.com/questions/3898572/what-is-the-standard-python-docstring-format)

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

## Glossary - Coding and computing in general

- **.net?** - A framework needed for running or writing newer windows apps.
- **algorithm?** - A way to do something.
- **api?** - The set of instructions that a program understands.
- **atom?** - A text editor.
- **authenticate?** -
- **batch file?** - A script run on windows, usually executing commands like running other programs, copying, moving or renaming files and directories.
- **binary?** -
- **compile?** -
- **daemon?** - A program that runs in the background.
- **data type?** - A form of data. Running a function using data of an unintended type is a common source of bugs. Eg, integer, string, object.
- **dynamically-typed?** - [overflow](https://stackoverflow.com/questions/2690544/what-is-the-difference-between-a-strongly-typed-language-and-a-statically-typed)
- **embed? embedded?** - Put into a physical device that is more than just a computer, like a camera, or toy.
- **framework?** - A way to do something.
- **github?** -
- **hard disk?** -
- **high-level?** -
- **ide?** -
- **interpret?** -
- **jre?** - A program which runs java programs. aka Java Runtime Environment.
- **keylogger?** - A program that records all keys pressed on a computer's keyboard.
- **library?** - A bunch of code to help do something.
- **low-level?** -
- **manifest file?** - A file with data about some other files that it comes together with.
- **markup?** -
- **microservice?** - 
- **rsa?** - A public-key encryption technology. (to simplify)
- **parse?** - To read.
- **pipeline?** - 
- **program?** - Code that constitutes some system. It is usually compiled.
- **proprietary?** - (Usually) A software you have to pay for.
- **script?** - Code that references some system. It is usually interpreted.
- **sublime?** - A light text editor.
- **syntax?** - The grammar for coding something, which needs to be correct for it to work.
- **tests?** -
- **vim?** - A powerful shell text editor.
- **xml?** -

## Glossary - Operating systems

- **absolute path?** - A path defined from a fixed point, usually root directory.
- **android?** - Google's mobile operating system.
- **directory?** -
- **file?** -
- **file extension?** - The part of the filename after the period. Eg, for 'zen.txt', the extension is 'txt'(or '.txt'). The operating system uses the extension to decide what program to open this file with. Changing the extension of a file doesn't change the actual content of the file.
- **file system?** - Something that keeps your files organized. Windows uses NTFS or FAT32(old). Mac uses HFS+ or HFS(old).
- **ios?** - Apple's mobile operating system.
- **operating system?** -
- **path?** - An address for a file or directory. Looks like this ~/Music/iTunes/ or this C:\\My Documents\\zen.txt or this ../../assets/zen.jpg. See **absolute path** and **relative path**.
- **relative path?** - A path defined from wherever the current directory is. This usually means it is shorter than a comparable absolute path.
- **shell?** -
- **partition?** - A part of a hard disk, which can have its own operating system.

## Glossary - Databases and data

- **access?** - A proprietary dbms for windows.
- **analog?** - Data stored electrically or in some tactile form.
- **csv?** - A human-readable file format for data in rows and columns.
- **digital?** - Data stored in 0s and 1s.
- **dbms? database management system?** - A way to store a lot of data efficiently.
- **mysql?** - A free relational database management system.
- **query?** - To get data from (something).
- **orm?** - 
- **sql?** - A way to select data from a database management system. aka Structured Query Language.

## Glossary - Python

- **append?** - Add to the back.
- **argument? parameter?** - Input.
- **attribute?** - Feature, property.
- **boolean?** - Item.
- **call? run? execute?** - Item.
- **comprehension?** - 
- **class?** - A custom type.
- **dictionary?** - Item.
- **element?** - Item.
- **float?** - To get data from (something).
- **for loop?** - Item.
- **function?** - Item.
- **generator?** - An object that can be looped over, without being run first.
- **generator function?** - A function used to create generators, just like classes are used to make class instances.
- **if statement?** - Item.
- **index?** - Address.
- **instantiate?** -
- **integer?** - To get data from (something).
- **iterable?** - Item.
- **key/value?** - Item.
- **library? module?** - Someone else's code(usually).
- **list slice?** - Item.
- **list?** - Item.
- **method?** - A function, owned by a type. For example, strings have a `.format` method.
- **return value?** - Item.
- **standard library?** - Someone else's code, pre-installed with python.
- **string?** - To get data from (something).
- **variable?** - To get data from (something).
- **while?** - Item.
- **write?** - To write to a file is to create the file.
decorators
context managers
descriptors
import hooks
metaclasses
AST transformations
pythonic/idiomatic
zen of python

## Glossary - Hardware

- **hdmi?** - A way to transmit audio and video data in a single cable.
- **parallel port?** - A port for an old type of cable.

## Glossary - Security and encryption

- **public key certificate?** -
- **public key encryption?** - A way to give data safely. A message is encrypted with a public key, and can only be decrypted by the matching private key. (not sure)

## Glossary - Programming Languages

- **c#?** - A programming language commonly used writing windows apps.
- **c++?** - A programming language commonly used for computing performance and embedded systems.
- **java?** - A programming language that can be easily deployed on many types of computers.
- **javascript?** -
- **paradigm?** - A set of features about a programming language.
- **php?** - A programming language commonly used for server-side programming.
- **ruby?** - A high-level, clean programming language, commonly used for web development.
- **rust?** -
- **scripting language?** - [wiki](https://en.wikipedia.org/wiki/Scripting_language)
- **statically-typed?** - [overflow](https://stackoverflow.com/questions/2690544/what-is-the-difference-between-a-strongly-typed-language-and-a-statically-typed)
- **strongly-typed?** - [overflow](https://stackoverflow.com/questions/2690544/what-is-the-difference-between-a-strongly-typed-language-and-a-statically-typed)
- **weakly-typed?** - [overflow](https://stackoverflow.com/questions/2690544/what-is-the-difference-between-a-strongly-typed-language-and-a-statically-typed)

## Glossary - Images

- **bitmap? raster?** - An image made of dots. When the image resolution is insufficient, the image looks blocky and pixellated. Compare with vector.
- **lossless?** - A way of compressing data that retains all of the original information. Compare with **lossy**.
- **lossy?** - A way of compressing data that loses some of the original information. Most commonly, this happens with jpg images. Compare with **lossless**.
- **vector?** - An image made of shapes. It can be scaled infinitely at any resolution. Compare with bitmap/raster.

## Glossary - The Web

- **3g?** - A range of technologies which support a mobile data transfer rate of at least 14.4mbps.
- **4g?** - A range of technologies which support a mobile data transfer rate of at least 100mbps.
- **802.11?** - A family of wifi standards. A bigger suffixing letter(b > a) means a newer standard.
- **access point?** - A physical place with wifi access.
- **ajax?** - A way for a webpage to update information based on some trigger without loading a new webpage.
- **angular?** - A front-end javascript framework.
- **app inventor?** - A web-based, simple way to build android apps.
- **applet?** - A (usually)java application meant to sent over the web for in-browser use.
- **asp.net?** - A Microsoft web framework.
- **aws?** -
- **babel?** -
- **bandwidth?** - The rate that data that can flow through a network connection. It is limited per connection, which is why 10 people downloading files on the same wifi connection causes everyone to slow down.
- **captcha?** - A test(usually on the web) designed to block access to programs(bots) but allow human users to pass.
- **client-side?** -
- **cms?** -
- **css?** - A way to describe how web content looks in the browser.
- **dns? name server?** - A server that translates domain names(like google.com) into ip addresses. It allows us to visit the address of a website just from its name.
- **endpoint?** -
- **front-end?** -
- **ftp?** -
- **full-stack?** -
- **html?** - A markup language to structure web pages, used with css and javascript.
- **http?** -
- **ip address?** - The address of a computer on a network. It is a number unique to every computer connected to that network. See **ipv4** and **ipv6**.
- **ipv4?** -
- **ipv6?** -
- **jquery?** - A javascript library to work with the DOM, events, animations and ajax.
- **json web token authentication?** -
- **jsp?** - A way for a servlet to create web pages dynamically.
- **let's encrypt?** - A non-profit organization providing free ssl certificates. [site](https://letsencrypt.org/)
- **mac address?** - A number unique to every network device. It is represented by 6 two-digit hexadecimal numbers, like 00:0d:83:b1:c0:8e.
- **mime? mime type?** - A label used to identify a type of data.
- **network backbone?** - A big, ultra-high bandwidth network connection that connects far away places.
  [wiki](https://en.wikipedia.org/wiki/Programming_paradigm)
- **newsgroup?** - A forum to meet online and talk about a subject.
- **packet?** - A self-sufficient bundle of data sent over a network. It contains(amongst other things) the addresses of the sender and intended recipient.
- **port?** -
- **render?** - To load and output a template(may be with data) onto a browser.
- **restful api?** -
- **root certificates?** -
- **ruby on rails?** - A full-stack ruby web framework.
- **server-side?** -
- **servlet?** - A java web backend.
- **ssl certificate?** - A way to confirm that you are currently on a certain website. Lacking an ssl certificate doesn't confirm that the website is fraudulent, but it is unprofessional.
- **tls host?** -

## Glossary - Linux

- **bash?** - A common shell.

## Glossary - Git

- **add?** -
- **blame?** -
- **commit?** -
- **diff?** -
- **gitk?** -
- **pull?** -
- **push?** -
- **origin?** -
- **repo? repository?** -
- **remote?** -
- **staging?** -
- **tracked?** -
- **untracked?** -

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
