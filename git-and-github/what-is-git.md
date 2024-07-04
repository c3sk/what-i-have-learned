# What is Git?

## Description

Git is a distributed version control system that allows multiple people to work on a project simultaneously without overwriting each other's changes. It keeps track of changes made to files and allows users to revert to previous versions if needed.

## Key features of Git

Some of the main features of Git are:

### It is distributed

This means thet every developer working on the same project has a full local copy of the entire repository, including its history.

### It allows Branching and Merging

Git's branching model allows parallel development and experimentation without affecting the main codebase. All branches can be merged back to the main branch once they are ready to be deployed.

### It captures the state of the entire project

Everytime we record the state of a project (commit) Git stores a full snapshot of the new or modified files and a reference to unchanched files. Every commit is immutable (by using a unique SHA-1 hash) and contains metadata such as the author, date and a message describing the change.

### It allows remote integration

Git can be used in remote repositories hosted on platforms such as GitHub. This allows collaboration with other developers around the world and secures the code in the cloud. You can _push_ your local changes to a remote repository and _pull_ changes from it.

### It is Open Source

Git is open source, free to use, and has a large community of users and contributors. This community provides extensive documentation, tutorials, and support.

## Common commands on Git

- `git init`: Initialize a new Git repository.
- `git clone [url]`: Clone an existing repository from a remote server.
- `git status`: Show the status of changes as untracked, modified, or staged.
- `git add [file]`: Stage a file. We can stage all the files in a directory by using `git add .`
- `git commit -m "message"`: Commit staged changes with a message.
- `git push`: Push local commits to a remote repository.
- `git pull`: Fetch and merge changes from a remote repository.
- `git branch`: List, create, or delete branches.
- `git checkout [branch]`: Switch to a different branch.
- `git merge [branch]`: Merge another branch into the current branch.
