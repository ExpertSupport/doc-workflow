# Learn tool stack for Angular documentation

To work on the Angular documentation, you need a foundation in the tools. 

## Learn about GitHub and git

* Go to https://git-scm.com/ for an intro to git.
* Go to https://help.github.com/ for the GitHub docs.

## Set up your environment

* Install git, node, npm, yarn.

## Get familiar with the command line

* For an intro to terminal for the mac: http://blog.teamtreehouse.com/introduction-to-the-mac-os-x-command-line
* For Windows: _____


## Get familiar with markdown

* An interactive tutorial: https://www.markdowntutorial.com/
* Another interactive tutorial: http://commonmark.org/help/tutorial/
* A great reference: https://guides.github.com/features/mastering-markdown/


## Extras

### Node and `npm`
You don't need to know how node and `npm` work other than node is like the engine under the hood. It's powerful and needs lots of things, or packages, to make the app work (that Angular specifies). `npm` is the node package manager, meaning it goes out and gets the packages that node needs. When you run the command `npm install`, `npm` downloads those packages and stores them in a directory called `node_modules`.

The `node_modules` directory has lots of stuff in it, but you shouldn't generally have to think about it. Because of all that stuff, developers generally do not upload it to GitHub with their projects. 

### Telling git to ignore things
A file called `.gitignore` lists all the things you want git to ignore when tracking your files or when pushing up to GitHub. For an example of a `.gitignore`, see the one in this repo. It is a copy of the one from the Angular repo. Notice that it includes `node_modules` and `.DS_Store`. `.DS_Store` is a hidden Mac file that keeps track with your preferences when you browse to a folder in the Finder. The OS does not generate this file when you traverse directories within the command line. If this file does appear when you do a `git status`, you need to delete it before committing.

### More info
If you are inspired to learn more about node, you can do so at [their site](https://nodejs.org/en/).


