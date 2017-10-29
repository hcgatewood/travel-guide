# The New Programmer's Travel Guide

A curated guide to relevant resources for the new computer science student—it's everything else you'll need to know.

Learning to program is hard. Finding your way to first-rate resources, however, just got a whole lot easier. See the [usage notes](#using-this-guide) for an intro. This guide assumes you're on a Mac, but is valuable on any machine.

## 🗺️ Topics

### First steps

- [Getting started](#getting-started)
- [Homebrew](#homebrew)
- [Sublime Text](#sublime-text)
- [Terminal (bash)](#terminal-bash)
- [Git](#git)
- [Python](#python)
- [Debugging](#debugging)
- [Getting a job](#getting-a-job)
- [Communicating](#communicating)

### Building things

- [Web development](#web-development)
- [HTML/CSS](#htmlcss)
- [JavaScript](#javascript)
- [Node.js](#nodejs)
- [MongoDB](#mongodb)
- [Markdown](#markdown)
- [Unicode](#unicode)
- [Profiling](#profiling)
- [Software development](#software-development)

### More technical

- [Vim](#vim)
- [Regex](#regex)
- [Serialization](#serialization)
- [C](#c)
- [LaTeX](#latex)
- [SSH](#ssh)
- [Tmux](#tmux)
- [IRC](#irc)
- [Blockchain](#blockchain)
- [Miscellanea](#miscellanea)


## 🏖️ Topical itinerary

### Getting started

A healthy mentality makes everything easier. Topics include learning to ask effective questions as well as taking a growth-based approach to learning.

- 🌟 [How to learn how to code](https://medium.freecodecamp.com/this-picture-will-change-the-way-you-learn-to-code-557ac1e109bd)
- 🌟 [Make deliberate practice a habit](http://www.makeuseof.com/tag/want-become-expert-something-try-deliberate-practice/)
- [Why learning to code is so damn hard](https://www.vikingcodeschool.com/posts/why-learning-to-code-is-so-damn-hard)
- [Great advice for new CS students](https://www.quora.com/What-advice-would-you-give-to-a-Computer-Science-major-student-that-you-wish-you-were-given-when-you-started-Computer-Science)
- [How to ask programming questions](https://www.propublica.org/nerds/item/how-to-ask-programming-questions)
- [How to find answers from Stack Overflow](https://meta.stackexchange.com/questions/5180/what-are-some-good-tips-for-searching-stack-overflow)
- [Rubber duck problem solving](http://blog.codinghorror.com/rubber-duck-problem-solving/)
- [Thoughts on dealing with failure](http://hcgatewood.me/014-failure/)
- [Lots of good, short introductions with further resources](https://learnxinyminutes.com)
- [Huge list of resources on many topics](https://github.com/sindresorhus/awesome)
- 🌟 [Self-taught online CS classes](https://github.com/ossu/computer-science)
- 🌟 [Map of computer science](https://www.youtube.com/watch?v=SzJ46YA_RaA)

### Homebrew

[Homebrew](https://en.wikipedia.org/wiki/Homebrew_(package_management_software)) is a popular [package manager](https://en.wikipedia.org/wiki/Package_manager) for the Mac operating system. It makes installing things as easy as `brew install <package>`. Similarly, Homebrew Cask facilitates installing GUI applications. Don't forget to run `brew doctor` after installing Homebrew and fix the reported issues.

- [Intro video](https://www.youtube.com/watch?v=TyDqlbXRU5g)
- [Install Homebrew](http://brew.sh)
- [Install Homebrew Cask](https://caskroom.github.io)

### Sublime Text

[Sublime Text](https://www.sublimetext.com) is powerful [text editor](https://en.wikipedia.org/wiki/Text_editor), [popular](https://insights.stackoverflow.com/survey/2017#technology-most-popular-developer-environments-by-occupation) especially among new developers. It's straightforward and easy to use, making for great first editor.

- Install: `brew cask install sublime-text`
- [Setup, packages, settings](https://www.youtube.com/watch?v=zVLJfrIwEP8)
- [Tutorial](https://www.youtube.com/playlist?list=PLpcSpRrAaOaqQMDlCzE_Y6IUUzaSfYocK)
- [Setting indentation and tab stop](https://www.sublimetext.com/docs/2/indentation.html)
- [Setting rulers](http://stackoverflow.com/questions/9910143/how-to-make-ruler-always-be-shown-in-sublime-text-2)

### Terminal (bash)

At a high level, a [shell](https://en.wikipedia.org/wiki/Shell_(computing)) is an interface facilitating interaction with an operating system. The shell most developers are familiar with is the [Unix shell](https://en.wikipedia.org/wiki/Unix_shell), which provides a [command line interface](https://en.wikipedia.org/wiki/Command-line_interface). Finally, [bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell)) is a mature, popular [shell language](https://en.wikipedia.org/wiki/Command_language).

#### Intro

- [Intro video 1](https://www.youtube.com/watch?v=x73WTEltyHU)
- [Intro video 2](https://www.youtube.com/watch?v=q7-aEspwwEI)
- 🌟 [Basic usage](http://cs.lmu.edu/~ray/notes/bash/)

#### Reference

- [Reference manual](http://www.faqs.org/docs/bashman/bashref.html)
- [Overview](http://linuxcommand.org/lc3_learning_the_shell.php)
- [Cheatsheet](https://learnxinyminutes.com/docs/bash/)

#### Specific topics

- [What is a dotfile](https://askubuntu.com/questions/94780/what-are-dot-files)
- [What is an rc file](http://stackoverflow.com/questions/11030552/what-does-rc-mean-in-dot-files)
- [What is a PATH](http://www.linfo.org/path_env_var.html)
- [How to add to your PATH](https://unix.stackexchange.com/questions/26047/how-to-correctly-add-a-path-to-path)
- [What is a .bashrc](https://unix.stackexchange.com/questions/129143/what-is-the-purpose-of-bashrc-and-how-does-it-work)
- [Difference between .bashrc and .bash_profile on Macs](https://apple.stackexchange.com/questions/51036/what-is-the-difference-between-bash-profile-and-bashrc)
- [Difference between shell, terminal, console](https://superuser.com/questions/144666/what-is-the-difference-between-shell-console-and-terminal)
- [Redirecting to stdout/stderr](https://stackoverflow.com/questions/818255/in-the-shell-what-does-21-mean)

#### Favorite programs

- 🌟 [tldr, the better version of man pages](http://tldr-pages.github.io)
- [ag, a fast and powerful replacement for grep](https://github.com/ggreer/the_silver_searcher)
- [rsync, for securely copying a file between devices](https://linux.die.net/man/1/rsync)
- [htop, the interactive process viewer](http://hisham.hm/htop/)
- [jq, a JSON processor](https://stedolan.github.io/jq/)

#### Resources

- [Mathias's dotfiles, a collection of quality dotfiles](https://github.com/mathiasbynens/dotfiles)
- [Dotbot, a dotfile manager](https://github.com/anishathalye/dotbot/)
- [Cmder, a bash-style shell for windows](http://cmder.net)
- [Dev-setup, a tool and listing of common installations](https://github.com/donnemartin/dev-setup)

### Git

[Git](https://git-scm.com) is a [distributed](https://en.wikipedia.org/wiki/Distributed_computing) [version control](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) system. Version control allows multiple people to work on the same code base at the same time, among other benefits. Git is [wildly popular](https://insights.stackoverflow.com/survey/2017#work-version-control), powerful, and somewhat notorious for being [difficult to learn](https://www.quora.com/Why-is-Git-so-hard-to-learn).

#### Intro

- Install: `brew install git`
- 🌟 [Intro to version control](http://web.mit.edu/6.005/www/fa16/classes/05-version-control/)
- [Conceptual intro](https://backlogtool.com/git-guide/en/intro/intro1_1.html)
- [Interactive tutorial](https://try.github.io/)

#### Reference

- [Cheatsheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)
- [Documentation](https://git-scm.com/documentation)
- [GitHub Guides, a collection of informational GitHub videos](https://guides.github.com)

#### Specific topics

- [Git is not GitHub](http://stackoverflow.com/questions/13321556/difference-between-git-and-github)
- [Intro to GitHub](https://guides.github.com/activities/hello-world/)
- [Effective commit messages](http://chris.beams.io/posts/git-commit/)
- [Version control in a team](http://web.mit.edu/6.005/www/fa16/classes/27-team-version-control/)
- [GitHub Flow, a popular git workflow](https://guides.github.com/introduction/flow/)

### Python

[Python](https://en.wikipedia.org/wiki/Python_(programming_language)) is a [popular](https://insights.stackoverflow.com/survey/2017#most-popular-technologies), general-purpose, high-level programming language. It's also a [great first language](http://effbot.org/pyfaq/is-python-a-good-language-for-beginning-programmers.htm).

#### Intro

- Install: `brew install python3`
- 🌟 [Curated guide to everything Python](http://docs.python-guide.org/en/latest/)
- [Google's official Python tutorial](https://developers.google.com/edu/python/)
- [Official tutorial](https://docs.python.org/3/tutorial/index.html)
- [Intro to programming class](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-00-introduction-to-computer-science-and-programming-fall-2008/)

#### Specific topics
- [Unicode overview](https://docs.python.org/3/howto/unicode.html)
- [String vs. bytes](https://stackoverflow.com/questions/6224052/what-is-the-difference-between-a-string-and-a-byte-string)
- [Static, class, and abstract methods](https://julien.danjou.info/blog/2013/guide-python-static-class-abstract-methods)
- [Anti-patterns](https://docs.quantifiedcode.com/python-anti-patterns/index.html)
- 🌟 [Deep dive into intermediate topics](http://www.diveintopython3.net/table-of-contents.html)

### Debugging

[Debugging](https://en.wikipedia.org/wiki/Debugging) is the process of tracking down and fixing [bugs](https://en.wikipedia.org/wiki/Software_bug). Rather than a series of ad hoc actions, debugging is a [much-discussed concept](https://news.ycombinator.com/item?id=11729806) that can [take up a large portion of time spent developing](https://softwareengineering.stackexchange.com/questions/91758/debugging-facts-and-statistics).

- 🌟 [Avoiding bugs](http://web.mit.edu/6.005/www/fa16/classes/08-avoiding-debugging/)
- [General strategy](http://web.mit.edu/6.005/www/fa16/classes/10-debugging/)
- [Python debugging tips](http://stackoverflow.com/questions/1623039/python-debugging-tips)
- [pdb, the Python builtin debugger](https://docs.python.org/3/library/pdb.html)
- [gdb, a debugger for many compiled languages](https://www.gnu.org/software/gdb/)
- [Intro to gdb](https://www.youtube.com/watch?v=sCtY--xRUyI)
- [GUI for gdb](https://github.com/cs01/gdbgui)
- [More gdb features](https://www.youtube.com/watch?v=PorfLSr3DDI)
- [Overview of Chrome DevTools, including debugger](https://developer.chrome.com/devtools)

### Getting a job

Proper preparation makes getting a job much easier. Topics include best practices, a nice resume template, practice questions, and a list of companies with a short application.

- 🌟 [Overview of the process, best practices](https://github.com/gu-app-club/lets-learn-jobs)
- [LaTeX resume template](https://www.overleaf.com/latex/templates/deedy-resume/sqdbztjjghvz#.WQNvMVIUVE5)
- [List of action verbs for descriptions](http://career.opcd.wfu.edu/files/2011/05/Action-Verbs-for-Resumes.pdf)
- [General resume tips](https://www.quora.com/What-are-some-examples-of-a-computer-science-students-resume-that-received-an-internship-at-Google)
- [Great site for technical interview practice](https://www.interviewcake.com)
- 🌟 [More algorithm-based interview practice questions](https://leetcode.com/problemset/algorithms/)
- [System design interview overview](https://github.com/checkcheckzz/system-design-interview)
- 🌟 [Big list of CS companies with a short application](https://github.com/j-delaney/easy-application)
- [Big list of CS companies without whiteboard interviews](https://github.com/poteto/hiring-without-whiteboards)
- [Intro to algorithms class](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/)

### Communicating

Design, development, research, and everything in between rely on effective communication between peers. Topics include how to present publicly, accept criticism, and write a quality [README](https://en.wikipedia.org/wiki/README).

- [Best practices for competent public speaking](https://www.gsb.stanford.edu/insights/big-data-approach-public-speaking)
- [Proper use of body language](https://www.youtube.com/watch?v=cFLjudWTuGQ&t=1s)
- [Best practices for group ideation](https://challenges.openideo.com/blog/seven-tips-on-better-brainstorming)
- 🌟 [Accepting criticism](https://medium.com/the-year-of-the-looking-glass/taking-feedback-impersonally-7c0f3a8199d9)
- [Writing a README, with examples](https://github.com/matiassingers/awesome-readme)
- [README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)

### Web development

[Web development](https://en.wikipedia.org/wiki/Web_development) refers to building some component of a [web site](https://en.wikipedia.org/wiki/Website) for the [World Wide Web](https://en.wikipedia.org/wiki/World_Wide_Web). It's a [hot occupation as of 2016](https://www.bls.gov/ooh/computer-and-information-technology/web-developers.htm).

- [What is a web app](https://www.youtube.com/watch?v=RsQ1tFLwldY)
- 🌟 [Web developer roadmap](https://github.com/kamranahmedse/developer-roadmap)
- 🌟 [Dash, an on-command documentation reader for Macs](https://kapeli.com/dash)
- 🌟 [Sample real-world apps in various stacks](https://github.com/gothinkster/realworld)
- [Disable browser caching](http://stackoverflow.com/questions/5690269/disabling-chrome-cache-for-website-development)
- [Internet vs. World Wide Web](https://www.youtube.com/watch?v=laepk9KrAZY)
- [HTTP and HTTPS](https://www.youtube.com/watch?v=po3zYOe00O4)
- [API: Application Programming Interface](https://www.youtube.com/watch?v=7YcW25PHnAA)
- [REST APIs](https://www.youtube.com/watch?v=YCcAE2SCQ6k)
- [TCP/IP](https://www.youtube.com/watch?v=PpsEaqJV_A0)
- [IPv4 vs. IPv6](https://www.youtube.com/watch?v=aor29pGhlFE)
- [NAT: Network Address Translation](https://www.youtube.com/watch?v=QBqPzHEDzvo)
- [Web development class](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-170-software-studio-spring-2013/)
- [Computer systems class](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-033-computer-system-engineering-spring-2009/)

### HTML/CSS

[HTML](https://en.wikipedia.org/wiki/HTML) and [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets), along with JavaScript, form the cornerstone technologies of the World Wide Web. Many newer software libraries are built on top of these languages, but learning the basic building blocks is still essential.

- 🌟 [Intro and overview](https://internetingishard.com/html-and-css/)
- [Hello-world HTML/CSS app](https://www.youtube.com/watch?v=wrdR5Su_Stg)
- [How layout works](http://learnlayout.com)
- [HTML in-depth](http://www.w3schools.com/html/default.asp)
- [Centering things](https://css-tricks.com/centering-css-complete-guide/)
- [Bootstrap, a popular framework making HTML/CSS easier](http://getbootstrap.com)

### JavaScript

[JavaScript](https://en.wikipedia.org/wiki/JavaScript) is the programming language of the World Wide Web, and can also be run outside of a [browser](https://en.wikipedia.org/wiki/Web_browser) with Node.js. It's high-level, general purpose, and the [most popular programming language of 2017](https://insights.stackoverflow.com/survey/2017#most-popular-technologies).

- 🌟 [Intro](http://jsforcats.com)
- 🌟 [Intro with an interactive tutorial](http://eloquentjavascript.net)
- [Hub for tutorials, tools, references](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [How the var keyword works](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var)
- [Promises](http://exploringjs.com/es6/ch_promises.html)
- [Style guide](https://github.com/airbnb/javascript)
- 🌟 [JSON browser formatter](https://github.com/rfletcher/safari-json-formatter)

### Node.js

[Node.js](https://en.wikipedia.org/wiki/Node.js) is a [cross-platform](https://en.wikipedia.org/wiki/Cross-platform) JavaScript [run-time environment](https://en.wikipedia.org/wiki/Runtime_system). In other words, while JavaScript was traditionally limited to the client-side browser, Node.js provides an environment allowing execution of JavaScript code on the [server-side](https://en.wikipedia.org/wiki/Server-side). [Npm](https://en.wikipedia.org/wiki/Npm_(software)) is the default [package manager](https://en.wikipedia.org/wiki/Package_manager) for Node.js.

#### Resources

- Install: `brew install node`
- 🌟 [Intro video](https://www.youtube.com/watch?v=pU9Q6oiQNd0)
- [Overview](https://github.com/maxogden/art-of-node#the-art-of-node)
- [Npm, the Node Package Manager](https://docs.npmjs.com/getting-started/what-is-npm)
- [Interactive tutorial](https://github.com/workshopper/learnyounode#learn-you-the-nodejs-for-much-win)
- [In-depth tutorial](https://www.tutorialspoint.com/nodejs/nodejs_introduction.htm)
- [Express, the de facto facto Node.js web framework](https://expressjs.com)

#### Favorite packages

- [diff-so-fancy, for easier to read Git diffs](https://www.npmjs.com/package/diff-so-fancy)
- [nodemon, for restarting programs upon code changes](https://www.npmjs.com/package/nodemon)
- 🌟 [husky, a git hook manager](https://www.npmjs.com/package/husky)
- [lodash, a set of JavaScript utilities](https://www.npmjs.com/package/lodash)
- [gulp, the streaming build system](https://www.npmjs.com/package/gulp)
- [cat-me, because cats make life better](https://www.npmjs.com/package/cat-me)

### MongoDB

[MongoDB](https://en.wikipedia.org/wiki/MongoDB) is a document-oriented database. It's a standalone program, but is also popularized as part of the [MEAN stack](https://en.wikipedia.org/wiki/MEAN_(software_bundle)). The `mongod` daemon starts and manages the database, the `mongo` command starts a shell-like connection to the database, and specific languages interact with the database through drivers (_i.e._ [bindings](https://en.wikipedia.org/wiki/Language_binding)).

- [Intro and tutorial video](https://www.youtube.com/watch?v=-0X8mr6Q8Ew&list=PLGLfVvz_LVvRfdt8_W0dV311Xa8SayfCY)
- [Official intro](https://docs.mongodb.com/getting-started/shell/)
- [Reference](https://docs.mongodb.com/manual/)
- [Using MongoDB in Node.js apps](https://mongodb.github.io/node-mongodb-native/api-articles/nodekoarticle1.html)
- [Node.js bindings](https://mongodb.github.io/node-mongodb-native/)

### Markdown

[Markdown](https://en.wikipedia.org/wiki/Markdown) is a [markup language](https://en.wikipedia.org/wiki/Lightweight_markup_language) designed to be easy to learn and fast to write. It can be converted directly to HTML, and is also a common choice for README files. Its formal specification is a bit loose, so many similar syntax flavors exist.

- [Intro video](https://www.youtube.com/watch?v=6A5EpqqDOdk)
- [Markdown for GitHub](https://guides.github.com/features/mastering-markdown/)
- [Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Original syntax specification](http://daringfireball.net/projects/markdown/syntax)
- [Pandoc, for converting files between markup formats](http://pandoc.org)
- 🌟 [grip, the GitHub-flavored markdown renderer](https://github.com/joeyespo/grip)

### Unicode

[Unicode](https://en.wikipedia.org/wiki/Unicode) is a worldwide standard for encoding and representing text. It makes things like [internationalization and localization](https://en.wikipedia.org/wiki/Internationalization_and_localization) a lot easier. Unicode can be actually implemented by a number of different [character encodings](https://en.wikipedia.org/wiki/Character_encoding), the current most popular of which is [UTF-8](https://en.wikipedia.org/wiki/UTF-8).

- [Intro video](https://www.youtube.com/watch?v=sqPTR_v4qFA)
- 🌟 [Overview and further info](http://reedbeta.com/blog/programmers-intro-to-unicode/)
- [Historical perspective](https://www.youtube.com/watch?v=MijmeoH9LT4)
- [Official intro](http://unicode.org/standard/principles.html)
- [UTF-8 is not the same thing as Unicode](http://stackoverflow.com/questions/643694/utf-8-vs-unicode)

### Profiling

[Profiling](https://en.wikipedia.org/wiki/Profiling_(computer_programming)) is the process of measuring, aggregating, and interpreting data on a program's space and time usage. It's an important tool for [performance engineers](https://en.wikipedia.org/wiki/Performance_engineering), but is also used across development fields, including in web development.

- [Intro to Python profiling video](https://www.youtube.com/watch?v=QJwVYlDzAXs)
- [line_profiler, a line-by-line profiling tool for Python](https://github.com/rkern/line_profiler)
- [General Python profiling information](http://stackoverflow.com/questions/582336/how-can-you-profile-a-python-script)
- 🌟 [Flame graph](http://www.brendangregg.com/FlameGraphs/cpuflamegraphs.html)
- [Chrome DevTools JavaScript profiler](https://developers.google.com/web/tools/chrome-devtools/rendering-tools/js-execution)
- [Perf, a Linux profiling tool](https://perf.wiki.kernel.org/index.php/Tutorial#Sampling_with_perf_record)
- [Cachegrind, a cache and branch-prediction profiler](http://valgrind.org/docs/manual/cg-manual.html)
- [General C/C++ profiling information](http://stackoverflow.com/questions/26663/whats-your-favorite-profiling-tool-for-c)
- [In-depth lectures on performance engineering](https://www.youtube.com/playlist?list=PLD2AE32F507F10481)

### Software development

[Software development](https://en.wikipedia.org/wiki/Software_development) is the process of designing, constructing, testing, and releasing software. At scale, many otherwise inconsequential issues turn into colossal problems without proper software development techniques.

- 🌟 [Intro to testing](http://web.mit.edu/6.005/www/fa16/classes/03-testing/)
- 🌟 [Difference between unit, integration, functional, and acceptance tests](http://stackoverflow.com/questions/4904096/whats-the-difference-between-unit-functional-acceptance-and-integration-test)
- [Software construction class](http://web.mit.edu/6.005/www/fa16/)
- [Long-term reading list](https://www.quora.com/What-are-the-must-read-books-for-software-engineers)

### Vim

[Vim](https://en.wikipedia.org/wiki/Vim_(text_editor)) is a [popular](https://insights.stackoverflow.com/survey/2017#technology-most-popular-developer-environments-by-occupation), powerful, mature text editor. It can have a [strong learning curve](http://yehudakatz.com/2010/07/29/everyone-who-tried-to-convince-me-to-use-vim-was-wrong/), but many feel [the effort pays off](http://stackoverflow.com/questions/597077/what-are-the-benefits-of-learning-vim).

- Install: `brew install vim`
- Official tutorial: `vimtutor`
- [Online tutorial](http://www.openvim.com)
- [Cheatsheet](https://learnxinyminutes.com/docs/vim/)
- [Sensible start to a vimrc](https://github.com/tpope/vim-sensible)
- [Tips](http://vim.wikia.com/wiki/Category:Getting_started)
- [Advice on settings](http://nvie.com/posts/how-i-boosted-my-vim/)
- 🌟 [Advice on making a vimrc](http://dougblack.io/words/a-good-vimrc.html)
- [Vimrc with more features](https://github.com/amix/vimrc)
- 🌟 [Intermediate topics](https://www.cs.oberlin.edu/~kuperman/help/vim/home.html)
- [Screencasts on various topics](http://vimcasts.org/categories/)

### Regex

A [regular expression](https://en.wikipedia.org/wiki/Regular_expression) is a string defining a search pattern. A regex functions as a declarative way to perform _find_ or _find and replace_ string operations. There are multiple flavors with often incompatible syntaxes. It's [pronounced like FedEx, with the "g" from "regular."](https://english.stackexchange.com/questions/94371/what-is-the-correct-pronunciation-of-regex)

- 🌟 [Interactive intro](https://regexone.com)
- [Interactive practice](https://regexr.com)
- [How-to in Python](https://docs.python.org/3/howto/regex.html)
- [Reference](https://www.regular-expressions.info/refflavors.html)

### Serialization

[Serialization](https://en.wikipedia.org/wiki/Serialization) is the process of converting an in-memory structure to a format that can be readily stored and/or transmitted. Often this takes the form of translating a language-specific object to a language-agnostic string or [bytestream](https://en.wikipedia.org/wiki/Bitstream).

#### Intro

- [Intro video](https://www.youtube.com/watch?v=uS37TujnLRw)
- [Intro to JSON](https://www.digitalocean.com/community/tutorials/how-to-work-with-json-in-javascript)
- 🌟 [Serialization in Python](http://www.diveintopython3.net/serializing.html)

#### Common formats

- [JSON: JavaScript Object Notation](http://www.json.org)
- [YAML: YAML Ain't Markup Language](http://yaml.org)
- [XML: eXtensible Markup Language](https://www.w3schools.com/xml/xml_whatis.asp)
- [Protocol buffers](https://developers.google.com/protocol-buffers/)

### C

[C](https://en.wikipedia.org/wiki/C_(programming_language)) is a general-purpose programming language with [static typing](https://en.wikipedia.org/wiki/Type_system#Static_type_checking). It was developed in the early 1970s and is historically [one of the most popular languages of all time](https://www.tiobe.com/tiobe-index//). It's a [medium-level language](https://en.wikipedia.org/wiki/High-level_programming_language) that maps efficiently to [machine code](https://en.wikipedia.org/wiki/Machine_code). C is considered more [difficult to learn](https://www.quora.com/How-easy-is-it-to-learn-C) than higher-level languages like Python and JavaScript, but [learning C is worth it](https://softwareengineering.stackexchange.com/questions/14744/i-dont-know-c-and-why-should-i-learn-it).

- 🌟 [Intro videos](https://www.youtube.com/playlist?list=PL2_aWCzGMAwLSqGsERZGXGkA5AfMhcknE)
- [Tutorial](https://en.wikibooks.org/wiki/C_Programming)
- [Reference book](https://www.amazon.com/Programming-Language-Brian-W-Kernighan/dp/0131103628)
- [How macros work](https://gcc.gnu.org/onlinedocs/cpp/Macros.html)
- 🌟 [Make intro](http://matt.might.net/articles/intro-to-make/)
- [Make reference](https://www.gnu.org/software/make/manual/make.html)
- 🌟 [How to read declarations](http://www.ericgiguere.com/articles/reading-c-declarations.html)
- [Declaration decoder](https://cdecl.org)
- [Class on how computers work](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2009/)

### LaTeX

[LaTeX](https://en.wikipedia.org/wiki/LaTeX) is a document preparation system. It's especially popular in academia, and is used in many STEM-related fields. It allows users to focus on a document's contents and let LaTeX focus on the document's preparation and formatting.

- [Intro video](https://www.youtube.com/watch?v=SoDv0qhyysQ)
- [Hub for tutorials, tools, references](https://www.latex-project.org)
- [Extensive guide](https://en.wikibooks.org/wiki/LaTeX)
- [Latexmk, a program for compiling LaTeX files locally](http://mg.readthedocs.io/latexmk.html)
- 🌟 [Detexify, a tool for finding LaTeX symbols](http://detexify.kirelabs.org/classify.html)
- 🌟 [Overleaf, an online tool for collaborative LaTeX writing](https://www.overleaf.com)
- [BibTeX, a bibliography management system](https://www.sharelatex.com/learn/Bibliography_management_with_bibtex)

### SSH

[SSH](https://en.wikipedia.org/wiki/Secure_Shell) is a protocol for operating remote devices from your local device, in a secure manner. SSH allows login and command execution over the Internet, even on devices not physically accessible.

- 🌟 [Intro video](https://www.youtube.com/watch?v=DbPDraCYju8)
- [How SSH works](https://www.youtube.com/watch?v=zlv9dI-9g1U)
- [Reference](https://www.ssh.com/ssh/command/)
- [GitHub and SSH](https://help.github.com/articles/connecting-to-github-with-ssh/)
- 🌟 [SSH in-depth](http://www.unixwiz.net/techtips/ssh-agent-forwarding.html)

### Tmux

[Tmux](https://en.wikipedia.org/wiki/Tmux) is a shell program that allows switching between and detaching of virtual consoles.

- 🌟 [Intro video](https://www.youtube.com/watch?v=BHhA_ZKjyxo)
- [Intro article](https://danielmiessler.com/study/tmux/#gs.t5PZaUE)
- 🌟 [Cheatsheet](https://gist.github.com/MohamedAlaa/2961058)
- [Pair programming](https://www.youtube.com/watch?v=norO25P7xHg)
- [Config file](http://www.hamvocke.com/blog/a-guide-to-customizing-your-tmux-conf/)

### IRC

[IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat) is an [application layer protocol](https://en.wikipedia.org/wiki/Application_layer) (same layer as the World Wide Web) facilitating text-based communication. Although it's less popular now than in the past, many open source projects communicate using the [freenode](https://en.wikipedia.org/wiki/Freenode) IRC [network](https://en.wikipedia.org/wiki/Computer_network). [Slack](https://slack.com) is a popular, easy to use, [proprietary](https://en.wikipedia.org/wiki/Proprietary_software) alternative for team communication.

- [Intro video](https://www.youtube.com/watch?v=Ltq0hMgizi0)
- [General overview and help](http://www.irchelp.org)
- [Irssi, a terminal-based IRC client](https://irssi.org)
- [Irssi intro video](https://www.youtube.com/watch?v=f0CWZAE3FEs)
- [Irssi quick commands](https://www.linode.com/docs/applications/messaging/using-irssi-for-internet-relay-chat)
- [Irssi in-depth commands](https://irssi.org/documentation/startup/#first-steps)
- [Irssi FAQ, including startup commands and scripts](https://irssi.org/documentation/faq/)
- [Irssi + tmux](https://coderwall.com/p/t1c7-w/persistent-irc-history-with-irssi-and-tmux)
- [Foonetic, a decent first network](http://foonetic.net)

### Blockchain

A [blockchain](https://en.wikipedia.org/wiki/Blockchain) is a continuously growing list of [timestamped](https://en.wikipedia.org/wiki/Timestamp) "blocks." Each block functions as a [record](https://en.wikipedia.org/wiki/Record_(computer_science)), allowing a blockchain to function as a [distributed database](https://en.wikipedia.org/wiki/Distributed_database). The idea of a blockchain is relatively new, first described in 2008 by an unknown person using the assumed pseudonym [Satoshi Nakamoto](https://en.wikipedia.org/wiki/Satoshi_Nakamoto). [Bitcoin](https://en.wikipedia.org/wiki/Bitcoin), on the other hand, is the [original](https://bitcoin.org/bitcoin.pdf) in a long line of [cryptocurrencies](https://en.wikipedia.org/wiki/Cryptocurrency) utilizing blockchain technology.

- 🌟 [Why blockchains are the future of money](https://www.ted.com/talks/neha_narula_the_future_of_money)
- 🌟 [Intro video](https://www.youtube.com/watch?v=_160oMzblY8)
- [Intro to Bitcoin](https://www.youtube.com/watch?v=Lx9zgZCMqXE)
- [Bitcoin vs. Ethereum](https://www.youtube.com/watch?v=-SMliFtoPn8)
- [Intro to Ethereum](https://www.youtube.com/watch?v=66SaEDzlmP4)
- [What Ethereum can be](https://steemit.com/ethereum/@hexayurt/what-does-ether-usd100-mean)
- [Shared public ledgers class](https://github.com/mit-dci/6.892-public)

### Miscellanea

Miscellaneous resources. Topics include technical discussions, an artificial intelligence playbook, and a recommendation of Google Scholar for organizing technical papers.

- [Google Scholar, a free scholarly literature browser](https://scholar.google.com)
- [How file extensions work](https://askubuntu.com/questions/803434/do-file-extensions-have-any-purpose-for-the-operating-system)
- [Floating point representations](http://www.toves.org/books/float/)
- [Interpreted vs. compiled](http://stackoverflow.com/questions/3265357/compiled-vs-interpreted-languages)
- [Serverless architecture](https://martinfowler.com/articles/serverless.html)
- 🌟 [Artificial intelligence playbook](http://aiplaybook.a16z.com)
- [Unix](https://en.wikipedia.org/wiki/Unix)
- [Linux distribution](https://en.wikipedia.org/wiki/Linux_distribution)
- [Linux filesystem hierarchy conventions](http://www.pathname.com/fhs/pub/fhs-2.3.html)
- [Static vs. shared vs. DL libraries](https://www.dwheeler.com/program-library/Program-Library-HOWTO/t1.html)
- [Daemon](https://en.wikipedia.org/wiki/Daemon_(computing))

## 🏕️ Back flap notes

### Using this guide

- Go in order, more or less.
- Do not skip the [getting started](#getting-started) section!
- Snippets like `bash --version` are meant to be run from the command line.
- Be sure to install [Homebrew](http://brew.sh) and [Homebrew Cask](https://caskroom.github.io).
- [MIT OCW](https://ocw.mit.edu/index.htm) also hosts all their [lectures on YouTube](https://www.youtube.com/user/MIT), where you can watch at up to 2x speed.
- These topics and resources are a subjective view of what has been helpful. Feel free to contribute!

### Why a travel guide

Learning to build software is hard. And not knowing what to learn, when, and from where makes it harder. Google searches return 1000's of results, but knowing which links to trust is unlear. That's where the travel guide comes in: a listing of what to learn, in an ordering that makes sense, paired with specific, curated resources. This isn't a resource dump—it's a travel guide.

### Contributing

- Fork, make changes, submit pull request

### License

- [MIT License](https://opensource.org/licenses/MIT)

### Authors

- Compiled by [Hunter Gatewood](http://hcgatewood.me/about/)
