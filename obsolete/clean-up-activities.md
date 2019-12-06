
# Clean up and Remove Merged Branches

When you are finished with your changes, and your changes have been merged back into the main repo, you need to delete your branch in two places: locally and on GitHub.

## Delete a branch locally
When your work is merged into master, you can delete your local branch with the following command:

`git branch -D your-branch-name`

## Delete a branch on GitHub
You can delete your remote branch in several different ways. The easiest is to go to the GitHub page of the repo your branch is in, go to the branches tab, and then click on the red trash can for the branch you want to delete. 

![Screenshot of delete branch icon on github](img/delete-branch.png)

If you're interested in the command line methods, see [this Stack Overflow question](https://stackoverflow.com/questions/2003505/how-do-i-delete-a-git-branch-both-locally-and-remotely).
