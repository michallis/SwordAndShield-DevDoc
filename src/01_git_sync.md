# Git Sync

## Introduction

Git is used to collaborate on the project. It is a distributed version control system that allows developers to track changes to code, collaborate on projects, and manage different versions of the codebase.

### The mental flow is
- check if a team member has updated changes on the central repository
- pull the latest changes from the remote repository
- check if you still have uncommitted changes.
- stage all local changes
- commit local changes
- push local changes to remote repository

### Simple flow - update your local files to the central repository

- stage all local changes
- commit local changes
- push local changes to remote repository

### Simple flow - pull changes from the central repository

- pull the latest changes from the remote repository
- check if you still have uncommitted changes.
- stage all local changes
- commit local changes
- push local changes to remote repository

## References

- [Git Documentation](https://git-scm.com/doc)
- [Git Tutorial](https://www.atlassian.com/git/tutorials)
- [Fork Client](https://git-fork.com/) 

Any Git client will do, we use Fork as it's simple and straightforward. Fork is a popular Git client that provides a user-friendly interface for managing Git repositories. It offers features such as branch management, commit history, and pull requests, making it an excellent choice for developers who prefer a graphical interface.

## Fetching using Fork

To fetch the latest changes from the remote repository, after selecting the repository in Fork, click on the "Fetch" button in the top-right corner of the screen.

This command fetches the latest changes from the remote repository and updates the local repository with the new changes. That does NOT mean that the files are already updated on the local machine. To update the files you need to:
- check if you still have uncommitted changes.
- pull the latest changes from the remote repository

## Stage local changes

To stage local changes, after selecting the repository in Fork, click on the "Stage" button in the top-right corner of the screen.

This command stages the local changes to the local repository. That does NOT mean that the changes are already committed to the local repository. To commit the changes to the local repository you need to:
- check if you still have unstaged changes.
- commit the changes to the local repository

## Commit local changes

To commit local changes, after selecting the repository in Fork, click on the "Commit" button in the top-right corner of the screen.

This command commits the local changes to the local repository. That does NOT mean that the changes are already pushed to the remote repository. To push the changes to the remote repository you need to:
- check if you still have uncommitted changes.
- push the changes to the remote repository
