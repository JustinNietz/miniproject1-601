# Remote

The `git remote` command helps us to manage connections to remote repositories. It shows us which remotes are currently
connected to each other, but also it gives an opportunity for us to add new connections or remove existing
ones. `Git remote` is essentially an interface for managing a list of remote entries that are stored in the
repository's `./.git/config` file.

## How to use

Remote connections act like bookmarks into other repositories. Instead of providing real-time access to another
repository, they serve as convenient names that can be used to reference a less convenient URL. We use these subcommands
below most of the time.

### Remote Show

    $ git remote -v 

By default, this command provides a list of remote repositories using their `short-names` (
e.g. `origin`). However, adding the `-v` option to the command, we will also see the remote's URLs in listings.

`Git remote -v` in action:

![]() 

### Remote Add

    $ git remote add <short-name> <url>

This command creates a new connection to a remote repository. So next time when we are referencing the remote, we can
use this `short-name` instead of the long URL. The most typical default as a `short-name` is `origin`.

### Remote Remove

    $ git remote rm <name>

Due to this command, the remote named will be disconnected from the local repository. All remote-tracking branches and
configuration settings for the remote will be removed.

