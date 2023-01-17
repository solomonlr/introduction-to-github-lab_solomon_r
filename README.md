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

<details>
<summary><h2> Making a fork </h2></summary>

You'll be working with a lab partner, so the next step only needs to be done by one person.

1. At the top right of the repository webpage, click the button labeled **Fork**. This makes a copy of the entire repository and moves it to your account so you can make whatever changes you want.

2. In the next screen, change the name to `introduction-to-github-first-partner-first-name-last-initial-second-partner-first-name-last-initial`. For example, `introduction-to-github-john-a-kyle-d`.

3. Make the repository private and keep **Copy the main branch only** checked, then click **Create fork**.

4. Wait about 30 seconds for Github to finish forking the repository, then refresh the page. You can continue the lab from this repository.

5. In this new repository, select the Settings tab near the top right, then click Collaborators on the left. Add your professor, ``, and your lab partner.

</details>

<details>
<summary><h2> Making a branch </h2></summary>

Making a new branch allows you to make changes to the repository without affecting other aspects of the project. That means people can upload different changes to a project without conflicting with other's work.

Each lab partner will have to do this next section on their own

1. At the top left of the page, click the button that says main
**INSERT IMAGE HERE**

2. Enter the name for the branch following the following naming convention, `first-name-last-initial-branch`. For example, `john-a-branch`. Then click `Create branch:`.

</details>

<details>
<summary><h2> Commit a file </h2></summary>

A commit is a group of edits you've made to files and folders. 

1. Open up Github Desktop. At the top right of the screen, click File -> Options. Login to your Github account from this screen.

2. Go back to the repository in your web browser. Click the green button near the top of the repository that says Code. Click the button next to the link to copy the link.

3. In Github Desktop, click **Clone a repository from the internet**. You should see the repository you forked in the previous step. Select that repository and click clone.

4. At the top, open the drop down menu titled **main branch** and select the branch you created earlier in this lab. 

5. Use whatever text editor to open up the folder that's been downloaded. If you already have Visual Studio Code installed, you can click **Open in Visual Studio Code**.

6. Create a new file named `hello-world-first-name-last-initial.c` ie `hello-world-john-a.c` with the following code:
```
#include <stdio.h>
int main() {
   printf("Hello, World!");
   return 0;
}
```

7. In Github desktop, you'll see your new file pop up on the left with the lines you added in the middle. At the bottom right, fill in the top text box to say **Added hello world**. Click the green button labeled **Commit** in the bottom left.

8. At the top of the screen, click **Fetch Origin**, then after a second, **Push Origin**. After that you can view the repository in your web browser and you should see your new file inside the branch you created. 

**Push and Pull**
    Imagine you are pushing your 'block' of code to the repository. That is the same as you uploading your changes. The same concept works the other way. When someone has made changes to the repository that you have not yet seen, you download, or **pull** those changes.
</details>

<details>
<summary><h2> Open a pull request </h2></summary>

Pull requests, or PRs, are used to combine branches either from the same repository or a different one. Instead of heading straight to making a commit, a pull request can be used to propose a change. Someone else can then look over your proposal before approving it and adding your change to the target branch.

In this lab, both you and your partner will make a pull request, merging their own branch to the main branch. 

1. After you've made your commit, you'll notice a message notifying that you can compare and pull request. You can either click that message, or access the pull request tab at the top of the repository page. If you choose the message, you can skip to step 5.

2. From the Pull requests tab, click **New pull request**. Make sure the main branch is selected from the **base:** dropdown menu.

3. In the **compare:** dropdown, select the branch you made previously.

4. Click **Create pull request**.

5. Provide a title and description. You can include info about the new branch and file that you created.

6. Click **Create pull request**.

**Background to a pull request**
    The conceptual understanding of a pull request is that you propose a change and request that someone else pulls your changes into the repository. This is often used when working on projects you do not have direct permissions to edit. You can contribute to other people's projects using a pull request.
</details>


<details>
<summary><h2> Merge your partner's pull request </h2></summary>

Now that both of you have created a pull request, you can both see each other's branch and pull request

</details>