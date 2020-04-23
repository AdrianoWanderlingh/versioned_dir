# Hello Github!

This is a text file that we are going to add to Git.

We will use Git to record all of the versions of this file,
letting us move back and forth through time.

For example, in this first version of the file we
will say that the cat goes mieow. Apparently.


"L'abuso è la porta del vizio" - Oscar Wild

## What Github can be used for

Now that you have begun using Git I hope that you can see
that it can be a really useful tool for researchers and programmers.

Consider using Git to version control your

* Papers
* Research proposals
* Course / website material
* Research outputs (graphs, datafiles)
* Scripts
* Lab notes
* Software projects

As with all things, you will learn more about and become more comfortable
with Git the more you use it. Taking a little pain now to add it to
your workflow will give you a lot of benefit later on. 
At the very least it
will save you from losing some work if your computer hard disk fails.


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

## Ideal Workflow (multiuser): branch and pull-request

The best way to use Git and GitHub for a multi-user project is
to make a lot of use of temporary branches and pull requests.

Whenever you want to implement a new feature, you should create
a new temporary branch. Give this branch a name that gives some
idea of who you are, and what feature you are implementing. Then,
make the changes, committing and pushing regularly.

When you have finished, do what you can to merge as much as possible
from `master` into your new feature branch. As far as possible, you
want your pull request to be automatically mergeable.

Then, issue a pull request, giving a useful message to other developers
to encourage them to put effort into merging your changes. Participate
in the resulting discussion on the pull request forum, and help
merge in all of the code.

Once ready, merge the pull request with the co-operation and help 
of other developers (and normally the blessing of the person/group that
manages `master`). Once merged, close the pull request and delete
the temporary branch.

While Git cannot help with the social problems of working on a multi-person
project, the above process of "branch and pull-request" makes it as
painless as possible, particularly if you have good communication 
in the pull request forum.


***


