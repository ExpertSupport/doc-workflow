# Questions about the workflow and tool stack

This page contains questions about the workflow and environment. We might want to keep this file as a FAQ for people new to the Angular docs environment.

Q: How do I change my default terminal editor?
A: You can edit `.gitconfig` as follows:
`[user]
    email = name@host.com
    name = Your Name
[core]
    editor = nano
`

Q: Do I always need to branch my copy of the angular repo? Or can I usually work in my master? 
A: Don't ever work in master. Master should always reflect what's in the Angular/angular master branch. Always create a new branch in your repo and do your work there. 

Q: What should I do if I create a PR and then discover more changes that weren't committed when I created the PR? Or changes that I should make?
A: Make your changes in the relevant branch for that PR, add, commit, and push. The updates should show up in the PR automatically.

