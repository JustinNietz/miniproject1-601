# Repository

A repository, or Git project, encompasses the entire collection of files and folders associated with a project, along
with each file’s revision history.

Using the command line or other ease-of-use interfaces, a git repository also allows for: interaction with the history,
cloning, creating branches, committing, merging, comparing changes across versions of code, and more.

Working in repositories keeps development projects organized and protected. Developers are encouraged to fix bugs, or
create fresh features, without fear of derailing mainline development efforts. Git facilitates this through the use of
topic branches: lightweight pointers to commits in history that can be easily created and deprecated when no longer
needed.

There are two types of repositories:

• **Local repository** — another term for where you keep your copy of a Git repository on your workstation.

• **Remote repository** — a secondary copy of a Git repository where you push changes for collaboration or backup.

## Command to Initialize a Repository

If you have a project directory that is currently not under version control and you want to start controlling it with
Git, you first need to go to that project’s directory. If you’ve never done this, it looks a little different depending
on which system you’re running:

For Linux:

    $ cd /home/user/my_project

For macOS:

    $ cd /Users/user/my_project

For Windows:

    $ cd C:/Users/user/my_project

And type:

    $ git init
