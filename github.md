---
layout: default
title: Using GitHub
permalink: /github/
---

## Working on the GitHub website

See video tutorial for details.

## Working on your own computer

If you prefer to work locally on your computer and have the necessary administrative privileges to install new programs, you can use use [**GitHubDesktop**](https://desktop.github.com/) to synchronize your local work with your GitHub account (or if you're already an expert at command-line use, you can interact with GitHub from there). You can edit the markdown files with any plain text editor but if you don't have a favorite yet, the text editor [**Atom**](https://atom.io/) is great for working with any text based document. Installation and use of GitHubDesktop and Atom are described below.

### Setting up GitHub Desktop

 1. Download and install GitHubDesktop for your operating system
    - [Instructions for Mac](https://help.github.com/desktop-beta/guides/getting-started-with-github-desktop/installing-github-desktop/#platform-mac)
    - [Instructions for Windows](https://help.github.com/desktop-beta/guides/getting-started-with-github-desktop/installing-github-desktop/#platform-windows)
 1. Start GitHubDesktop and sign into your GitHub account
    - [Instructions for Mac](https://help.github.com/desktop-beta/guides/getting-started-with-github-desktop/authenticating-to-github/#platform-mac)
    - [Instructions for Windows](https://help.github.com/desktop-beta/guides/getting-started-with-github-desktop/authenticating-to-github/#platform-windows))
 1. Clone (i.e. copy) a repository from GitHub to GitHubDesktop ([Instructions](https://help.github.com/desktop-beta/guides/contributing-to-projects/cloning-a-repository-from-github-to-github-desktop/))

### Working with GitHub Desktop

1. To clone additional repositories, go to the menu `File -> Clone Repository` and select the `GitHub.com` tab to see all the repositories you have access to. Select the one you want to copy and choose where you want it copied to on your computer. Use the `Current Repository` button at the top of the GitHub Desktop window to quickly jump back and forth between your different repositories.

2. To switch between different branches in a repository, use the `Current Branch` button that is right new to the Current Repository at the top of the GitHub Desktop window. Make sure you are in the right branch before you start making edits or simply create a new branch (menu `Branch -> New Branch...`).

3. Now you can make changes to any of the repository files (markdown files, images, etc.) on your own computer (using whichever programs you like to use for text and image editing) and make commits of one or multiple files back in the GitHub Desktop application (changed/remove/new files will show up in the main GitHub Desktop window and you can select them to add them to a commit). **Important note**: committing changes in GitHub Desktop does **NOT** automatically synchronize them back to the online version of your repository on GitHub.

4. To synchronize with GitHub, you need to use the button in the upper right corner of GitHub Desktop that says `Fetch origin` (i.e. check if something has changed in the repository on GitHub), `Pull origin` (i.e. copy all changes from GitHub that a teammate might have made there) or `Push origin` (i.e. upload your _committed_ changes to GitHub so your teammates can see them there and download them as well).

#### Setting up Atom Text Editor

 1. Download and install Atom for your operating system
    - [Instructions for Mac](https://flight-manual.atom.io/getting-started/sections/installing-atom/#platform-mac)
    - [Instructions for Windows](https://flight-manual.atom.io/getting-started/sections/installing-atom/#platform-windows)
    - [Instructions for Linux](https://flight-manual.atom.io/getting-started/sections/installing-atom/#platform-linux)
 1. Start Atom and add the cloned assignment folder as a new project with `File > Add Project Folder`
 1. Install a few useful extensions for working with markdown files and images ([Instructions for installing extensions](http://flight-manual.atom.io/using-atom/sections/atom-packages/)):
     - `markdown-writer`
     - `tool-bar`
     - `tool-bar-markdown-writer`
     - `markdown-preview-plus`
     - `atom-image-resize`
 1. Restart Atom to make sure all extensions are loaded properly
 1. Edit the assignment files and use `Packages -> Markdown Preview Plus -> Toggle Preview` (in the menu) to launch an automatic  preview of the rendered markdown file (Note that this will not be able to render special commands that use the `{% %}` notation, e.g. some of those used for images in the blog will not show up the way they do online).
 1. There are many more useful extensions for atom - feel free to explore them and see which ones you like. Easiest way to figure out what they do is by googleing them. If you install one you don't like, it is easy to disable or uninstall it again in the preferences (same place where you installed them to begin with). Some extensions worth considering are `wordcount`, `linter-markdown`, `pandoc-convert`, `project-manager`
