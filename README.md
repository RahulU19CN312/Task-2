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
