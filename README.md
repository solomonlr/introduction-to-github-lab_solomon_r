# Introduction to Git and Github

## Introduction

Git is a distributed version control system. In layman's terms, this is a piece of software that helps you organize your projects whether you work alone or collaborate with others. It has become integral to the world of STEM as it helped replace the olden days of sending code back and forth through emails. It generates a history of every change you've made and keeps those changes so collaborators can see exactly what others have worked on and make contributions to others work.

The difference between Git and Github is that git is a separate software created back in 2005 by Linus Torvalds, the same person who created the Linux operating system. Github is a cloud computing implementation of Git created in 2008. This is the equivalent of Microsoft Word being created, then Google Drive coming along and allowing you to collaborate and access your documents from multiple devices with ease.

## Why you should learn about Github

If you plan on continuing in Computer Science, you'll run into Github in both your upper division classes and in your career. Even if you don't plan on continuing with CS, many STEM fields still need the use of code to process their data, and that code will often be shared and maintained using Github.

## Setup

First, go ahead and install the following software on your own device.
[Github Desktop](https://desktop.github.com/)
Use whatever code editor you prefer, but here is a link to a recommended one if you need it.
[Visual Studio Code (optional)](https://code.visualstudio.com/)

## Definitions

**What is a repository?** 
A repository is a project of files and folders that are tracked for changes. This tutorial is a repository itself.

**What is a branch**
A parallel working version of your repository. You can have multiple branches at a time and branches can be created and deleted at will. Each repository default branch is called `main`.

## Making a fork

You'll be working with a lab partner, so the next step only needs to be done by one person.

1. At the top right of the webpage, click the button labeled "Fork". This makes a copy of the entire repository and moves it to your account so you can make whatever changes you want and test them out.

2. In the next screen, change the name to `introduction-to-github-first-partner-first-name-last-initial-second-partner-first-name-last-initial`. For example, `introduction-to-github-john-a-kyle-d`.

3. Make the repository private and keep "Copy the main branch only" checked, then click create fork.

4. Wait about 30 seconds for Github to finish forking the repository, then refresh the page. You can continue the lab from this repository.

5. In this new repository, select the Settings tab near the top right, then click Collaborators on the left. Add your professor, ``, and your lab partner.

## Making a branch

Making a new branch allows you to make changes to the repository without affecting other aspects of the project. That means people can upload different changes to a project without conflicting with other's work.

Each lab partner will have to do this next section on their own

1. At the top left of the page, click the button that says main
**INSERT IMAGE HERE**

2. Enter the name for the branch following the following naming convention, `first-name-last-initial-branch`. For example, `john-a-branch`. Then click `Create branch:`.

## Commit a file

A commit is a group of edits you've made to files and folders. 

1. Open up Github Desktop. At the top right of the screen, click File -> Options. Login to your github account from this screen.

2. Go back to the repository in your web browser. Click the green button near the top of the repository that says Code. Click the button next to the link to copy the link.

3. In Github Desktop, click "Clone a repository from the internet". You should see the repository you forked in the previous step. Select that repository and click clone.

4. Use whatever text editor to open up the folder that's been downloaded. If you already have Visual Studio Code installed, you can click "Open in Visual Studio Code". 

5. Create a new file named `hello-world-first-name-last-initial.c` ie `hello-world-john-a.c` with the following code:
