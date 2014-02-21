Guides or How to Keep a Beautiful Code Garden
======

Guides for getting things done, programming well, and programming in style.

* [Code Review](/code-review)
* [Best Practices](/best-practices)
* [Sandi Metz' Rules](/sandi-metz-rules)

A note on the language:

* "Avoid" means don't do it unless you have good reason.
* "Don't" means there's never a good reason.
* "Prefer" indicates a better option and its alternative to watch out for.
* "Use" is a positive instruction.

TechLabs Code Philosophy Overview:

* We follow Sandi Metz' rules for [development and testing](/sandi-metz-rules)
* Test come first: They're written first and they're refactored first.
* Bugs are not fixed until tests are written to prevent it from happening again.
* Test the happy and sad paths for every user story.
* Branch from the development branch when working on new features.
* Avoid branching from the master branch unless it's for a hotfix bug.
* Conduct a code review before merging your branch into the codebase.
* Make meaningful [git commit messages]
* Run your test suite before and after merging.
* Don't rewrite existing code to follow this guide.
* Don't violate a guideline without a good reason.
* A reason is good when you can convince a teammate.

[git commit messages]: http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html

Credits
-------

Adapted from thoughtbot's guides. Much thanks guys!

License
-------

Distributed under the [Creative Commons Attribution License](http://creativecommons.org/licenses/by/3.0/).
