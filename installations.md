# Set up your working environment

## Required installations and configurations

### Create an account at GitHub
* Go to https://github.com/. 
* If you have an account, log in. If you don't have an account, create one and log in.

### Install Visual Studio Code 
* Go to https://code.visualstudio.com/. 
* Download and install VSCode. 
* Put it in your Dock (mac) or ??(windows)

### Configure the PATH variable so you can invoke VSCode from the terminal
* (mac) Go to https://code.visualstudio.com/docs/setup/mac
* (windows) Go to ??

### Install node and npm

Node.js is a Javascript interpreter. It enables you to run JS programs locally on your workstation. 

npm is the Node Package Manager. It enables easy installation of pre-packaged programs. In particular, it is used to install a local copy of Angular.

* Go to [the npm installation page](https://www.npmjs.com/get-npm?utm_source=house&utm_medium=homepage&utm_campaign=free%20orgs&utm_term=Install%20npm)
* Follow the directions on that page

### (Mac only) Install HomeBrew

[Homebrew](https://brew.sh/) is a package manager for MacOS. It enables simple installation of other software. 

1. In Terminal, `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

### Install Yarn

[Yarn](https://yarnpkg.com/en/) is the app that enables automatic translation of your Markdown files to HTML for display. With Yarn watching your files, you can edit in Markdown and immediately see the result in your browser. The [Yarn installation page](https://yarnpkg.com/lang/en/docs/install/) contains more info, including the instructions for installation on other operating systems.

1. (Mac) In Terminal, `brew install yarn`

This assumes you installed HomeBrew.

1. (Windows) ??


### Configure your Finder/Explorer to show hidden files

You probably will want to customize various settings in your environment. Many such settings are in hidden files. By default, the Mac does not show hidden files.

1. (Mac) In terminal, `defaults write com.apple.finder AppleShowAllFiles YES`

1. (Windows)

### Configure a terminal editor, and your email address

You will need a terminal editor for "squashing" a bunch of commits into one. ?? And maybe for other reasons. ??

vim is the default editor. If you know the vim commands, you can leave it as is.

KW recommends nano. It includes the basic editing commands on the screen. She finds it easier than vim.

emacs is also an option. We haven't explored that option yet.

1. (Mac) Edit the file, **Get file name from KW** ??

`[user]
    email = kapunahelewong@gmail.com
    name = Kapunahele Wong
[core]
    editor = nano
`




## Optional installations and configurations

