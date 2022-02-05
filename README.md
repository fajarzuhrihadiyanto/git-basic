# About Module
This module is a basic git material include instalation and basic commands

# Installation
Download link - https://git-scm.com/downloads

# About Version Control System and Git
## What is version control system ?
Version Control System is a system that record all changes of a set of files that will be tracked. 

## Why using version control system ?
- Keep our code tracked and managed
- Easy collaborating

## What is git ?
Git is just one of several kind of version control system. There is also another version control system, like subversion and mercury

# Basic Command
## clone
Clone is command to clone online repository to our local repository.
To clone from repository, type command :
~~~
git clone <repository> [<directory>]
~~~
- ```<repository>``` git urls refer to the repository we want to clone from
- ```<directory>``` directory on our local machine

Learn more about clone here : https://git-scm.com/docs/git-clone

## fetch
Fetch is command to fetch refs (branch and/or tags) from one or more repository (in this case, remote repository).
Simply, we can track remote repository using fetch command. To fetch from remote repository, type command :
~~~
git fetch [<option>]
~~~

Learn mode about fetch here : https://git-scm.com/docs/git-fetch

## pull
Pull is command to fetch and integrate from remote repository to our local repository.
To pull from remote repository, type command :
~~~
git pull [<options>]
~~~

Learn more about pull here : https://git-scm.com/docs/git-pull

## add
Add is command to add new file or modified file from our local repository to index (staging area).
This command will not change current repository until commit.
To add file(s), type command :
~~~
git add [<pathspec>…​]
~~~
- ```[<pathspec>…​]``` file(s) path to be added

Learn more about add here : https://git-scm.com/docs/git-add

## commit
Commit is a command to record change(s) to the repository.
Only file(s) in staging area will be committed to the current repository, so make sure to add file to staging area before commit.
This commit will just applied to local repository, not remote repository.
To commit change(s), type command :
~~~
git commit [--all] [-m <msg>]
~~~
- ```[--all]``` stage all modified files. Untracked files will not be considered
- ```[-m <msg>]``` commit message

Learn more about commit here : https://git-scm.com/docs/git-commit

## push
Push is a command to update remote repository refs with a local repository refs.
To push commits to remote repository, type command :
~~~
git push
~~~

Learn more about push here : https://git-scm.com/docs/git-push
