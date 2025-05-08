# <h1>Learning ApnaCollege Git &amp; GitHub Course: </h1>

<p>This repository contains the code and exercises completed during my Git and GitHub learning journey with Apna College.</p>
<p>Author : <b>Maqsood Ahmad</b></p>
<br>
<h2>🔍 Key Features of This Course:</h2>

- **Course Overview**: Provides a brief summary of the topics covered in the Apna College Git and GitHub tutorial.
- **Repository Contents**: Lists the files included in the repository, giving visitors an idea of what to expect.
- **Getting Started**: Offers clear instructions on how to clone the repository and view the content locally.
- **Tools Used**: Mentions the tools and technologies utilized in the project.
- **Course Link**: Directs users to the full tutorial for further learning.
- **License**: Specifies the licensing terms for the repository.
<br>
<hr><br>

# Git Commands

## Initial Setup

- `git config --global user.name "Your Name"`
  Set your Git username.

- `git config --global user.email "you@example.com"`
  Set your Git email.

## Starting a Project

- `git init`
  Initialize a new Git repository.

- `git clone <repo-url>`
  Clone a remote repo to your system.

## Checking Status

- `git status`
  Show the status of changes.

## Staging & Committing

- `git add <file>`
  Stage a specific file.

- `git add .`
  Stage all changes (tracked & untracked).

- `git commit -m "Your message"`
  Commit staged changes with a message.

## Removing Files from Staging

- `git restore --staged <file>`
  Unstage a file.

## Viewing Changes

- `git diff`
  Show unstaged changes.

- `git diff --staged`
  Show staged changes.

## Working with Remote Repositories

- `git remote -v`
  Show remote URLs.

- `git push origin <branch>`
  Push local changes to remote repo.

- `git pull origin <branch>`
  Pull changes from remote repo.

## Branching

- `git branch`
  List all branches.

- `git branch <name>`
  Create a new branch.

- `git checkout <branch>`
  Switch to a branch.

- `git checkout -b <name>`
  Create and switch to a new branch.

- `git merge <branch>`
  Merge another branch into the current one.

## Log & History

- `git log`
  View commit history.

- `git log --oneline`
  Condensed commit history.

## Undoing Changes

- `git restore <file>`
  Discard changes in working directory.

- `git reset --hard HEAD`
  Reset all changes to the last commit.

## Advanced/Optional

- `git commit -am "msg"`
  Add & commit in one step (for tracked files only).

- `git reset HEAD~1`
  Undo the last commit.
