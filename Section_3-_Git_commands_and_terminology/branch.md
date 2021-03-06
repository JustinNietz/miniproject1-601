# Branch

Nearly every VCS supports branching. **Branching** means you *diverge, or separate, from the main line* of development
and continue to do work without messing with that main line.

In many VCS tools, this is a somewhat expensive process, often requiring you to create a new copy of your source code
directory, which can take a long time for large projects.

Some people refer to Git’s branching model as its **killer feature**,and it certainly sets Git apart in the VCS
community. The way Git branches is incredibly lightweight, making branching operations nearly instantaneous, and
switching back and forth between branches generally just as fast.

Unlike many other VCSs, Git encourages workflows that branch and merge often, even multiple times in a day.
Understanding and mastering this feature gives you a powerful and unique tool and can entirely change the way that you
develop.

## Command to Create a new Branch in Git

    $ git branch <new-branch-name>

## Switching Branches

![Switching Branches](Images/branch.png)

*A visualization of understanding branches.*

To switch to an existing branch, you run the git checkout command. To switch to the new testing branch:

    $ git checkout testing

This moves **HEAD** to point to the testing branch.
