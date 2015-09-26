# Git Tips

Git is crucial to any programming project since it'll allow you to save versions
of your work. Commit your work at crucial junctures, and if you get in over your
head with a new feature, you can easily go back in time to the last working
version of your project (among many other awesome features).

## Install git

If you've followed the [Python installation instructions
here](https://github.com/limedaring/HelloWebApp/tree/master/installation-instructions),
you should have brew, so you can easily run `brew install git` in your terminal.
Not on a Mac or don't have brew? [Check out these
instructions.](http://git-scm.com/book/en/Getting-Started-Installing-Git)

## The very basic, important commands

* **git init**: Starts a git repository in your current folder. Essentially,
  starts tracking changes in your project. Make sure you're at the top level
folder for your project (and only track individual projects, don't init your
entire computer. :P)
* **git status**: Shows the current state of your project - which files have
  changes, which have been added, and which branch you're on.
* **git add [FILE]**: Adds files to be tracked - new files aren't tracked by
  default. You can add all new files using `git add .` rather than naming the
individual files as well. 
* **git commit [FILE]**: Commits the changed files - use when you've hit a good
  state. Generally, you'll want to commit all files and add a message, so you
can use `git commit -a -m "Message!"` to do that (-a commits all files, -m
indicates that you're adding a message.)

## More!

There are pretty much a billion other awesome commands, [check them out
here](http://gitref.org/). 
