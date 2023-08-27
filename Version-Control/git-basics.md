# Git Basics

[<- Back](../README.md)

Git is a distributed version control system commonly used in software
development for tracking changes in source code. This guide aims to cover the
fundamental concepts and commands in Git that every developer should know.

## Why Use Git?

- **Version Control**: Maintain a history of changes to your code.
- **Collaboration**: Multiple contributors can work simultaneously without overwriting each other's changes.
- **Branching**: Create branches to work on features, bugs, or experiments independently.

## Common Commands

```bash
# Initialize a New Repository
git init

# Generate a .gitignore file
npx gitignore <template-name>
#=> ./.gitignore

# Clone an Existing Repository
git clone [repository_url]
#=> ./<repository-name>

# Check the Status of Changes
git status

# Stage all changes
git add -A
# Or stage changes to a specific file
git add [file_name]

# Commit Changes
git commit -m "Your commit message here"
#=> <commit-hash>

# Switch Branches or Create a New One
git checkout -b [branch_name]
# or to switch:
git checkout [existing_branch_name]

# Push Changes to a Remote Repository
git push origin [branch_name]

# Pull Changes from a Remote Repository
git pull origin [branch_name]

# Merge Changes from Another Branch
git merge [source_branch]
```

## Key Concepts

### What is Git?

Git is a version control system that allows you to track changes to files over
time. It is a distributed version control system, which means that it allows
you to work with a local copy of a project and then push your changes to a
remote repository. Git is the most popular version control system in use today.

### What is GitHub?

GitHub is a web-based hosting service for Git repositories. It provides a
graphical interface for managing Git repositories and a platform for
collaboration. GitHub is the most popular Git hosting service in use today.

### What is a Repository?

A repository is a collection of files and folders that are tracked by Git. A
repository can be local or remote.

### What is a Commit?

A commit is a snapshot of a repository at a given point in time. It is a
collection of changes to files and folders that are tracked by Git. A commit
can be local or remote.

### What is a Branch?

A branch is a parallel version of a repository. It is a collection of commits
that are tracked by Git. A branch can be local or remote.

### What is a Pull Request?

A pull request is a request to merge changes from one branch into another. It
is a collection of commits that are tracked by Git. A pull request can be local
or remote.

### What is a Merge?

A merge is the process of combining changes from one branch into another. It is
a collection of commits that are tracked by Git. A merge can be local or
remote.

### What is a Fork?

A fork is a copy of a repository. It is a collection of commits that are
tracked by Git. A fork can be local or remote.

### What is a Clone?

A clone is a copy of a repository. It is a collection of commits that are
tracked by Git. A clone can be local or remote.

### What is a Remote?

A remote is a connection to a remote repository. It is a collection of commits
that are tracked by Git. A remote can be local or remote.

## Best Practices

- Write meaningful commit messages.
- Frequently pull changes from the remote repository to stay up-to-date.
- Use branching to separate different lines of work.
- Always check the status of your changes before committing.

## References

- https://www.atlassian.com/git
- https://www.w3schools.com/git/default.asp
- https://learn.microsoft.com/en-us/training/modules/intro-to-git
- https://docs.github.com/en/get-started/quickstart/git-and-github-learning-resources
