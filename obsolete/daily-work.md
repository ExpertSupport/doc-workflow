{@ dailywork}

## Daily Work

This document lists the daily tasks that you need to perform while contributing to Angular docs.

The document assumes that:
* You are working in a local branch.
* You have `yarn` running.

### Step 1 - Open VSC with files you want to work on

Quick version: In a Terminal window, `cd` to the directory you are working in, enter the command `code .` 
This opens all of the files in that directory.

Longer version: Open VSC from the Finder, navigate to the right folder, and open the files/folders you want. 

### Step 2 - Edit files

You can create new files, edit files, delete files, etc. Save them as you work.

### Step 3 - Review your work

1. Open browser (Chrome works best.)
1. Go to `localhost:4200`.

### Step 4 - Repeat Steps 3 & 4 as many times as necessary.

### <a id='push'>Step 5 - Push your work up to GitHub </a>

When you're ready to quit for a while, push your changes up to GitHub. 

1. (Optional but recommended) Check the status of your changes using `git status`.
    
    This will give you a summary of files you've changed, and what state they are in. 

1. Stage your changes using `git add --all`.
    
    This will add the files you have changed to your local repository and stages it for commit.

1. Commit your changes to the local repository using `git commit -m "docs(aio): your-commit-message"`.
    
    This commits all of your changes in the current local branch. 
    
1. Push your changes to GitHub using `git push`.
    
    This pushes your changes to the corresponding branch on GitHub. If that branch doesn't exist on GitHub yet, you need to do `git push --set-upstream origin name-of-your-branch`. The error message will contain the exact syntax for the command just as you should enter it. 
