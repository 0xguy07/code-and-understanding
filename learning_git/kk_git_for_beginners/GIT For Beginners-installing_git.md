# GIT For Beginners
## Installing Git

### Installing Git

You can install Git by:

1. Installing from the website
2. Installing from Homebrew
    - `brew install git`
    - `git --version` -- ensure git is installed
    - `brew update git`

I won't cover the install of Git here, because I already have it installed on both machines. 

### Lab Introduction

#### Lab: Install GIT

1. Check OS version

```
sarah@dev01 ~ ➜  cat /etc/os-release 
NAME="Alpine Linux"
ID=alpine
VERSION_ID=3.22.2
PRETTY_NAME="Alpine Linux v3.22"
HOME_URL="https://alpinelinux.org/"
BUG_REPORT_URL="https://gitlab.alpinelinux.org/alpine/aports/-/issues"
```
Due to the lab, I think we get a different answer with this command:

```
sarah@dev01 ~ ➜  uname -a
Linux dev01 6.8.0-90-generic #91~22.04.1-Ubuntu SMP PREEMPT_DYNAMIC Thu Nov 20 15:20:45 UTC 2 x86_64 Linux
```

2. Check GIT Version

```
sarah@dev01 ~ ➜  git --version
git version 2.49.1
```

3. Using Git Help to list different objects

```
sarah@dev01 ~ ✖ git --help
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--no-lazy-fetch]
           [--no-optional-locks] [--no-advice] [--bare] [--git-dir=<path>]
           [--work-tree=<path>] [--namespace=<name>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   restore    Restore working tree files
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   diff       Show changes between commits, commit and working tree, etc
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   backfill   Download missing objects in a partial clone
   branch     List, create, or delete branches
   commit     Record changes to the repository
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   reset      Reset current HEAD to the specified state
   switch     Switch branches
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.
```

### Lab Learning Summary

1. Show various types of objects:
    - `git show`
2. List, create, or delete branches:
    - `git branch`
3. Download objects and refs from another repository:
    - `git fetch`
4. Create an empty Git repository or reinitialize an existing one:
    - `git init`
5. Create a bare git init:
    - `git init --bare`

### Lab Learning Questions

1. What is an **Object**?
2. What is a **Branch**?
3. What is the purpose of a *bare* git repository?

### Thoughts

Very helpful for getting started with git. The lab was useful for not only git, but for reinforcing linux cli commands. This is the issue with relying on **Artificial Intelligence** like **Claude Code** or **Codex** too much is forgetting the **steps** in a *process* and *why* you're doing them. 
