## Git & GitHub Daily Practice Summary

Today I practiced core Git and GitHub workflows using the command line on CentOS.

### What I Did

* Initialized a new local Git repository using `git init`
* Renamed the default branch from `master` to `main`
* Created and tracked files using `git add`
* Made the first commit to establish repository history
* Connected the local repository to a remote GitHub repository
* Pushed code to GitHub using HTTPS authentication with a Personal Access Token
* Resolved the issue of pushing without an initial commit
* Created a new branch for updates and feature work
* Modified an existing file on the new branch
* Committed changes separately on the feature branch
* Pushed the new branch to GitHub
* Merged the feature branch back into the `main` branch
* Pushed the merged changes to GitHub
* Learned safe branching and merging practices used in real-world development

### Key Learnings

* Git branches allow isolated development without affecting the main codebase
* A branch must have at least one commit before it can be pushed
* GitHub no longer supports password authentication; Personal Access Tokens are required
* Merging is always done from the target branch
* This workflow mirrors professional Git usage in teams

### Result

* Local and remote repositories are fully synchronized
* Changes are successfully merged into the main branch
* Strong foundation built in Git and GitHub fundamentals
Git practice on CentOS Stream 10


# Git & GitHub Practice Summary (Today)

## Environment

-   OS: CentOS Stream 10
-   Tool: Git (command line)
-   Remote: GitHub (HTTPS)

## What I Did Today

### 1. Initialized a Git Repository

``` bash
git init
```

-   Created a new local Git repository.
-   Default branch was `master`.

### 2. Renamed Default Branch to `main`

``` bash
git branch -m main
```

-   Updated branch name to follow GitHub standards.

### 3. Added Files to Staging Area

``` bash
git add .
```

-   Selected two files to be tracked by Git.

### 4. Created First Commit

``` bash
git commit -m "Initial commit"
```

-   Saved project state in Git history.

### 5. Connected Local Repo to GitHub

``` bash
git remote add origin https://github.com/RahulU19CN312/Task-2.git
```

-   Linked local repository with GitHub remote.

### 6. Pushed Code to GitHub

``` bash
git push -u origin main
```

-   Uploaded local commits to GitHub repository.
-   Learned that GitHub requires a Personal Access Token instead of a
    password.

## Key Learnings

-   A branch cannot be pushed without at least one commit.
-   GitHub no longer supports password-based authentication.
-   `main` is the preferred default branch name.

## Result

✅ Two files successfully pushed to GitHub\
✅ Local and remote repositories are now synced
