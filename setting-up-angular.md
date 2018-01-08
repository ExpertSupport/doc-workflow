
# Angular.io local setup

Follow these steps when you are setting up the `ExpertSupport/angular` repo locally for the first time.

**In terminal:**

1. `git clone the-angular-repo-you-want-to-clone`
1. `cd angular`
1. `yarn`
1. `cd aio`
1. `yarn setup`
1. `yarn start`
1. Open a new terminal tab or window in the same directory.
1. `yarn docs-watch` in new tab.
1. Open a third tab or window so you can issue git commands as you work. 
1. `git init` (This initializes your local directory as a Git repo.)
1. `git checkout -b yourname-branch-topic` (The -b flag creates a new branch. Omit it for an existing branch.)
1. You can open Visual Studio Code from the aio directory by typing `code .`
1. If this command doesn’t work, go to the VSC docs to configure terminal to recognize it: https://code.visualstudio.com/docs/setup/mac

**In Chrome (best browser to work in):**

1. Go to localhost:4200

_Note: Always view your work in the browser to make sure nothing breaks from your edits. As you work, toggle over to Chrome frequently so that if the page does break, you know which edit might have caused the issue._
