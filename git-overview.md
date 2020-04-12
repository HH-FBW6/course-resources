# GIT

## What & Why?

    + Tool for managing changes to our codebase
    + Becomes more relevant when working in teams

## Overview

There are 2 aspects to using GIT:

    1 - Local repository (local changes)
    2 - Remote repository (remove service, such as GitHub, GitLab, BitBucket, etc...)

## Starting with a repository

    - `git init` (creates a local empty repository)
    - `git clone` (downloads a repository from the internet)

## Versioning

    - Create a `master` branch
    + Creating / moving between branches
        - (1) `git checkout -b {name}` flag - clones and moves us into a new branch {name}
        - (2) `git checkout {name}` Allows us to move between branches

## Synchronising between branches

    - `git merge` - more direct, no confirmation (terminal)
    - `git push` - push local changes to a remote repository
    - `git pull` - get changes from a remote repository to our local
    
    - Via interface - create a pull request - polite way of copying code between branches

## Conflict resolution
