# The Simple Guide to Software Development

_Software development concepts explained simply._

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/siowyisheng/simple-software-development/blob/master/LICENSE) ![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

## Table of Contents <!-- omit in toc -->

1. [Software Development](#software-development)
2. [The Web](#the-web)
3. [Data](#data)
4. [Computing](#computing)
5. [Documentation](#documentation)
6. [Tests](#tests)
7. [Profiling](#profiling)
8. [Languages](#languages)
9. [Bootstrap](#bootstrap)
10. [Javascript](#javascript)
11. [Python](#python)
12. [Text Editors / IDEs](#text-editors--ides)
13. [Git](#git)
14. [Github](#github)
15. [Unix](#unix)
16. [Docker](#docker)
17. [Jobs](#jobs)
18. [Ways](#ways)
19. [Licensing](#licensing)

- [Glossary - Coding and computing in general](#glossary---coding-and-computing-in-general)
- [Glossary - Operating systems](#glossary---operating-systems)
- [Glossary - Hardware](#glossary---hardware)
- [Glossary - Security and encryption](#glossary---security-and-encryption)
- [Glossary - Images](#glossary---images)
- [Glossary - The Web](#glossary---the-web)
- [Glossary - Linux](#glossary---linux)
- [Glossary - Git](#glossary---git)

## Software Development

### What is software development?

Creating computer programs.

This involves writing, testing, debugging and maintaining [code<sup>?↗</sup>](#what-is-code).

### What is code?

Code is instruction for a computer, written in a programming language.

It is usually written in a [text editor<sup>?</sup>](#what-is-a-text-editor) or [IDE<sup>?</sup>](#what-is-an-ide), which can be downloaded free.

### What are the different types of software?

Computers can store information, create video, graphics or music, run games, make movements (through embedded systems), make predictions, solve problems and communicate with other computers. Software development is telling the computer how to do these things.

Some common software development fields are:

- Web development
- Desktop app development
- Mobile app development
- Game development
- Embedded systems / Robotics
- Internet of things
- Natural language processing
- Machine learning
- Image processing
- Computer vision
- Big data
- Cryptography
- Security hacking
- Operating systems

### What programming languages should I learn?

A good programming language to learn (1) allows you to do what you want to do, (2) has a lot of community support, ie. it's popular.

Regarding (1), different systems use different languages for their software. Mac and iOS apps are written in Swift. C# is a popular language for writing Windows apps. C, C++, Rust are popular for embedded systems. Python is popular for machine learning. It's best to read about the different domains in programming to decide what you want to do, and then find the language(s) most suitable for that purpose.

A language's popularity is important because developers build tools for the languages that they use, and popular languages have more and better tools. For example, Javascript is known mainly for being the language of the web, but because the web is so popular and important, Javascript is also really popular, and great tools for Machine Learning have also been developed for Javascript.

### What is Stack Overflow?

The main question and answer website used by software developers.

### What is open source?

### What are dependencies?

Code that code **imports**(depends on). This includes code written by us, standard library packages, or third-party packages.

### What is a dependency tree?

The [dependencies<sup>?</sup>](#what-are-dependencies) for some code, together with the dependencies of those dependencies and so on. The dependency tree needs to be **resolved** so that suitable versions are determined for installation.

### What is a function signature?

A definition of the name, [parameters<sup>?</sup>](#what-is-a-parameter-or-argument) and [return values<sup>?</sup>](#what-is-a-return-value) (and their types) of a function.

In [Python<sup>?</sup>](#what-is-python), a function signature can look like this:

```python
def write_readme(repo: str, length: int) -> bool:
```

The function name is `write_readme`, the first argument is a [string<sup>?</sup>](#what-is-a-string), the second argument is an [integer<sup>?</sup>](#what-is-an-integer) and it returns a [boolean<sup>?</sup>](#what-is-a-boolean).

### What is a string?

A sequence (string) of [characters<sup>?</sup>](#what-is-a-character). In many programming languages, strings are surrounded by double quotes like `"cow"` or single quotes like `'cat'` or sometimes backticks like `` `dog` ``.

### What is a character?

A character is any letter (like `'g'`), number (like `'5'`), space (`' '`), punctuation mark (like `'.'`), or symbol (like `'\'`) that can be typed on a computer.

### What is an integer?

A positive or negative number (like `42`) without decimal places. An integer holds mathematical meaning, and so is different from the string representation of the integer, which has no mathematical meaning.

### What is a boolean?

A type of data with only two possibilities. One represents a true value, and the other, false.

In [Python<sup>?</sup>](#what-is-python), they are written as `True` and `False` while in [Javascript<sup>?</sup>](#what-is-javascript) they are written as `true` and `false`.

### What is a function or method?

Some lines of code. It can take in inputs known as [parameters<sup>?</sup>](#what-is-a-parameter-or-argument) and spit out output known as [return values<sup>?</sup>](#what-is-a-return-value) when it finishes.

### What is a parameter or argument?

An input to a function. The function should use the input in its code.

Technically, an argument is the data passed into the function's parameter.

### What is indirection?

Referencing something using a name instead of the value itself. Also called `dereferencing`.

### What is type introspection?

Checking the type or properties of an object when code is run.

For example, in Python, `dir(pig)` lists every name in `pig`'s [namespace<sup>?</sup>](#what-is-a-namespace) and `type(cat)` returns `cat`'s type.

### What is a namespace?

### What is object-oriented programming?

A [programming paradigm<sup>?</sup>](#what-is-a-programming-paradigm) using "objects", which have attributes and methods. In most languages, objects are instances of [classes<sup>?</sup>](#what-is-a-class).

### What is boilerplate?

### What is a hook?

A place in packaged code to insert custom code.

### What is a programming paradigm?

### What is a driver?

### What is thread-safe?

### What is connection-pooling?

### What is character encoding?

### What is a class?

A custom [data type<sup>?</sup>](#what-is-a-data-type). It defines what an object (ie. instance) of that class should have as attributes or methods.

### What is a data type?

### What is tightly coupled code? What is loosely coupled code?

### What is idempotence?

When an idempotent function is run multiple times on an input, only the first run changes the input.

### What is a return value?

An output for a function, passed to the code which called the function.

### What is integration?

Making two systems work together.

### What is string interpolation?

### What is YAGNI?

The idea that software shouldn't be built until it becomes necessary.

This has parallels to idea of JIT(Just-in-time) in manufacturing.

_Short for: You Aren't Gonna Need It._

### What is Extreme Programming?

## The Web

### What is Docker?

### What are Containers?

Containers offer a logical packaging mechanism in which applications can be abstracted from the environment in which they actually run. This decoupling allows container-based applications to be deployed easily and consistently, regardless of whether the target environment is a private data center, the public cloud, or even a developer’s personal laptop. Containerization provides a clean separation of concerns, as developers focus on their application logic and dependencies, while IT operations teams can focus on deployment and management without bothering with application details such as specific software versions and configurations specific to the app.

For those coming from virtualized environments, containers are often compared with virtual machines (VMs). You might already be familiar with VMs: a guest operating system such as Linux or Windows runs on top of a host operating system with virtualized access to the underlying hardware. Like virtual machines, containers allow you to package your application together with libraries and other dependencies, providing isolated environments for running your software services. As you’ll see below however, the similarities end here as containers offer a far more lightweight unit for developers and IT Ops teams to work with, carrying a myriad of benefits.

source: https://cloud.google.com/containers/

### What are Client-Side Rendering and Server-Side Rendering?

### What is Universal Javascript?

apps where JavaScript runs on both client and server. This is great both for performance in first-page load and SEO purposes, as we'll see in a moment.

isomorphism.

### What is pre-rendering?

Store cached version of pages.

### What is a server?

### What is a browser?

### What is Prettier?

### What is minifying?

### What is uglifying?

### What is compression?

### What is bundling?

Combining modules, css, images, fonts and other static assets into a single file.

### What is transpiling?

Translating ES6+ Javascript back to ES5 for compatibility with older browsers.

### What is linting?

Statically analyzing code for style and logical errors.

### What is a live server?

A development server that watches files, recompiles and auto-reloads as they change.

### What is a service worker?

Something that sits between your device and the web, that redirects you to your cache when the network is poor. It only helps for the second load onwards.

It makes web apps behave more like native apps.

### What is workbox?

A collection of libraries for PWA development.

### What is a native app?

### What is a path?

### What is a slug?

### What is HTTPS?

Having a secure connection. The user can trust that the site is owned by the proper owner, that no one has tampered with the page and that no one is listening in on the connection.

### What is SSH?

Remotely accessing another computer, often using an [ssh key<sup>?</sup>](#what-is-an-ssh-key).

```bash
ssh -i deployment_key.txt demo@192.237.248.66
```

```bash
# to copy a file
scp file.txt 10.10.10.10:/root/

# to copy a folder
scp -r foldername 10.10.10.10:/root/
```

### What is an SSH key?

A two-key system that authenticates a user for SSH. It often uses the RSA algorithm.

### What is a Web App Manifest?

A configuration file to determines how the app behaves and looks on mobile.

### What is a Progressive Web App?

Push notifications, placement on the home screen, service worker, opens as a separate app.

Removes high-friction step of getting users to install a native app.

Opens reliably, user never sees a network error.

Use Lighthouse to check if an app meets the requirements of a Progressive Web App.

### What is Lighthouse?

### What is Redux?

### What is an API?

### What is the DOM?

### What are routes?

### What is lazy-loading?

### What is chunking?

### What is code splitting?

### What is a CDN?

### What is nginx?

Open source software for web serving, reverse proxying, caching, load balancing, media streaming and more.

nginx [engine x] is an HTTP and reverse proxy server, a mail proxy server, and a generic TCP/UDP proxy server, originally written by Igor Sysoev.

https://nginx.org/en/

### What is Apache?

### What is uWSGI?

A fast, self-healing application container server.

### What is mod_wsgi?

### What does “sudo apt-get update” do?

https://askubuntu.com/questions/222348/what-does-sudo-apt-get-update-do

### What are CSRF attacks?

### What is a Virtual Machine?

### What is a hypervisor?

### What is GraphQL?

GraphQL is a modern way to write and execute API queries.

[The Simple Guide to GraphQL](https://github.com/siowyisheng/simple-graphql)
[GraphQL docs](https://graphql.github.io/learn/)

### What is Webpack?

A popular Javascript bundler.

### What is chunking?

### What is server-side programming?

The code that is run on the computer serving the web app to users. It usually includes the business logic for the application and the code to interact with the database (if any). ! TO IMPROVE !

### What are some free APIs for exploring?

https://randomuser.me/ is a good one.

### What are some good free resources for learning?

- [Google networking course](https://www.coursera.org/learn/computer-networking)

## Data

### What is data?

Information.

### What is scalar data vs vector data?

Scalar data has a single value. For example, the number 5 is scalar.

Vector data can have any number of values. For example, a list of two numbers 4 and 6 is vector.

### What is Microsoft Access?

A proprietary DBMS for Windows.

### What is analog data?

Data stored electrically or in some tactile form.

### What is digital data?

Data stored in 0s and 1s.

### What is a csv file?

A human-readable file format for data in rows and columns.

### What is a Database Management System(DBMS)?

A way to store a lot of data efficiently.

### What is an ORM?

### What is MySQL?

A free relational database management system.

### What does it mean to 'query' something?

To get data from (something).

### What is SQL?

A way to select data from a database management system. aka Structured Query Language.

## Computing

### What is computing about?

Computing cares about two things: Speed(time efficiency) and memory efficiency. Computing problems can be solved in many ways, but the field strives towards time- and memory-efficient solutions.

## Documentation

### What is documentation?

It's the manual for a software.

### How do you write Python documentation?

A good way is to use Sphinx and write it in reStructuredText(.rst). Some documentation can be generated automatically from your docstrings using Sphinx's autodoc and [napoleon](http://www.sphinx-doc.org/en/master/usage/extensions/napoleon.html#module-sphinx.ext.napoleon).

### How do you write reStructuredText(.rst)?

It's like Markdown([cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)) but with:

- [Directives](http://docutils.sourceforge.net/docs/ref/rst/directives.html)
- [Definition Lists](http://docutils.sourceforge.net/docs/user/rst/quickref.html#definition-lists)
- [Different code block formatting syntax](http://docutils.sourceforge.net/docs/user/rst/quickref.html#literal-blocks)
- [Sections instead of h1,h2,h3](http://docutils.sourceforge.net/docs/user/rst/quickref.html#section-structure)
- [Document title and subtitle](http://docutils.sourceforge.net/docs/user/rst/quickstart.html#document-title-subtitle)
- [Different image syntax](http://docutils.sourceforge.net/docs/user/rst/quickstart.html#images)

[A primer](http://docutils.sourceforge.net/docs/user/rst/quickstart.html)
TODO

## Tests

### What are tests?

Tests are functions separate from your software, which tell you whether your code works the way it's supposed to.

Tests have 3 or 4 parts.

1. Setup the test.
2. Exercise the test function.
3. Assert the expected results.
4. Teardown the test.

### What are some common testing pitfalls?

Tests should test inputs from the public interface and returns to the public interface.

TEST YOUR API. THAT IS YOUR BEHAVIOR. DON'T TEST YOUR INTERNAL FUNCTIONS.

For every internal function in your software, the set of possible valid input to the function is larger than the set your software is actually going to pass to the function.
This is obvious but important.

### What are the main types of tests?

**Unit tests** test functions. They only test the code that is being tested, also known as CUT(Code Under Test), and nothing else. They are fast and any interaction with outside systems is [mocked or stubbed](https://martinfowler.com/articles/mocksArentStubs.html).
**Functional tests**(or acceptance tests, UI tests, systems tests) simulate user behavior on the software as a whole from the perspective of the user.

### Why write tests? Why not just run the code and test it manually?

1. Software can have too many functions to test manually.
2. Software can have too many test cases to test manually.
3. Written tests can run more quickly than manual testing.
4. Even if you find something wrong, running the code does not tell you exactly which functions are not working correctly. Unit tests tell you exactly which function fails.
5. Written tests can be executed automatically without human attention with CI/CD tools and tools like pytest-watch.
6. Written tests can be run by others collaborating with you, so that they can contribute code while being confident of not breaking existing functionality.
7. Written tests can be run by users(or potential buyers) of your code, to ensure that your code works as advertised.

### What is a mock, stub or spy?

**Stubs override a function/object** and provide canned answers to calls made during the test. Their purpose is to allow you to run your test.

**Mocks are stubs with in-built tests**. They specify expectations of how the mock is called. This can include with what arguments, how many times, and what was returned.

**Spies do not override functionality**. They record how the spied functions were called.

However, definitions vary between systems.

[source](https://martinfowler.com/articles/mocksArentStubs.html)

[source 2](https://stackoverflow.com/questions/3459287/whats-the-difference-between-a-mock-stub/17810004#17810004)

### What is monkey patching?

Changing the code at runtime, often to isolate code for testing.

### How do I write tests for Python?

Pytest is the most popular testing framework. Learn how to use it [here](https://docs.pytest.org/en/latest/getting-started.html).

### What is tox?

A testing tool that tests code against different Python versions.

### How do I write tests for JavaScript?

Mocha is the most popular framework. Learn to use it [here](https://mochajs.org/#getting-started). Other tools to use with it are Chai and Sinon.

### What is CI/CD?

### What is Continuous Integration?

### What is Continuous Delivery?

### What are the most important CI/CD technologies?

[CircleCI](https://circleci.com/) is recommended for small projects for fast setup.

[TravisCI](https://travis-ci.org/) is recommended for open-source projects for testing in different environments.

[Jenkins](https://jenkins.io/) is recommended for the big projects for customizations. You need to setup your own server.

## Profiling

### What is Profiling?

Measuring the speed and memory cost of a program.

### How do I do profiling in Python?

```python
# for short snippets
>>> import timeit
>>> timeit.timeit('"-".join(str(n) for n in range(100))', number=10000)
0.3018611848820001

# for functions/programs runnable independently
>>> import cProfile
>>> cProfile.run('my_function_to_profile()', globals(), locals())

# for functions run within another system
from profilehooks import coverage, profile, timecall

@coverage # for looking at line coverage
@timecall # for just timing
@profile # for full profiling
def my_function():
    ...
```

```bash
$ python3 -m timeit '"-".join(str(n) for n in range(100))'
10000 loops, best of 5: 30.2 usec per loop
```

## Languages

### What is JSON?

A popular language for storing data. Learn it [here](https://learnxinyminutes.com/docs/json/).

### What is YAML?

A very readable language for storing data, which allows comments. Learn it [here](https://learnxinyminutes.com/docs/yaml/).

### What is TOML?

**Tom's Obvious, Minimal Language** is a language for configuration files. Learn it [here](https://github.com/toml-lang/toml).

### What is Markdown?

A way to write formatted text.

### What is reStructuredText(rst)?

A fancier way to write formatted text.

### What is C#?

A programming language commonly used writing windows apps.

### What is C++?

A programming language commonly used for computing performance and embedded systems.

### What is Java?

A programming language that can be easily deployed on many types of computers.

### What is Javascript?

### What is Python?

An easy programming language to learn. It is commonly used for data work and [server-side programming](#what-is-server-side-programming).

### What is a programming paradigm?

A set of features about a programming language.

### What is php?

A programming language commonly used for server-side programming.

### What is Ruby?

A high-level, clean programming language, commonly used for web development.

### What is Rust?

### What is a scripting language?

[wiki](https://en.wikipedia.org/wiki/Scripting_language)

### What is a statically-typed language?

[overflow](https://stackoverflow.com/questions/2690544/what-is-the-difference-between-a-strongly-typed-language-and-a-statically-typed)

### What is a strongly-typed language?

[overflow](https://stackoverflow.com/questions/2690544/what-is-the-difference-between-a-strongly-typed-language-and-a-statically-typed)

### What is a weakly-typed language?

[overflow](https://stackoverflow.com/questions/2690544/what-is-the-difference-between-a-strongly-typed-language-and-a-statically-typed)

## Bootstrap

### How do I center an image?

```html
<img class="center-block" src="logo.png" />
```

## Javascript

### What is Javascript used for?

Primarily front-end(with jQuery/React/Angular/Vue) and back-end(with MongoDB/Express/Node) app development. However, it can also do many other things like machine learning, data visualization and more.

## Python

### What is Python used for?

Primarily data work(Data Science, Data Analysis, Data Visualization), working with [natural language](https://en.wikipedia.org/wiki/Natural_language_processing) and back-end web development. However, it can also do many other things like desktop app development, image manipulation and more.

### What is 'Pythonic' code?

Code that is clear, concise and follows conventions of the Python community.

### How do I create 'requirements.txt'?

`requirements.txt' is a common way to log dependencies used in a project. You can create it with:

```bash
pip freeze > requirements.txt
```

### What is a decorator?

A way to extend functions.

```python
# defining a decorator
def timeit(func):

  def wrapper(*arg):
      t = time.clock()
      res = func(*arg)
      print(func.func_name, time.clock() - t)
      return res

  return wrapper

# this prints the runtime of function when it is run
@timeit
def myFunction(n):
    ...
```

### How do I check if a substring exists within a string?

```python
'star' in 'star wars'
# returns True
```

### How do I save the requirements of my current project?

```bash
pip freeze > requirements.txt
```

### How do I write a docstring?

[overflow](https://stackoverflow.com/questions/3898572/what-is-the-standard-python-docstring-format)

### How do I remove all .pyc files in my project?

```bash
find . -name '*.pyc' -delete
```

### What does if **name** == “**main**”: do?

It protects code from being run when imported. The code within the `if __name__ == “__main__”:` only runs when the file is directly run instead of also when it is imported.

### How can I run a shell command within Python?

This runs `ls -l` in the shell:

```python
from subprocess import call
call(["ls", "-l"])
```

### How do I merge two dictionaries?

```python
# in place
dict1.update(dict2)

# returned (for python > 3.4)
dict_merged = {**dict1, **dict2}
```

### How do I safely create a nested directory?

```python
import pathlib
pathlib.Path('/my/directory').mkdir(parents=True, exist_ok=True)
```

### How do I create a list of all files in a directory?

```python
from os import listdir
from os.path import isfile, join
onlyfiles = [f for f in listdir(mypath) if isfile(join(mypath, f))]
```

### How do I check if a list is empty?

Empty lists evaluate to `False`.

```python
if not my_list:
  print("List is empty")
```

### How do I access the count within a for loop?

```python
for index, value in enumerate(my_list):
  print(index, value)
```

### What is duck typing?

### How do I check the type of an object?

```python
# returns the type of the object
type(a)

# checks for type inheritance
isinstance(a, SomeType)
```

### Does Python have a ternary operator?

Yes. `a if condition else b` returns a if condition evaluates to True, else b is returned.

### What does the “yield” keyword do?

It's a word [generators<sup>?</sup>](#what-are-generators) use.

### What are generators?

They are like lists, but they generate their elements only when we need them, saving us memory and time.

### What are metaclasses in Python?

A metaclass is a custom type of class.

### How do I show print messages when running pytest?

```bash
py.test -s my_test.py
```

### Should my classes inherit from `object`?

`class MyClass(object):` is used for Python 2 compatibility. If this is not important, use `class MyClass:` instead.

### What are type hints?

Optional notes which add code clarity by specifying the intended types for variables and function definitions. Static analysis tools like mypy can also catch type errors in code before it is run. Some text editors and IDEs can also provide type information during code completion when type hints are provided.

Since they are optional, only add them as necessary. They are especially useful for [function signatures<sup>?</sup>](#what-is-a-function-signature).

Use `# type: ignore` to ignore a mypy error, but first check that it's actually an error.

### How do I use type hints?

[Learn it here.](https://mypy.readthedocs.io/en/latest/cheat_sheet_py3.html#functions)

```python
from typing import Dict, Tuple, List, Callable, Mapping, Sequence, Iterable, Any, IO, NoReturn, Union, Optional

def null_aware_func(x: Optional[float]) -> Optional[float]:
    if x is None:
        return None
    return 2.2*x**1.05
```

### Should I group my pytest tests into classes?

There are pros and cons.

Module-level tests have omit the meaningless `self` argument and are flatter.

Grouping tests into classes(one class per class tested in the module) allows us to use the same test name when two classes have the same function name to be tested. It also forces us to group our tests by the class they are testing (and also enables automatic grouping using a text editor).

### What are magic methods/dunders?

### Should I use Mock or MagicMock when mocking?

[The docs](https://docs.python.org/dev/library/unittest.mock.html) recommend to use MagicMocks by default. It saves time defining magic methods.

A MagicMock is just Mock with [magic methods<sup>?</sup>](#what-are-magic-methodsdunders) which don't raise exceptions.

```python
>>> int(Mock())
TypeError: int() argument must be a string or a number, not 'Mock'
>>> int(MagicMock())
1
>>> len(Mock())
TypeError: object of type 'Mock' has no len()
>>> len(MagicMock())
0
```

### Glossary - Python

- **argument parameter** - Input.
- **attribute** - Feature, property.
- **boolean** - A value which is either True or False.
- **class** - A custom type.
- **comprehension** -
- **dictionary** -
- **element** - Item.
- **float** - Number with a decimal point.
- **for loop** - A way to run some code multiple times.
- **function** - A bunch of code.
- **generator** - An object that can be looped over, without being run first.
- **generator function** - A function used to create generators, just like classes are used to make class instances.
- **if statement** -
- **index** - Address.
- **iterable** - An object you can loop over.
- **library module** - Someone else's code(usually).
- **key/value** -
- **list** -
- **list slice** -
- **method** - A function, owned by a type. For example, strings have a `.format` method.
- **return value** -
- **standard library** - Someone else's code, pre-installed with python.
- **string** -
- **variable** -
- **while** -
- **write** - To write to a file is to create the file.
  decorators
  context managers
  descriptors
  import hooks
  metaclasses
  AST transformations
  pythonic/idiomatic
  zen of python

* **append** - Add to the back.
* **instantiate** -

## Text Editors

### Text Editors / IDEs

### What is a text editor?

### What is an IDE?

It is like Notepad (on Windows) or Notes (on Mac). It allows us to type and save code as plain text.

### What is an IDE?

A text editor with many tools to help development.

_Short for: integrated development environment._

### VSCode

### Atom

### What are some useful regex for find and replace?

- ^\s.\*\n selects all lines which start with a whitespace character.
- You can replace selections with an empty string to delete the selections.

## Git

### What is Git?

A version control system. It helps collaboration, works as a form of backup, and more.

### Github

### What is Github?

A place to store code, which integrates well with [git<sup>?</sup>](#git).

## Unix

### What is Unix?

An operating system, like Windows or MacOS.

### Why is Unix important?

MacOS terminal is based on Unix. Webservers mainly use Unix. We can interact with the computer filesystem more efficiently with some useful Unix commands.

### What is a Makefile?

A file that lets you compile a program from source code. [This is a good explanation.](https://opensource.com/article/18/8/what-how-makefile)

### How to delete a folder?

```bash
rm -rf my_folder
```

### How to clean up the disk?

```bash
sudo ncdu
```

### What are exit codes / return codes?

A number returned to the shell after a program ends. 0 indicates that the program ran successfully. On Unix-like systems, it goes up to 255. On Windows systems, it goes up to 15999.

[Tutorial](https://shapeshed.com/unix-exit-codes/)

### What is POSIX?

### What is bash?

The most important shell. It is the default shell for many operating system distributions.

### What are some common bash commands?

```bash
cd
export
ls
mkdir
rm
mv
cp
touch
cat
grep
```

### How to find a file?

`*` is a wildcard.

```bash
find /home/username/ -name "*.err"
```

### What is an shell/environment variable?

`$ export` shows all shell variables.
Environment variables also often refers to shell variables, but can also refer to variables used by applications other than a shell.

These can be set with `VAR=value`, `export VAR=value` or `env VAR=value`. `value` should use quotes if it's a string.
`export VAR=value` is most common. It's bash-syntax. `VAR=value` doesn't expose the set variable to other programs like `grep`. `env` works like `export` but is a program in itself. (https://askubuntu.com/questions/205688/whats-the-difference-between-set-export-and-env-and-when-should-i-use-each)

### Why don't I need quotes for strings when setting shell variables?

In the `VAR=value` syntax, value is taken to be a string _by default_ when there are no spaces in it. If there are spaces, you need to enclose the string in quotes.

## Docker

### What is docker?

An app that allows the deployment of software in independent containers.

It allows you to build lightweight _containers_ which run apps, from _images_ which are like recipes or blueprints for containers.

An image includes a _Dockerfile_ which are the instructions for part of a stack, and a `docker-compose.yml`, which can run multiple Dockerfiles.

Docker has its own public collection of images called _DockerHub_.

### How do I run a container?

```
docker container run -d -p 8080:80 nginx
// this would download (if not already available) and run an nginx container in the background (because of `-d`), making the container available at port 8080 on the local computer, and exposing port 80 from the container.

docker container run -d -p 3306:3306 --env MYSQL_ROOT_PASSWORD=123456 mysql
```

### What are some common docker commands?

```
// runs a container
docker container run my_image
docker container run -it my_image

// runs a container in the background
docker container run -d my_image

// lists running containers (below are equivalent)
docker container ls
docker ps

// lists all containers (below are equivalent)
docker container ls -a
docker ps -a

// removes a container
docker container rm my_partial_container_id

// stops a container
docker container stop container_name

// lists all local images
docker images

// run and mirror a container directory on the local machine
$ docker container run  -p 80:80 -v $(pwd):/usr/share/nginx/html nginx

// access a running container
$ docker container exec -it nginx bash
```

## Jobs

### What is a developer?

Someone who writes code.

### What do developers do on a day-to-day basis?

### What is a data analyst?

Someone who works primarily with data. This usually involves collecting, manipulating, visualizing and analyzing the data.

### What is a data scientist?

Someone who does machine learning. They often also need to do the work of a data analyst.

## Ways

### What is the principle of least astonishment?

If a necessary feature has a high astonishment factor, it may be necessary to redesign the feature. It is applied to user interface and software design.

### What is Agile?

### What is Test Driven Development(TDD)?

### What is Behavior Driven Development(BDD)?

[source](https://dannorth.net/introducing-bdd/)

### Licensing

### How do I add a license to my software?

Simply copy a LICENSE file to your repo.

### What software licenses should I choose?

[Choose a license](https://choosealicense.com/)

## Glossary - Coding and computing in general

- **What is .net?** - A framework needed for running or writing newer windows apps.
- **algorithm** - A way to do something.
- **api** - The set of instructions that a program understands.
- **atom** - A text editor.
- **authenticate** -
- **batch file** - A script run on windows, usually executing commands like running other programs, copying, moving or renaming files and directories.
- **binary** - An executable file, ie. one that doesn't need to be installed or compiled.
- **compile** -
- **daemon** - A program that runs in the background.
- **data type** - A form of data. Running a function using data of an unintended type is a common source of bugs. Eg, integer, string, object.
- **dynamically-typed** - [overflow](https://stackoverflow.com/questions/2690544/what-is-the-difference-between-a-strongly-typed-language-and-a-statically-typed)
- **embed embedded** - Put into a physical device that is more than just a computer, like a camera, or toy.
- **framework** - A way to do something.
- **github** -
- **hard disk** -
- **high-level** -
- **ide** -
- **interpret** -
- **jre** - A program which runs java programs. aka Java Runtime Environment.
- **keylogger** - A program that records all keys pressed on a computer's keyboard.
- **library** - A bunch of code to help do something.
- **low-level** -
- **manifest file** - A file with data about some other files that it comes together with.
- **markup** -
- **microservice** -
- **rsa** - A public-key encryption technology. (to simplify)
- **parse** - To read.
- **pipeline** -
- **program** - Code that constitutes some system. It is usually compiled.
- **proprietary** - (Usually) A software you have to pay for.
- **script** - Code that references some system. It is usually interpreted.
- **sublime** - A light text editor.
- **syntax** - The grammar for coding something, which needs to be correct for it to work.
- **tests** -
- **vim** - A powerful shell text editor.
- **xml** -

## Glossary - Operating systems

- **absolute path** - A path defined from a fixed point, usually root directory.
- **android** - Google's mobile operating system.
- **directory** -
- **file** -
- **file extension** - The part of the filename after the period. Eg, for 'zen.txt', the extension is 'txt'(or '.txt'). The operating system uses the extension to decide what program to open this file with. Changing the extension of a file doesn't change the actual content of the file.
- **file system** - Something that keeps your files organized. Windows uses NTFS or FAT32(old). Mac uses HFS+ or HFS(old).
- **ios** - Apple's mobile operating system.
- **operating system** -
- **path** - An address for a file or directory. Looks like this ~/Music/iTunes/ or this C:\\My Documents\\zen.txt or this ../../assets/zen.jpg. See **absolute path** and **relative path**.
- **relative path** - A path defined from wherever the current directory is. This usually means it is shorter than a comparable absolute path.
- **shell** -
- **partition** - A part of a hard disk, which can have its own operating system.

## Glossary - Hardware

- **hdmi** - A way to transmit audio and video data in a single cable.
- **parallel port** - A port for an old type of cable.

## Glossary - Security and encryption

- **public key certificate** -
- **public key encryption** - A way to give data safely. A message is encrypted with a public key, and can only be decrypted by the matching private key. (not sure)

## Glossary - Images

- **bitmap raster** - An image made of dots. When the image resolution is insufficient, the image looks blocky and pixellated. Compare with vector.
- **lossless** - A way of compressing data that retains all of the original information. Compare with **lossy**.
- **lossy** - A way of compressing data that loses some of the original information. Most commonly, this happens with jpg images. Compare with **lossless**.
- **vector** - An image made of shapes. It can be scaled infinitely at any resolution. Compare with bitmap/raster.

## Glossary - The Web

- **3g** - A range of technologies which support a mobile data transfer rate of at least 14.4mbps.
- **4g** - A range of technologies which support a mobile data transfer rate of at least 100mbps.
- **802.11** - A family of wifi standards. A bigger suffixing letter(b > a) means a newer standard.
- **access point** - A physical place with wifi access.
- **ajax** - A way for a webpage to update information based on some trigger without loading a new webpage.
- **angular** - A front-end javascript framework.
- **app inventor** - A web-based, simple way to build android apps.
- **applet** - A (usually)java application meant to sent over the web for in-browser use.
- **asp.net** - A Microsoft web framework.
- **aws** -
- **babel** -
- **bandwidth** - The rate that data that can flow through a network connection. It is limited per connection, which is why 10 people downloading files on the same wifi connection causes everyone to slow down.
- **captcha** - A test(usually on the web) designed to block access to programs(bots) but allow human users to pass.
- **client-side** -
- **cms** -
- **css** - A way to describe how web content looks in the browser.
- **dns name server** - A server that translates domain names(like google.com) into ip addresses. It allows us to visit the address of a website just from its name.
- **endpoint** -
- **front-end** -
- **ftp** -
- **full-stack** -
- **html** - A markup language to structure web pages, used with css and javascript.
- **http** -
- **ip address** - The address of a computer on a network. It is a number unique to every computer connected to that network. See **ipv4** and **ipv6**.
- **ipv4** -
- **ipv6** -
- **jquery** - A javascript library to work with the DOM, events, animations and ajax.
- **json web token authentication** -
- **jsp** - A way for a servlet to create web pages dynamically.
- **let's encrypt** - A non-profit organization providing free ssl certificates. [site](https://letsencrypt.org/)
- **mac address** - A number unique to every network device. It is represented by 6 two-digit hexadecimal numbers, like 00:0d:83:b1:c0:8e.
- **mime mime type** - A label used to identify a type of data.
- **network backbone** - A big, ultra-high bandwidth network connection that connects far away places.
  [wiki](https://en.wikipedia.org/wiki/Programming_paradigm)
- **newsgroup** - A forum to meet online and talk about a subject.
- **packet** - A self-sufficient bundle of data sent over a network. It contains(amongst other things) the addresses of the sender and intended recipient.
- **port** -
- **render** - To load and output a template(may be with data) onto a browser.
- **restful api** -
- **root certificates** -
- **ruby on rails** - A full-stack ruby web framework.
- **server-side** -
- **servlet** - A java web backend.
- **ssl certificate** - A way to confirm that you are currently on a certain website. Lacking an ssl certificate doesn't confirm that the website is fraudulent, but it is unprofessional.
- **tls host** -

## Glossary - Linux

- **bash** - A common shell.

## Glossary - Git

- **add** -
- **blame** -
- **commit** -
- **diff** -
- **gitk** -
- **pull** -
- **push** -
- **origin** -
- **repo repository** -
- **remote** -
- **staging** -
- **tracked** -
- **untracked** -

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
