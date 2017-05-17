# The New Programmer's Travel Guide

A minimal, curated guide to relevant resources for the new computer science student.

This guide assumes you're on a Mac, but is valuable on any machine. See the [back flap notes](#using-this-guide) for an overview of this guide.

## 🗺️ Front flap topic map

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
- [Profiling](#profiling)
- [Software development](#software-development)

### More technical

- [Vim](#vim)
- [Tmux](#tmux)
- [IRC](#irc)
- [Blockchain](#blockchain)
- [Miscellanea](#miscellanea)


## 🏖️ Topic itinerary

### Getting started

A healthy mentality makes everything easier. Topics include learning to ask effective questions as well as taking a growth-based approach to learning.

- [Take a growth mindset](https://medium.freecodecamp.com/this-picture-will-change-the-way-you-learn-to-code-557ac1e109bd)
- [Great advice for new CS students](https://www.quora.com/What-advice-would-you-give-to-a-Computer-Science-major-student-that-you-wish-you-were-given-when-you-started-Computer-Science)
- [How to ask programming questions](https://www.propublica.org/nerds/item/how-to-ask-programming-questions)
- [How to find answers from Stack Overflow](https://meta.stackexchange.com/questions/5180/what-are-some-good-tips-for-searching-stack-overflow)
- [Rubber duck problem solving](http://blog.codinghorror.com/rubber-duck-problem-solving/)
- [Thoughts on dealing with failure](http://hcgatewood.me/014-failure/)
- [Lots of good, short introductions with further resources](https://learnxinyminutes.com)
- [Huge list of resources on many topics](https://github.com/sindresorhus/awesome)

### Homebrew

[Homebrew](https://en.wikipedia.org/wiki/Homebrew_(package_management_software)) is a popular [package manager](https://en.wikipedia.org/wiki/Package_manager) for the Mac operating system. It makes installing things as easy as `brew install <package>`. Similarly, Homebrew Cask facilitates installing GUI applications.

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

- [Intro video 1](https://www.youtube.com/watch?v=x73WTEltyHU)
- [Intro video 2](https://www.youtube.com/watch?v=q7-aEspwwEI)
- [Basic commands](http://www.tldp.org/LDP/abs/html/basic.html)
- [Interactive tutorial](https://www.codecademy.com/learn/learn-the-command-line)
- [Reference manual](http://www.faqs.org/docs/bashman/bashref.html#SEC_Top)
- [Overview](http://linuxcommand.org/learning_the_shell.php)
- [Cheatsheet](https://learnxinyminutes.com/docs/bash/)
- [Difference between shell, terminal, console](https://superuser.com/questions/144666/what-is-the-difference-between-shell-console-and-terminal)
- [Cmder, a bash-style shell for windows](http://cmder.net)
- [Tldr, the better version of man pages](http://tldr-pages.github.io)
- [Dotbot, a dotfile manager](https://github.com/anishathalye/dotbot/)

### Git

[Git](https://git-scm.com) is a [distributed](https://en.wikipedia.org/wiki/Distributed_computing) [version control](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) system. Version control allows multiple people to work on the same code base at the same time, among other benefits. Git is [wildly popular](https://insights.stackoverflow.com/survey/2017#work-version-control), powerful, and somewhat notorious for being [difficult to learn](https://www.quora.com/Why-is-Git-so-hard-to-learn).

- Install: `brew install git`
- [Conceptual intro](https://backlogtool.com/git-guide/en/intro/intro1_1.html)
- [Intro to version control](http://web.mit.edu/6.005/www/fa16/classes/05-version-control/)
- [Functional intro](http://rogerdudler.github.io/git-guide/)
- [Interactive tutorial](https://try.github.io/)
- [Cheatsheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)
- [Documentation](https://git-scm.com/documentation)
- [Git is not GitHub](http://stackoverflow.com/questions/13321556/difference-between-git-and-github)
- [Effective commit messages](http://chris.beams.io/posts/git-commit/)
- [Version control in a team](http://web.mit.edu/6.005/www/fa16/classes/27-team-version-control/)
- [GitHub Flow, a popular git workflow](https://guides.github.com/introduction/flow/)

### Python

[Python](https://en.wikipedia.org/wiki/Python_(programming_language)) is a [popular](https://insights.stackoverflow.com/survey/2017#most-popular-technologies), general-purpose, high-level programming language. It's also a [great first language](http://effbot.org/pyfaq/is-python-a-good-language-for-beginning-programmers.htm).

- Install: `brew install python3`
- [Google's official Python tutorial](https://developers.google.com/edu/python/)
- [Official tutorial](https://docs.python.org/3/tutorial/index.html)
- [Intro to programming class](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-00-introduction-to-computer-science-and-programming-fall-2008/)

### Debugging

[Debugging](https://en.wikipedia.org/wiki/Debugging) is the process of tracking down and fixing [bugs](https://en.wikipedia.org/wiki/Software_bug). Rather than a series of ad hoc actions, debugging is a [much-discussed concept](https://news.ycombinator.com/item?id=11729806) that can [take up a large portion of time spent developing](https://softwareengineering.stackexchange.com/questions/91758/debugging-facts-and-statistics).

- [Avoiding bugs](http://web.mit.edu/6.005/www/fa16/classes/08-avoiding-debugging/)
- [General strategy](http://web.mit.edu/6.005/www/fa16/classes/10-debugging/)
- [Python debugging tips](http://stackoverflow.com/questions/1623039/python-debugging-tips)
- [Pdb, the Python builtin debugger](https://docs.python.org/3/library/pdb.html)
- [Gdb, a debugger for many compiled languages](https://www.gnu.org/software/gdb/)
- [Intro to gdb](https://www.youtube.com/watch?v=sCtY--xRUyI)
- [Overview of Chrome DevTools, including debugger](https://developer.chrome.com/devtools)

### Getting a job

Proper preparation makes getting a job much easier. Topics include best practices, a nice resume template, practice questions, and a list of companies with a short application.

- [Overview of the process, best practices](https://github.com/gu-app-club/lets-learn-jobs)
- [LaTeX resume template](https://www.overleaf.com/latex/templates/deedy-resume/sqdbztjjghvz#.WQNvMVIUVE5)
- [List of action verbs for descriptions](http://career.opcd.wfu.edu/files/2011/05/Action-Verbs-for-Resumes.pdf)
- [General resume tips](https://www.quora.com/What-are-some-examples-of-a-computer-science-students-resume-that-received-an-internship-at-Google)
- [Great site for technical interview practice](https://www.interviewcake.com)
- [Big list of CS companies with an easy application process](https://github.com/j-delaney/easy-application)
- [Intro to algorithms class](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/)

### Communicating

Design, development, research, and everything in between rely on effective communication between peers. Topics include how to present publicly, accept criticism, and write a quality [README](https://en.wikipedia.org/wiki/README).

- [Best practices for competent public speaking](https://www.gsb.stanford.edu/insights/big-data-approach-public-speaking)
- [Proper use of body language](https://www.youtube.com/watch?v=cFLjudWTuGQ&t=1s)
- [Best practices for group ideation](https://challenges.openideo.com/blog/seven-tips-on-better-brainstorming)
- [Accepting criticism](https://medium.com/the-year-of-the-looking-glass/taking-feedback-impersonally-7c0f3a8199d9)
- [Writing a README, with examples](https://github.com/matiassingers/awesome-readme)

### Web development

[Web development](https://en.wikipedia.org/wiki/Web_development) refers to building some component of a [web site](https://en.wikipedia.org/wiki/Website) for the [World Wide Web](https://en.wikipedia.org/wiki/World_Wide_Web). It's a [hot occupation as of 2016](https://www.bls.gov/ooh/computer-and-information-technology/web-developers.htm).

- [What is a web app](https://www.youtube.com/watch?v=RsQ1tFLwldY)
- [Web developer roadmap](https://github.com/kamranahmedse/developer-roadmap)
- [Dash, an on-command documentation reader for Macs](https://kapeli.com/dash)
- [Sample real-world apps in various stacks](https://github.com/gothinkster/realworld)
- [Disable browser caching](http://stackoverflow.com/questions/5690269/disabling-chrome-cache-for-website-development)
- [Internet vs World Wide Web](https://www.youtube.com/watch?v=laepk9KrAZY)
- [HTTP and HTTPS](https://www.youtube.com/watch?v=po3zYOe00O4)
- [APIs](https://www.youtube.com/watch?v=7YcW25PHnAA)
- [REST APIs](https://www.youtube.com/watch?v=YCcAE2SCQ6k)
- [TCP/IP](https://www.youtube.com/watch?v=PpsEaqJV_A0)
- [IPv4 vs. IPv6](https://www.youtube.com/watch?v=aor29pGhlFE)
- [Web development class](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-170-software-studio-spring-2013/)
- [Computer systems class](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-033-computer-system-engineering-spring-2009/)

### HTML/CSS

[HTML](https://en.wikipedia.org/wiki/HTML) and [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets), along with JavaScript, form the cornerstone technologies of the World Wide Web. Many newer software libraries are built on top of these languages, but learning the basic building blocks is still essential.

- [Intro and overview](https://internetingishard.com/html-and-css/)
- [Hello-world HTML/CSS app](https://www.youtube.com/watch?v=wrdR5Su_Stg)
- [How layout works](http://learnlayout.com)
- [HTML in-depth](http://www.w3schools.com/html/default.asp)
- [Centering things](https://css-tricks.com/centering-css-complete-guide/)
- [Bootstrap, a popular framework making HTML/CSS easier](http://getbootstrap.com)

### JavaScript

[JavaScript](https://en.wikipedia.org/wiki/JavaScript) is the programming language of the World Wide Web, and can also be run outside of a [browser](https://en.wikipedia.org/wiki/Web_browser) with Node.js. It's high-level, general purpose, and the [most popular programming language of 2017](https://insights.stackoverflow.com/survey/2017#most-popular-technologies).

- [Intro](http://jsforcats.com)
- [Intro book](http://bdcampbell.net/javascript/book/javascript_the_good_parts.pdf)
- [Interactive tutorial](http://eloquentjavascript.net)
- [Hub for tutorials, tools, references](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [How the var keyword works](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var)
- [Promises](http://exploringjs.com/es6/ch_promises.html)
- [Style guide](https://github.com/airbnb/javascript#whitespace)

### Node.js

[Node.js](https://en.wikipedia.org/wiki/Node.js) is a [cross-platform](https://en.wikipedia.org/wiki/Cross-platform) JavaScript [run-time environment](https://en.wikipedia.org/wiki/Runtime_system). In other words, while JavaScript was traditionally limited to the client-side browser, Node.js provides an environment allowing execution of JavaScript code on the [server-side](https://en.wikipedia.org/wiki/Server-side). [Npm](https://en.wikipedia.org/wiki/Npm_(software)) is the default [package manager](https://en.wikipedia.org/wiki/Package_manager) for Node.js.

- Install: `brew install node`
- [Intro video](https://www.youtube.com/watch?v=pU9Q6oiQNd0)
- [Overview](https://github.com/maxogden/art-of-node#the-art-of-node)
- [Npm, the Node Package Manager](https://docs.npmjs.com/getting-started/what-is-npm)
- [Interactive tutorial](https://github.com/workshopper/learnyounode#learn-you-the-nodejs-for-much-win)
- [In-depth tutorial](https://www.tutorialspoint.com/nodejs/nodejs_introduction.htm)

### Profiling

[Profiling](https://en.wikipedia.org/wiki/Profiling_(computer_programming)) is the process of measuring, aggregating, and interpreting data on a program's space and time usage. It's an important tool for [performance engineers](https://en.wikipedia.org/wiki/Performance_engineering), but is also used across development fields, including in web development.

- [Intro to Python profiling video](https://www.youtube.com/watch?v=QJwVYlDzAXs)
- [line_profiler, a line-by-line profiling tool for Python](https://github.com/rkern/line_profiler)
- [General Python profiling information](http://stackoverflow.com/questions/582336/how-can-you-profile-a-python-script)
- [Flame graph](http://www.brendangregg.com/FlameGraphs/cpuflamegraphs.html)
- [Chrome DevTools JavaScript profiler](https://developers.google.com/web/tools/chrome-devtools/rendering-tools/js-execution)
- [Perf, a Linux profiling tool](https://perf.wiki.kernel.org/index.php/Tutorial#Sampling_with_perf_record)
- [Cachegrind, a cache and branch-prediction profiler](http://valgrind.org/docs/manual/cg-manual.html)
- [General C/C++ profiling information](http://stackoverflow.com/questions/26663/whats-your-favorite-profiling-tool-for-c)
- [In-depth lectures on performance engineering](https://www.youtube.com/playlist?list=PLD2AE32F507F10481)

### Software development

[Software development](https://en.wikipedia.org/wiki/Software_development) is the process of designing, constructing, testing, and releasing software. At scale, many inconsequential issues turn into colossal problems without proper software development techniques.

- [Intro to testing](http://web.mit.edu/6.005/www/fa16/classes/03-testing/)
- [Difference between unit, integration, functional, acceptance tests](http://stackoverflow.com/questions/4904096/whats-the-difference-between-unit-functional-acceptance-and-integration-test)
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
- [Advice on making a vimrc](http://dougblack.io/words/a-good-vimrc.html)
- [Vimrc with more features](https://github.com/amix/vimrc)
- [Intermediate topics](https://www.cs.oberlin.edu/~kuperman/help/vim/home.html)
- [Screencasts on various topics](http://vimcasts.org/categories/)

### Tmux

[Tmux](https://en.wikipedia.org/wiki/Tmux) is a shell program that allows switching between and detaching of virtual consoles.

- [Intro video](https://www.youtube.com/watch?v=BHhA_ZKjyxo)
- [Intro article](https://danielmiessler.com/study/tmux/#gs.t5PZaUE)
- [Cheatsheet](https://gist.github.com/MohamedAlaa/2961058)

### IRC

[IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat) is an [application layer protocol](https://en.wikipedia.org/wiki/Application_layer) (same layer as the World Wide Web) facilitating text-based communication. Although it's less popular now than in the past, many open source projects communicate using the [freenode](https://en.wikipedia.org/wiki/Freenode) IRC [network](https://en.wikipedia.org/wiki/Computer_network). [Slack](https://slack.com) is a popular, easy to use, [proprietary](https://en.wikipedia.org/wiki/Proprietary_software) alternative for team communication.

- [Intro video](https://www.youtube.com/watch?v=Ltq0hMgizi0)
- [General overview and help](http://www.irchelp.org)
- [Irssi, a terminal-based IRC client](https://irssi.org)
- [Foonetic, a decent first network](http://foonetic.net)
- [Irssi intro video](https://www.youtube.com/watch?v=f0CWZAE3FEs)
- [Irssi quick commands](https://www.linode.com/docs/applications/messaging/using-irssi-for-internet-relay-chat)
- [Irssi in-depth commands](https://irssi.org/documentation/startup/#first-steps)
- [Irssi FAQ, including startup commands and scripts](https://irssi.org/documentation/faq/)
- [Vim keybindings in irssi](https://github.com/shabble/irssi-scripts/tree/master/vim-mode#___top)
- [Irssi + tmux](https://coderwall.com/p/t1c7-w/persistent-irc-history-with-irssi-and-tmux)

### Blockchain

A [blockchain](https://en.wikipedia.org/wiki/Blockchain) is a continuously growing list of [timestamped](https://en.wikipedia.org/wiki/Timestamp) "blocks." Each block functions as a [record](https://en.wikipedia.org/wiki/Record_(computer_science)), allowing a blockchain to function as a [distributed database](https://en.wikipedia.org/wiki/Distributed_database). The idea of a blockchain is relatively new, first described in 2008 by an unknown person using the assumed pseudonym [Satoshi Nakamoto](https://en.wikipedia.org/wiki/Satoshi_Nakamoto). [Bitcoin](https://en.wikipedia.org/wiki/Bitcoin), on the other hand, is the [original](https://bitcoin.org/bitcoin.pdf) in a long line of [cryptocurrencies](https://en.wikipedia.org/wiki/Cryptocurrency) utilizing blockchain technology.

- [Intro video](https://www.youtube.com/watch?v=_160oMzblY8)
- [Intro to Bitcoin](https://www.youtube.com/watch?v=Lx9zgZCMqXE)
- [Bitcoin vs. Ethereum](https://www.youtube.com/watch?v=-SMliFtoPn8)
- [Intro to Ethereum](https://www.youtube.com/watch?v=66SaEDzlmP4)
- [What Ethereum can be](https://steemit.com/ethereum/@hexayurt/what-does-ether-usd100-mean)

### Miscellanea

Miscellaneous resources. Topics include technical discussions, how to use macros in C, and a recommendation of Google Scholar for organizing technical papers.

- [Google Scholar, a free scholarly literature browser](https://scholar.google.com)
- [Floating point representations](http://www.toves.org/books/float/)
- [Interpreted vs. compiled](http://stackoverflow.com/questions/3265357/compiled-vs-interpreted-languages)
- [C macros](https://gcc.gnu.org/onlinedocs/cpp/Macros.html)
- [Serverless architecture](https://martinfowler.com/articles/serverless.html)

## 🏕️ Back flap notes

### Using this guide

- Go in order, more or less.
- Snippets like `bash --version` are meant to be run from the command line.
- Be sure to install [Homebrew](http://brew.sh) and [Homebrew Cask](https://caskroom.github.io).
- [MIT OCW](https://ocw.mit.edu/index.htm) also hosts all their [lectures on YouTube](https://www.youtube.com/user/MIT), where you can watch at up to 2x speed.
- These topics and resources are a subjective view of what has been helpful. Feel free to contribute!

### Contributing

- Fork, make changes, submit pull request

### Authors

- Compiled by [Hunter Gatewood](http://hcgatewood.me/about/)
