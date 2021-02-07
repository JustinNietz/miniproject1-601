# Git <img src="Images/git_logo.png" alt="git logo" width= 50 height=50>

Git is a **DVCSs** (Distributed Version Control System) that saves data as a *series of snapshots*.

Every time you **commit**, or *save the state of your project*, Git takes a picture of what all your files look like at
that moment and stores a reference to that snapshot. Git does not store files again if they have not been changed.

## Brief History

* **2002**: The Linux kernel project began using a proprietary DVCS called **BitKeeper**.
* **2005**: Tensions between the company that developed BitKeeper and the community that built Linux broke down.
* The Linux development community, including Linus Torvalds, the creator of Linux, created Git based on the lessons they
  learned while using BitKeeper.

## How to use

### Setting up username and email:

    $ git config -global user.name "Your name"


    $ git config -global user.email "Your email"

This is a one time setup so that when you make a project, your name and email will be associated with it.

### To initialize an Existing Directory:

    $ cd C:/Users/user/my_project

    $ git init

The command `git init` will allow Git to start tracking your project.

### To clone an Existing Repo

    $ git clone https://github.com/someone/someone'srepo

You can use `git clone` when you want to clone a repo from **Github**.

---

*For many other commands, refer to this book **[here.](https://git-scm.com/book/en/v2)***

---

## How Git improves productivity

Version control systems record changes to a file or set of files over time so that you can recall specific version
later. Before DVCSs, there were **Local Version Control Systems** and **CVCSs** (Centralized Version Control Systems).

**Local Version Control** keep all changes to files under revision control on one computer.

**CVCSs** have a single server that contains all the versioned files.

Both of these methods have **major flaws**:

For one, If the server goes down, no one can work on any projects until the server comes back online.

Also, if the hard disk becomes corrupted, you risk the chance that entire databases become unusable and cannot be
recovered.

With DVCSs like Git, each client who accesses the information *fully mirror* the repository including its full history.
Each and every **clone** is a full backup of all the data. You also do not need to be connected to the internet or be in
the same building or even the same time zones to work on projects together. Git makes collaboration effortless.

The five lessons the Linux development community used in creating Git were: **Speed**, **Simple Design**, **Strong
support for non-linear development**, **Fully Distributed**, and able to handle large projects like the Linux kernel
**Efficiently**.

## Three main sections of a Git Project

**The working tree**
: a single checkout of one version of the project.

**The staging area**
: a file that stores info about what will go into your next commit.

**The Git directory**
: where Git stores the metadata and object database for your project. It is what is copied when you clone a repository
from another computer.

![Git sections](Images/git_sections.png)

*The image above demonstrates the way each section interacts with each other.*
