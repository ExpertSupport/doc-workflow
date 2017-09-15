# Workflow for editing Angular docs

This doc captures Denny's understanding of the workflow. **KW and others, please edit to add missing info and correct mistakes.**

This assumes:
* You have a GitHub account.
* You have installed node, npm, and yarn. See [Installations](/installations.md)
* You have installed and configured Visual Studio Code (VSC). See [Installations](/installations.md)

## Section 1: Initial setup for a new story

For purposes of this doc, a story is a logical collection of documentation tasks that fit together. Usually, a story is completed by editing in a branch. That is, one story = one branch.

### Step 1.1: Fork the angular/angular repo

This creates a repo in your account. e.g. dennispbrown/angular by creating a copy of angular/angular. You have to fork someone else's repo you want to work on because you have read only permissions on it by default. The owner can give you 
more permissions, but working with the least possible is the safest route.

### Step 1.2: Clone the repo

This creates a copy of the repo, aka a clone, locally that you'll use for this story. 

### Step 1.3: Create a branch

This creates a local copy of a branch for you to work in. This isn't on GitHub until you push up later. 


## Section 2: Daily Setup

This section assumes that you'll work on a story (branch) over a few days. 

### Step 2.1: Rebase your branch(es)

This makes sure you have the most recent changes that are in master in your feature branches. You do this because you want your branches to be as close as possible to the master branch with the only differences being what you are working on. In order to merge your branch with the master branch, your branch will have to be up-to-date. If it isn't, the owner of the repo will ask you to rebase. If you've been rebasing all along, it should be an easy task. If you haven't, it will be more involved (read: rebase often!!).

### Step 2.2: Run yarn

This turns on the compiler that watches your local folder for changes, translates the markdown to html, and displays the result in your browser.

?? add how

In terminal:
1. yarn setup
1. yarn start
Leave this window open. Yarn is now running in the background. Don't ^C out of this command until you're done for the day. And you might even keep it running over multiple days.
1. Open a new tab or window in Terminal
1. yarn docs-watch
Again, leave this window open. The watcher is running in the background. 
1. Open yet another tab or window in Terminal (You will have 3 Terminal screens.)
Use this screen for git commands as you work.

## Section 3: Daily Work

This section assumes:
* You are working in a local branch of whatever repo is right.
* You have yarn running.

### Step 3.1 - Open VSC with files you want to work on

Quick version: In a Terminal window, cd to the directory you are working in, do `code .` This opens all of the files in that directory.

Longer version that you might be used to: Open VSC from the Finder, navigate to the right folder, and open the files you want. 

### Step 3.2 - Edit files

That is, do the real work that you have wanted to do all along.

You can create new files, edit files, save them as you work.

### Step 3.3 - Review your work

1. Open browser (Chrome works best for Angular stuff.)
1. Go to `localhost:4200`

### Step 3.4 - Repeat Steps 3.2 & 3.3 as many times as necessary.

This is just the normal stuff of "I wonder how this looks rendered."

### Step 3.5 - Push your work up to GitHub

When you're ready to quit for a while, push your changes up to GitHub.

1. (Optional) `git status`
This will show you what you've changed, and what state it's in. If it's red, git sees it, but you need to stage it before you can commit it. 
1. `git add --all`
This stages all of the files you changed to be ready for the commit.
1. (Optional) `git status`
This will show you the files in green that are now staged for the next commit.
1. `git commit -m "docs(aio): your-commit-message"
This commits all of your changes in the current local branch. 
1. `git push`
This pushes your changes to the corresponding branch at GitHub. If that branch doesn't exist up on GitHub yet, you need to do `git push --set-upstream origin name-of-your-branch`. The error message will contain the exact syntax for the command just as you should enter it. 

### Step 3.6 - Squashing



## Section 4 - Daily Shut down

I think this section might be empty. But you might want to do the following. **Check with KW about her conventions.**

1. Make sure you have done Step 3.4 - Push your work up to GitHub.
1. In Terminal, go to the tab containing `yarn docs-watch`. ^C to quit out of that background process. You will be back at a terminal prompt.
1. In Terminal, go to the tab containing `yarn start`. ^C to quit out of that background process. You will be back at a terminal prompt.
1. Quit out of VSC. 

## Section 5 - When you're done with the work on this story(branch)

1. Make sure you have done Step 3.4. 
1. Go to your repo on GitHub.
1. ?? **Add how to create a PR**
1. ?? **Add how to communicate regarding the PR. Conventions, etc.**
1. ?? **Add what to do if you have to make changes based on the reviews.**

## Section 6 - When your changes have been merged back into the main repo

?? **Add info about when and how to delete repos/branches, etc.**




