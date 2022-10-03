# Class 3 Reading Notes - *Revisions and the Cloud*

## **Git Tutorial**

## Version Control

**Version Control:** a system that allows you to revisit various verions of a file by recording changes. This allows you to revert a file/project to a previous version, track modifications & who made those changes, and compare changes. Using a Version Control System (VCS) mistakes or deleted information is esily fixed and collaboration between multiple people is simplified.

- **Local Version Control:** Outdates system in which a local VCS uses 1 database on your hard disk that stores changes and file data
- **Centralized Version Control (CVCS):** A system which allows for a single server to store all changes and file data which can be accessed by multiple users.
- **Distributed Version Control (DVCS):** This system addresses the flaw or weak point of a CVS: the server is a single point of failure. If a CVS server crashes, users cannot share work or save new changes. A DCVS fixes this by allowing clients to create *mirrored repositories* or data backups in case of a server error.

### So What is Git?

**Snapshots**: Git is a DVCS that stores data in a file system made up of *snapshots*. Each time you save a new version of a project (aka a commit) Git makes a snapshot of this file and references it for future use.

**States**: Files in Git can exist in three (3) main states.

1. Committed: Data is securely stored in a local database.
2. Modified: File has been changed, but not committed/saved to the database.
3. Staged: Flagged a file's changed version to be committed/saved in the next snapshot.

***Pop Quiz: Do you remember exponents?***

1. 2<sup>2</sup> = 4
2. 2<sup>3</sup> = 8
3. 2<sup>4</sup> = ?

## History of Git

Git's history begins with an open source software project called Linux kernel. Project developers started using a DVCS called BitKeeper in 2002, but in 2005 this stopped due to personal tensions. Following this, Linus Torvalds (chief developer of Linux kernel) started making Git. Since it's development, Git has become one of the most utilized Version Control Systems in the world with millions of users.

## Setting up a Git Repository

### Cloning

A copy of an existing Git respository can be cloned down to a computer server using the clone command with a repository's URL: 
> `git clone [Git repository URl]`

## Workflow

### Useful Git Tips in the Terminal

- command: `git status`
    - This command checks if there are unsaved changes/edits. What is the status of my Git project or Git files?

> We need to ‘ACP’ our changes: Add, Commit, Push!

1. command: `git add [file name]`
    - Selects the file which a user wants to begin saving. 
    - Multiple files can be selected by adding a space between file names. E.g. `git add file1 file2`
2. command: `git commit -m “Message goes here”`
    - Adds a commit comment which is a brief description of changes made to a project.
    - In order to commit **ALL** changes use the following command: `git commit -a` 
3. command: `git push origin main`
    - Sends/Pushes changes from VS Code terminal on my computer up to the GitHub server.

Exclamation marks will break code unless needed for a specific function. 

1. command: `git pull origin main`
    - Pulls changes from GitHub down to our computer which can then be edited on VS Code

### *"Git"uations*

If changes are not properly consolidated between GitHub and VSCode then the request will break

3 Ways to Fix "Git"uations:

1. command: `git config pull.rebase false`
    - \# merge
    - Recommend using this one so that changes can be edited as much/little as you want
2. command: `git config pull.rebase true`
    - \# rebase
3. command: `git config pull.ff only` 
    - \# fast-forward only