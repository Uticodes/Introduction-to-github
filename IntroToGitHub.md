# Introduction to GitHub

# Introduction
![Github page](https://res.cloudinary.com/utibe/image/upload/v1665096519/Technical%20writing/Screenshot_2022-10-06_at_4.13.08_PM_prnfdw.png)
GitHub helps developers to build some of the most advanced technologies in the world. You could want to visualize data or build a new app, there’s a whole community and set of tools on GitHub that can help you do it even better.

This article will guide you through the basic things you need to know about GitHub like how to: 

- Clone a repository
- Make a Pull Request
- Make a Commit

## **Prerequisites**

- A [GitHub account](https://github.com/)
- [Download and Install Git](https://git-scm.com/downloads)

## What is GitHub?

GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

GitHub helps every team member work together on a project from any location while facilitating collaboration. You can also review previous versions created at an earlier point in time.

GitHub is said to be the world’s largest coding community.

## Why GitHub?

GitHub provides the important DevOps features companies and organizations of all sizes need for their public and private projects.

It is also fairly easy to screw up your local Git repository, especially when you’re new at this, also, it is also very easy for your PC to get damaged or get stolen, or your hard disk can crash.

Hence, it is a good idea to push your work to a remote location for peace of mind and GitHub is one of the best remote hosting services to store your code. 

## Git vs GitHub

By now you might be wondering about the difference between **Git** and **GitHub** or maybe this will be your first time hearing about the differences between the two. Anyways, welcome to the show 😁

**Git** is a distributed version control system (DVCS) that allows multiple developers or other contributors to work on a project. It makes it possible to work with one or more local branches and push them to a remote repository. Git is responsible for everything GitHub-related that happens locally on your computer. Key features provided by Git include:

- It's installed and used on your local machine
- Handles version control
- Supports branching

**GitHub** is a cloud platform that uses Git as its core technology. It simplifies the project collaboration process and provides a website, command-line tools, and overall flow that allows developers and users to work together. GitHub acts as the "**remote repository**".

Key features provided by GitHub include:

- Issues
- Discussions
- Pull requests
- Notifications
- Labels
- Actions
- Forks
- Projects

## How to Clone a repository

Cloning a repository will make a copy of the repository and its history on your local machine. To clone a repository, you can use the `git clone [repo url]` command or the GitHub CLI's `gh repo clone [url]` command.

They are several ways to clone a repository from GitHub, some of which are:

Through

- [GitHub Desktop](https://desktop.github.com/)
- [Command line](https://tutorial.djangogirls.org/en/intro_to_command_line/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Android Studio](https://developer.android.com/studio)
- Etc.

But for the purpose of this article, we will be using **Command Line** to clone a repository.

To get started cloning a repository: 

- Open GitHub and go to the GitHub repository that you want to clone

![Clone-steps](https://res.cloudinary.com/utibe/image/upload/v1665096518/Technical%20writing/Screenshot_2022-10-06_at_4.16.52_PM_shwnlc.png)

- Click “**Code**”**(arrow 1)** and on the pop-up screen, copy the repository URL by clicking on the two overlayed icons **(arrow 2)**.

![terminal](https://res.cloudinary.com/utibe/image/upload/v1665097347/Technical%20writing/Screenshot_2022-10-06_at_4.47.39_PM_cpgkpu.png)

- Open “**Terminal or CMD**” on your PC and change the current working directory to the location where you want the cloned directory.
- Type ***git clone*** in the terminal, paste the **URL** you copied earlier, and press “**enter or return**” on your PC keyboard to create your local clone.
- Wait for the process to complete

Now you have a copy of the remote repository on your local machine

## How to make a Commit

Before you can make a commit, it means that you already have existing source code or repositories stored locally on your computer or private network, you can add them to GitHub by typing some commands in a terminal. You can do this by typing Git commands directly, or by using [GitHub CLI](https://docs.github.com/en/github-cli/github-cli/about-github-cli).

Using the **Command line** to make a commit, follow the steps below: 

1. In the command line, navigate to the root directory of your project
2. Initialize the local directory as a Git repository with the command `git init -b main` if this is your first commit, if it is not your first commit, skip to the next step
3. Stage and commit all the files in your project with the command `git add . && git commit -m "[your commit message]"`

## How to Create a Pull request

