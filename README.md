# Hello Github!

This is a text file that we are going to add to Git.

We will use Git to record all of the versions of this file,
letting us move back and forth through time.

For example, in this first version of the file we
will say that the cat goes mieow. Apparently.


"L'abuso è la porta del vizio" - Oscar Wild


## Workflow

The "normal" workflow when using Git on your own is;

* `git pull` new versions from the cloud repository
* Now make changes to your files as you would normally.
* `git commit -a` your changes.
* `git status` to ensure that your working directory is clean.
* `git push` to push your changes back up to the cloud.

## Workflow (multi-user)

A good workflow when working on a shared GitHub repository is

* `git status` to ensure your working directory is clean. If it isn't,
   then clean it up and `git commit -a` any changes.
* `git pull` the latest changes from other people. If there are any
  conflicts, then merge them now, then `git commit -a` and `git push`
  the merges to the cloud.
* Make changes to your files as you want.
* `git commit -a` your changes, and use `git status` to then ensure
  that your working directory is clean.
* `git pull` to pull in any changes that anyone else has made while 
  you were working. If there are any conflicts, then resolve those 
  conflicts and `git commit -a` until your working directory is clean.
* When `git pull` causes no changes and `git status` shows your working
  directory is clean, then use `git push` to push your work to the cloud
  repository.

***


