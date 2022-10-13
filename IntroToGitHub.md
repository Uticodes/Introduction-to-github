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

But for the purpose of this article, I will be using **Command Line** to clone a repository.

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
4. Push your code to GitHub with the command `git push`

![commit](https://res.cloudinary.com/utibe/image/upload/v1665101444/Technical%20writing/Screenshot_2022-10-07_at_1.07.06_AM_cxnl15.png)   


## How to Create a Pull request

A pull request (or PR) is a way to alert repository (repo) owners or collaborators that you want to make some changes to their code. It allows them to review the code and make sure it looks good before putting your changes on the primary branch.

![branch terminal](https://res.cloudinary.com/utibe/image/upload/v1665238005/Technical%20writing/Screenshot_2022-10-08_at_2.59.57_PM_leyrif.png)
Once you create a new branch off the primary branch, make changes, commit and push your changes, then, you can make a pull request.

Here are the steps to make a pull request:

1. Open the GitHub repo of the project
2. Click on **Compare & Pull Request**

![Compare](https://res.cloudinary.com/utibe/image/upload/v1665239105/Technical%20writing/Screenshot_2022-10-08_at_3.08.25_PM_aux9ud.png)

1. Type a comment to best explain what your changes were all about in the **Leave a comment** section

![Create pull request](https://res.cloudinary.com/utibe/image/upload/v1665239105/Technical%20writing/Screenshot_2022-10-08_at_3.11.31_PM_m1mfx6.png)

1. When you’re done with the comment, Click on **Create pull request**

![Merge preview](https://res.cloudinary.com/utibe/image/upload/v1665239105/Technical%20writing/Screenshot_2022-10-08_at_3.20.06_PM_zwqw2w.png)

Congratulations 🥳🥳👏👏 you have created a pull request, now it is left for your team to review your changes and approve, then, merge the pull request.

## GitHub Desktop vs Github CLI

**[GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/overview/getting-started-with-github-desktop)** is an application that enables you to interact with GitHub using a GUI instead of the command line or a web browser. GitHub Desktop encourages you and your team to collaborate using best practices with Git and GitHub. You can use GitHub Desktop to complete most Git commands from your desktop with visual confirmation of changes. You can push to, pull from, and clone remote repositories with GitHub Desktop, and use collaborative tools such as attributing commits and creating pull requests.

**[GitHub CLI](https://docs.github.com/en/github-cli/github-cli/about-github-cli)** is a command-line tool that brings pull requests, issues, GitHub Actions, and other GitHub features to your terminal, so you can do all your work in one place. it is an open-source tool for using GitHub from your computer's command line. When you're working from the command line, you can use the GitHub CLI to save time and avoid switching contexts.

GitHub CLI includes GitHub features such as:

- View, create, clone, and fork repositories
- Create, close, edit, and view issues and pull requests
- Review, diff, and merge pull requests
- Run, view, and list workflows
- Create, list, view, and delete releases
- Create, edit, list, view, and delete gists
- List, create, delete, and connect to a codespace

## Conclusion

In this article, you have learned about GitHub, and why you need GitHub. I when ahead to explain the differences between GitHub and Git because when you’re new to GitHub, it’s easy to be confused between the two.  I also explained some features of GitHub like cloning a repo, making a commit, and making a pull request.

Finally, I explained the differences between GitHub Desktop and GitHub CLI. This might be your first time hearing about the two or not, but if it is your first time, you’ll get to use them someday.

I believe that this article will help a lot of people trying to understand some things about GitHub and will help them to explore more of what GitHub can do.