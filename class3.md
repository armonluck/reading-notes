# Class 3 Reading Notes - *Revisions and the Cloud*

## **Git Tutorial**

## Version Control

**Version Control:** a system that allows you to revisit various verions of a file by recording changes. This allows you to revert a file/project to a previous version, track modifications & who made those changes, and compare changes. Using a Version Control System (VCS) mistakes or deleted information is esily fixed and collaboration between multiple people is simplified.

- **Local Version Control:** Outdates system in which a local VCS uses 1 database on your hard disk that stores changes and file data
- **Centralized Version Control (CVCS):** A system which allows for a single server to store all changes and file data which can be accessed by multiple users.
- **Distributed Version Control (DVCS):** This system addresses the flaw or weak point of a CVS: the server is a single point of failure. If a CVS server crashes, users cannot share work or save new changes. A DCVS fixes this by allowing clients to create *mirrored repositories* or data backups in case of a server error.

### So What is Git?

**Snapshots**: Git is a DVCS that stores data in a file system made up of *snapshots*. Each time you save a new version of a project (aka a commit) Git makes a snapshot of this file and references it for future use.

**Local Operations**:

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

## Workflow

## Remote Repositories

