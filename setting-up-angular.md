
# Angular.io local setup

Follow these steps when you are setting up the repo locally for the first time.

**In terminal:**

1. `git clone the-angular-repo-you-want-to-clone` 
1. `cd angular`
1. `npm install`
1. `cd aio`
1. `yarn setup`
1. `yarn start`
1. Open a new terminal tab or window in the same directory.
1. `yarn docs-watch` in new tab.
1. Open a third tab or window so you can issue git commands as you work. 
1. `git checkout -b yourname-branch-topic` (The -b flag creates a new branch. Omit it for an existing branch.)
1. You can open Visual Studio Code from the aio directory by typing `code .`
1. If this command doesn’t work, go to the VSC docs to configure terminal to recognize it: https://code.visualstudio.com/docs/setup/mac

**In Chrome (best browser to work in):**

1. Go to localhost:4200

**In your editor**

1. Open your editor.
1. Go to aio/content/guide to get to the guides.

After working, go back to the third tab/window you’d opened in terminal and add, commit, and push. Here are helpful git commands:

1. `git add --all`
1. `git commit -m “docs(aio): the-edits-you-are-adding”`
1. `git push` (You’ll get an error the first time you try this if you don’t have a branch on GitHub that mirrors this one you’re working on. Just use the command that the error suggests.)


_Note_: Always view your work in the browser to make sure nothing breaks from your edits. As you work, toggle over to Chrome frequently so that if the page does break, you know which edit might have caused the issue.
