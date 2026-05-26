# Version Control Systems: Understanding Git and GitHub

## Introduction to Version Control

Version control is a system that helps developers track changes in files over time. It is important in software development because code changes often happen step by step. Without version control, it would be difficult to know who changed something, when it was changed, and why it was changed. Git is one of the most common version control tools because it allows developers to save work in commits, compare versions, and return to earlier versions when needed.

## How Version Control Tracks Changes

Git tracks changes by using commits. A commit is like a saved checkpoint of the project. Each commit stores the changed files, the author, the time, and a message explaining what was done. Git also gives each commit a unique ID, called a hash, so the exact version can be found later. This helps developers understand the history of the project and fix mistakes more safely.

## Three Collaboration Benefits with Examples

### 1. Working on Different Tasks

Git allows people to work on different branches. For example, one student can work on the home page while another student works on the about page. Their work can stay separate until it is ready to merge.

### 2. Reviewing Work Before Merging

GitHub pull requests allow team members or instructors to review code before it goes into the main branch. For example, if a student adds a new page, the instructor can check the pull request and suggest changes before approving it.

### 3. Recovering from Mistakes

Version control helps when something goes wrong. For example, if a file is accidentally changed or deleted, Git can show the previous version. The developer can use commands like `git log`, `git revert`, or `git reset` to recover work.

## Git's Backup and Recovery Mechanisms

Git stores project history inside the hidden `.git` folder. Because Git is distributed, every cloned copy of a repository contains the project history. This means the project is safer because it is not stored in only one place. If a local computer has a problem, the GitHub copy can still be used. Git also has recovery tools like `reflog`, `reset`, `revert`, and `fsck`.

## Difference Between Git and GitHub

| Aspect | Git | GitHub |
|---|---|---|
| Type | Version control software | Online hosting platform |
| Location | Runs on the local computer | Runs on the web |
| Internet Needed | Not needed for local commits | Needed for pushing, pull requests, and collaboration |
| Main Purpose | Tracks changes and manages versions | Stores repositories and supports collaboration |
| Examples of Features | commit, branch, merge, log | pull request, issues, reviewers, Actions |

## Conclusion

Git and GitHub are important tools for modern software development. Git helps track changes, create commits, use branches, and recover from mistakes. GitHub helps publish the project online and makes collaboration easier through pull requests and reviews. Together, they help developers work in a more organized and professional way.