# The Simple Guide to Software Development

_Technologies, concepts and terms explained simply._

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/siowyisheng/simple-software-development/blob/master/LICENSE) ![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

## Usage

`Ctrl/Cmd + f` to search for what you're looking for.

Or start at one of these questions.

1. [**What is software development?**](#what-is-software-development)
2. [**What is the web?**](#what-is-the-web)

Internal links are [**bolded**](#usage) and external links are in [_italics_](https://en.wikipedia.org/wiki/Italic_type). Explore through the links or press 'back' to go back to the previous question.

### What is software development?

Creating computer programs.

This involves [**planning out programs**](#how-is-a-program-created), [**writing**](#how-is-code-usually-written), [**testing**](#what-is-code-testing), [**debugging**](#what-is-code-debugging), [**refactoring**](#what-is-code-refactoring), [**documenting**](#what-is-code-documentation) and [**maintaining**](#what-is-code-maintenance) [**code**](#what-is-code).

### What is a computer?

An electronic device for storing and processing [**data**](#what-is-data) according to instructions given to it in programs.

This includes [**mobile devices**](#what-is-a-mobile-device) like smartphones and tablets, as well as laptops, desktops, Raspberry Pis, digital televisions and more.

Different computers use different [**operating systems**](#what-is-an-operating-system).

### What is a mobile device?

Any type of handheld [**computer**](#what-is-a-mobile-device). The most common is the smartphone, but also includes tablets and e-readers.

### What is Raspbian?

The official [**operating system**](#what-is-an-operating-system) of the [**Raspberry Pi**](#what-is-a-raspberry-pi).

### What is a Raspberry Pi?

A low cost, credit-card sized computer that plugs into a computer monitor or TV, and uses a standard keyboard and mouse.

### How is a program created?

After deciding what we want to make, we need to consider what technologies to use (which frameworks, programming languages, platforms). We also need to think about what features to include in the MVP (minimum viable product, ie. most basic first version). We should also do a mockup of what the user will see (if anything) and prepare a timeline for each planned version.

### What is code?

Code is instruction for a computer, written in a programming language. Also called source code.

### How is code written?

Code is usually written in a [**text editor**](#what-is-a-text-editor) like [**vscode**](#what-is-vscode) or [**IDE**](#what-is-an-ide) like [**pycharm**](#what-is-pycharm), which can be downloaded free.

### What is VSCode?

The [_most popular text editor_](https://code.visualstudio.com/) (2019).

### What is PyCharm?

A [_popular IDE_](https://www.jetbrains.com/pycharm/) for [**Python**](#what-is-python) (2019).

### What is code testing?

Running the [**code**](#what-is-code) and making sure it works. If something doesn't work the way it's supposed to, we say there is a [**bug**](#what-is-a-bug) and the code needs to be [**debugged**](#what-is-code-debugging).

Automated tests can be written and run to make the process more efficient, especially for larger programs.

### What is a feature?

Something that a program can do. If the feature doesn't work, there is a [**bug**](#what-is-a-bug).

### What is a bug?

A part of a program which doesn't work as intended. Buggy programs need to be [**debugged**](#what-is-code-debugging).

### What is code debugging?

Fixing [**bugs**](#what-is-a-bug) in programs.

First, we will try to replicate/reproduce the bug, usually in the [**local environment**](#what-is-the-local-environment). Next, we try to understand the cause of the bug, either through hypothesis (guessing the cause), reading logs or reading the relevant [**source code**](#what-is-code). Then, we attempt to fix the bug by editing the code. After the bug is fixed, a regression test may be written to detect if the same bug appears again in future.

### What is code refactoring?

Changing the source code without changing what it does.

Refactoring can make code more performant (faster), use less memory, look more readable and be easier to add on to (more extensible).

### What is code maintenance?

Code maintenance includes fixing bugs in the code as they appear and updating the code to work with current technologies in use so that the program can continue to be used properly.

Maintaining code is also called supporting the code.

### What is deprecated code?

Deprecated code is code which works but is old and not recommended for use.

It may be removed in a future version of the program. Usually, code is deprecated because there is a better alternative available.

### What is the local environment?

The local environment refers to your own computer. Running a website or program locally means running it on your own computer, where it can only be accessed by you.

### What is web development?

[**Creating**](#how-is-a-program-created), [**maintaining**](#what-is-code-maintenance) and improving [**web apps**](#what-is-a-web-app-or-website).

### What is desktop app development?

### What is mobile app development?

### What is game development?

### What are embedded systems?

Putting code into a physical device that is more than just a computer, like a camera, or toy.

### What is the Internet of Things (IoT)?

### What is natural language processing (NLP)?

### What is machine learning?

### What is data science?

### What is image processing?

### What is computer vision?

### What is big data?

### What is cryptography?

### What is security hacking?

### What programming languages should I learn?

A good programming language to learn (1) allows you to do what you want to do, (2) has a lot of community support, ie. it's popular.

Regarding (1), different systems use different languages for their software. Mac and iOS apps are written in Swift. C# is a popular language for writing Windows apps. C, C++, Rust are popular for embedded systems. Python is popular for machine learning. It's best to read about the different domains in programming to decide what you want to do, and then find the language(s) most suitable for that purpose.

A language's popularity is important because developers build tools for the languages that they use, and popular languages have more and better tools. For example, Javascript is known mainly for being the language of the web, but because the web is so popular and important, Javascript is also really popular, and great tools for Machine Learning have also been developed for Javascript.

### What is Stack Overflow?

The [_main question and answer website used by software developers_](https://stackoverflow.com/).

### What is open source code?

Open source code is code that anyone can see. Anyone can copy the code, ask about it, complain about it, comment on it, and make suggested changes (in [**pull requests**](#what-is-a-pull-request)) to it. Also called open-source code.

### What is a pull request?

A request for someone with authority to accept some changes to some [**code**](#what-is-code).

### What are dependencies?

Code that code **imports**(depends on). This includes code written by us, standard library packages, or third-party packages.

### What is a dependency tree?

The [**dependencies**](#what-are-dependencies) for some code, together with the dependencies of those dependencies and so on. The dependency tree needs to be **resolved** so that suitable versions are determined for installation.

### What is a function signature?

A definition of the name, [**parameters**](#what-is-a-parameter-or-argument) and [**return values**](#what-is-a-return-value) (and their types) of a function.

In [**Python**](#what-is-python), a function signature can look like this:

```python
def write_readme(repo: str, length: int) -> bool:
```

The function name is `write_readme`, the first argument is a [**string**](#what-is-a-string), the second argument is an [**integer**](#what-is-an-integer) and it returns a [**boolean**](#what-is-a-boolean).

### What is a string?

A sequence (string) of [**characters**](#what-is-a-character). In many programming languages, strings are surrounded by double quotes like `"cow"` or single quotes like `'cat'` or sometimes backticks like `` `dog` ``.

### What is a character?

A character is any letter (like `'g'`), number (like `'5'`), space (`' '`), punctuation mark (like `'.'`), or symbol (like `'\'`) that can be typed on a computer. Multiple characters make a [**string**](#what-is-a-string).

### What is an integer?

A positive or negative number (like `42`) without decimal places. An integer holds mathematical meaning, and so is different from the [**string**](#what-is-a-string) representation of the integer, which has no mathematical meaning.

### What is a boolean?

A type of data with only two possibilities. One represents a true value, and the other, false.

In [**Python**](#what-is-python), they are written as `True` and `False` while in [**Javascript**](#what-is-javascript) they are written as `true` and `false`.

### What is a function or method?

Some lines of code. It can take in inputs known as [**parameters**](#what-is-a-parameter-or-argument) and spit out output known as [**return values**](#what-is-a-return-value) when it finishes.

### What is a parameter or argument?

An input to a [**function**](#what-is-a-function-or-method). The function should use the input in its code.

Technically, an argument is the data passed into the function's parameter.

### What is indirection?

Referencing something using a name instead of the value itself. Also called `dereferencing`.

### What is type introspection?

Checking the type or properties of an object when code is run.

For example, in Python, `dir(dog)` lists every name in `dog`'s [**namespace**](#what-is-a-namespace) and `type(cat)` returns `cat`'s type.

### What is a namespace?

A space in which names must be unique. Here are a few examples in [**JavaScript**](#what-is-javascript).

Here, `name` is in the global namespace.

```javascript
const name = 'bruno'
```

Here, `name` is in `dog`'s namespace.

```javascript
const dog = {}
dog.name = 'bruno'
```

Here, `name` exists only in the for-of loop's namespace.

```javascript
const names = ['bruno', 'alfred', 'doggo']
for (const name of names) {
  console.log(name)
}
```

### What is object-oriented programming?

A style of programming (programming paradigm) using "objects", which have attributes and methods. In most languages, objects are instances of [**classes**](#what-is-a-class).

### What is boilerplate?

Sections of reusable code meant to be used with few or no changes.

### What is a hook?

A place in packaged code to insert custom code.

This is different from a [**React hook**](#what-are-react-hooks).

### What are React hooks?

Functions in React which allow access to some React API within functional components, without using classes and lifecycle methods.

### What is React?

The [_most popular front-end development framework_](https://reactjs.org/) (2019).

### What is a driver?

Usually, it is some code that allows a device to communicate with an operating system.

It can also refer to a software driver, some code that allows a program to communicate with an operating system in kernel mode.

### What is AWS?

Amazon Web Services, a suite of services for developing web apps.

### What is Kubernetes?

### What is microservice?

### What is OpenShift?

### What is .NET?

Also called dotnet.

### What is Serverless?

### What is Kafka?

### What is Flink?

### What is Spark?

### What is Angular?

### What is a PWA?

A Progressive Web App is a

### What is a thread?

A run of some code. Multiple threads can exist in one process.

### What is multithreading?

Having multiple [**threads**](#what-is-a-thread) at the same time.

### What is implementation?

Implementing a [**feature**](#what-is-a-feature) involves writing it and including it in released code.

### What is thread-safe code?

Code which is safe from [**race conditions**](#what-are-race-conditions) when run in multiple [**threads**](#what-is-a-thread).

### What are race conditions?

An error which happens when multiple [**threads**](#what-is-a-thread) use a shared variable, which is changed by one thread while another thread is checking it.

### What is connection-pooling?

### What is character encoding?

### What is a class?

A custom [**data type**](#what-is-a-data-type). It defines what an object (ie. instance) of that class should have as attributes or methods.

### What is a data type?

### What is tightly coupled code? What is loosely coupled code?

### What is idempotence?

When an idempotent function is run multiple times on an input, only the first run changes the input.

This [**Python**](#what-is-python) code is idempotent. No matter how many times you call it, the end result is that `dogs` is set to `5`, and only the first run did anything.

```python
dogs = 5
```

This code is NOT idempotent.

```python
dogs = dogs + 1
```

`dogs` keeps increasing as we run the code multiple times.

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

### What is the web?

Also called the internet.

### What is a web app or website?

A program that can be accessed with a [**browser**](#what-is-a-browser). It usually requires an internet connection. Web app is the modern term for modern websites. A single web app can serve many [**web pages**](#what-is-a-web-page).

Also called a web application.

### What is a web page?

A page that can be accessed with a [**browser**](#what-is-a-browser). One web page is saved as one html file (and some other supporting files).

### What is a static web page?

A web page that is delivered to the user's web browser exactly as stored, in contrast to dynamic web pages. Also called a static webpage.

### What is an operating system?

A software that manages computer hardware and allows computer programs to run.

### What is a kernel?

### What is Linux?

The [**operating system**](#what-is-an-operating-system) for the vast majority of web servers.

It is one of the three most popular [**operating systems**](#what-is-an-operating-system) for desktop [**computers**](#what-is-a-computer), together with [**Windows**](#what-is-windows) and [**macOS**](#what-is-macos).

### What is Windows?

The [**operating system**](#what-is-an-operating-system) for most non-Apple desktops.

It is one of the three most popular [**operating systems**](#what-is-an-operating-system) for desktop [**computers**](#what-is-a-computer), together with [**Linux**](#what-is-linux) and [**macOS**](#what-is-macos).

### What is macOS?

The [**operating system**](#what-is-an-operating-system) for Apple desktops.

It is one of the three most popular [**operating systems**](#what-is-an-operating-system) for desktop [**computers**](#what-is-a-computer), together with [**Windows**](#what-is-windows) and [**macOS**](#what-is-macos).

### What is Android?

Google's mobile [**operating system**](#what-is-an-operating-system).

### What is iOS?

Apple's mobile [**operating system**](#what-is-an-operating-system).

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

A technology to remotely access another computer, often using an [**ssh key**](#what-is-an-ssh-key).

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

GraphQL is a modern way to write and execute API queries over the internet.

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

### What is PostgreSQL?

### What is DynamoDB?

A [**DBMS**](#what-is-a-database-management-systemdbms) that works easily with [**AWS Lambda**](#what-is-aws-lambda).

### What is MongoDB?

### What does it mean to 'query' something?

To get data from (something).

### What is SQL?

A way to select data from a database management system. aka Structured Query Language.

### What is FaaS?

Functions-as-a-service (FaaS) is a way to deploy services without interacting directly with a server.

### What is AWS Lambda?

FaaS on AWS.

### What is computing about?

Computing cares about two things: Speed(time efficiency) and memory efficiency. Computing problems can be solved in many ways, but the field strives towards time- and memory-efficient solutions.

### What is code documentation?

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

### What is JSON?

A popular language for storing data. Learn it [here](https://learnxinyminutes.com/docs/json/).

### What is YAML?

A very readable language for storing data, which allows comments. Learn it [here](https://learnxinyminutes.com/docs/yaml/). The file extension is `.yml`.

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

An easy programming language to learn. It is the primary language of code that runs on web pages, but it is also suitable for many other types of code.

### What is Python?

An easy programming language to learn. It is commonly used for data work (data gathering, data analysis, data science) and [server-side programming](#what-is-server-side-programming).

### What is a programming paradigm?

A set of features about a programming language.

### What is php?

A programming language commonly used for server-side programming.

### What is Ruby?

A high-level, clean programming language, commonly used for web development.

### What is Rust?

### What is Flutter?

### What is Go?

### What is Ruby?

### What is PHP?

### What is TypeScript?

### What is Kotlin?

### What is Scala?

### What is Clojure?

### What is a scripting language?

[wiki](https://en.wikipedia.org/wiki/Scripting_language)

### What is a statically-typed language?

[overflow](https://stackoverflow.com/questions/2690544/what-is-the-difference-between-a-strongly-typed-language-and-a-statically-typed)

### What is a strongly-typed language?

[overflow](https://stackoverflow.com/questions/2690544/what-is-the-difference-between-a-strongly-typed-language-and-a-statically-typed)

### What is a weakly-typed language?

[overflow](https://stackoverflow.com/questions/2690544/what-is-the-difference-between-a-strongly-typed-language-and-a-statically-typed)

### What is Javascript used for?

Primarily front-end(with jQuery/React/Angular/Vue) and back-end(with MongoDB/Express/Node) app development. However, it can also do many other things like machine learning, data visualization and more.

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

It's a word [**generators**](#what-are-generators) use.

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

Since they are optional, only add them as necessary. They are especially useful for [**function signatures**](#what-is-a-function-signature).

Use `# type: ignore` to ignore a mypy error, but first check that it's actually an error.

### How do I use type hints?

[Learn it here.](https://mypy.readthedocs.io/en/latest/cheat_sheet_py3.html#functions)

```python
from typing import Dict, Tuple, List, Callable, Mapping, Sequence, Iterable, Any, IO, NoReturn, Union, Optional

def null_aware_func(x: Optional[float]) -> Optional[float]:
    if x is None:
        return None
    return 2.2 * x ** 1.05
```

### Should I group my pytest tests into classes?

There are pros and cons.

Module-level tests have omit the meaningless `self` argument and are flatter.

Grouping tests into classes(one class per class tested in the module) allows us to use the same test name when two classes have the same function name to be tested. It also forces us to group our tests by the class they are testing (and also enables automatic grouping using a text editor).

### What are magic methods/dunders?

### Should I use Mock or MagicMock when mocking?

[The docs](https://docs.python.org/dev/library/unittest.mock.html) recommend to use MagicMocks by default. It saves time defining magic methods.

A MagicMock is just Mock with [**magic methods**](#what-are-magic-methodsdunders) which don't raise exceptions.

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

### What is a text editor?

It's like Notepad (on Windows) or Notes (on Mac). It allows us to type and save code as plain text.

### What is an IDE?

A text editor with many tools to help development.

_Short for: integrated development environment._

### What is Atom?

### What are some useful regex for find and replace?

- ^\s.\*\n selects all lines which start with a whitespace character.
- You can replace selections with an empty string to delete the selections.

### What is Git?

A version control system. It helps collaboration, works as a form of backup, and more.

### What is Github?

A place to store code, which integrates well with [**git**](#git).

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

### What is a developer?

Someone who writes code.

### What do developers do on a day-to-day basis?

### What is a data analyst?

Someone who works primarily with data. This usually involves collecting, manipulating, visualizing and analyzing the data.

### What is a data scientist?

Someone who does machine learning. They often also need to do the work of a data analyst.

### What is the principle of least astonishment?

If a necessary feature has a high astonishment factor, it may be necessary to redesign the feature. It is applied to user interface and software design.

### What is Agile?

### What is Test Driven Development(TDD)?

### What is Behavior Driven Development(BDD)?

[source](https://dannorth.net/introducing-bdd/)

### How do I add a license to my software?

Simply copy a LICENSE file to your repo.

### What software licenses should I choose?

[Choose a license](https://choosealicense.com/)

### What is .NET?

A framework needed for running or writing newer windows apps.

### What is an algorithm?

A way to solve a problem by repeating a set of instructions.

### What is an API?

The set of instructions that a program understands.

### What is vim?

A powerful shell text editor.

### What is a batch file?

A script run on windows, usually executing commands like running other programs, copying, moving or renaming files and directories.

### What is a binary?

Often it is used to refer to an executable file, ie. one that doesn't need to be installed or compiled.

Technically, it is any file which has non-text information and cannot be understood by humans.

### What is code compiling?

### What is a daemon?

A program that runs in the background.

### What is a data type?

A form of data. Running a function using data of an unintended type is a common source of bugs. Eg, integer, string, object.

### What is a framework?

A way to do something, which usually comes with its API and sometimes its own folder structure and configuration files. For example, React is a front-end web framework and Django is a back-end web framework.

### What is a hard disk?

### What is high level code?

Also called high-level.

### What is an interpreter?

A program that directly executes instructions, without requiring them to be [**compiled**](#what-is-code-compiling) first.

### What is the JRE?

The Java Runtime Environment is a program which runs [**Java**](#what-is-java) programs.

### What is a keylogger?

A program that records all keys pressed on a computer's keyboard.

### What is a library?

A bunch of code to help do something.

### What is low level code?

### What is a manifest file?

A file with data about some other files that it comes together with.

### What is markup?

### What is RSA?

A public-key encryption technology. (to simplify)

### What is code parsing?

To parse code is to read it.

### What is a pipeline?

### What is a program?

Code that makes up some system. It is usually compiled.

### What is a proprietary software?

(Usually) A software you have to pay for.

### What is a script?

Code that references some system. It is usually interpreted.

### What is Sublime Text?

A popular, lightweight text editor.

### What is a lightweight program?

One that is small in size and consumes less memory than other similar programs.

### What is syntax?

The grammar for coding something, which needs to be correct for it to work.

### What is XML?

### What is an absolute path?

A path defined from a fixed point, usually root directory.

### What is a directory?

### What is a file?

### What is a file extension?

The part of the filename after the period. Eg, for 'zen.txt', the extension is 'txt'(or '.txt'). The operating system uses the extension to decide what program to open this file with. Changing the extension of a file doesn't change the actual content of the file.

### What is a file system?

Something that keeps your files organized. Windows uses NTFS or FAT32(old). Mac uses HFS+ or HFS(old).

### What is a path?

An address for a file or directory. Looks like this ~/Music/iTunes/ or this C:\\My Documents\\zen.txt or this ../../assets/zen.jpg. See **absolute path** and **relative path**.

### What is a relative path?

A path defined from wherever the current directory is. This usually means it is shorter than a comparable absolute path.

### What is a shell?

### What is a partition?

A part of a hard disk, which can have its own operating system.

### What is HDMI?

A way to transmit audio and video data in a single cable.

### What is a parallel port?

A port for an old type of cable.

### What is a public key certificate?

### What is public key encryption?

A way to give data safely. A message is encrypted with a public key, and can only be decrypted by the matching private key. (not sure)

### What is OneDrive?

A shared storage space for use with SharePoint and Microsoft Teams.

### What is SharePoint?

A system to create SharePoint sites to use with Microsoft Teams.

### What is Microsoft Teams?

A chat app for Office365.

### What is Office365?

### What is PowerApps?

A Microsoft proprietary cross-platform development framework which includes WYSIWYG GUI IDE.

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
- **ajax** - A way for a webpage to update itself without loading a new webpage.
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
