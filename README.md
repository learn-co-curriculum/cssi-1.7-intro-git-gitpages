---
tags: cssi, git workflow, github
level: 1
languages: git
---
#Intro to Git and Github Pages

#Prior Knowledge:
+ Intro to the web
+ Github account setup
+ Learn.co walkthrough
+ Intro to HTML
+ Intro to CSS
+ Intro to Command Line

#Student Objectives:
+ Understand the purpose of GitHub and learn how to fork and clone repositories.
+ Deploy to github pages


#Motivation:
Github is like Facebook for developers. Developers created tools for source and version control - programs to help them manage the history of files and help share across teams. We'll also use a Github feature called Pages to publish our first site for the world to see!

#Forking and Cloning
We will practice forking a repository here https://github.com/octocat/Spoon-Knife
1. Click “Fork” button to copy the GitHub repository
2. At “Where should we fork this repository?” popup, select own account.
3. GitHub then redirects to a page with your username/lab-name in URL. Your account now has a copy on GitHub but you can’t edit it on your computer in Atom just yet.
4. In the right sidebar of the repository page on Github, click to copy the http URL for the repository.
5. In terminal, in your Dev directory, enter "git clone" and paste the URL.Cloning a repository just means it is copied onto your computer from your github account.
6. Terminal will prompt you to enter your github username and password.

#Github pages
<<<<<<< HEAD
1. Open Chrome and go to www.github.com
2. At the top right click the “+” new repository
3. Name your repository “firstname_lastname”, make the repository public, and initialize with a README
4. Copy the repository URL
5. Open your terminal
6. cd into your dev folder
7. git clone https://github.com/username/firstname_lastname.git
8. cd into your my_profile_project
9. mv your html and css page into your “firstname_lastname” repository
10. cd into your “firstname_lastname” repository
11. `git checkout -b gh-pages`
12. `git push origin gh-pages` (You may need your username and password again)

#Conclusion
Two words: Open Source. There are over eight million people who use GitHub to store their code. Having a free account on GitHub means that anyone in the community can fork or clone your repositories and make changes to or contribute to your codebase. It’s all about people building publicly accessible applications together.
=======
Let's get a page online for the world to see!
Github, which is so cool for storing our files and the history of our commits, also has an awesome Pages feature, which lets us publish simple websites for free, all from the command line.

Here's an example github page with instruction to create your own!
<a href= "http://google-cssi.github.io/sample-pages/">Example github page</a>

+ Initialize a repository
+ Set your remote to a repository on github
+ Add some changes, commit them, and push them up to the remote master branch
+ Checkout a branch named gh-pages (`git checkout gh-pages`)
+ Push to a remote branch named gh-pages(`git push origin gh-pages`)
+ Go check out your site!(`http://username.github.io/profileproject/profile.html`)

You have already finished steps 1-3. Just three more steps to publish a site to the world!
Follow the directions above to create a github pages for your profile page project!

#Git Fork and Git Clone for Labs

Each day you will have labs for each lesson. To work on the lab your will fork the lab to copy it onto your github account. Then you will clone it onto your local machine (your computer).

We want our own version each lab called. To make our own version, we'll fork the original - that will give us a copy to modify.

Fork the repository
To fork the github repository, click the Fork button.
<img src= "images/fork.png">

Sit back and watch the forking magic. When it’s finished, you’ll be taken to your copy of the  repository in your github account.

Clone your fork
You’ve successfully forked the repository, but so far, the files only exist on GitHub. To be able to work on the project, you will need to get the files onto your computer. Here's how to clone it to a directory on your local machine.

<img src= "images/clone.png" "height= "300" width= "250">

In the right sidebar of the repository page on Github, click to copy the URL for the repository. The url should be something like: ```https://github.com/YOUR-USERNAME/LAB-REPOSITORY.git```

In Terminal, navigate to the directory where you want the files. (Use cd!)
git clone, and paste the URL you copied, and hit enter.
```git clone https://github.com/YOUR-USERNAME/LAB-REPOSITORY.git```
>>>>>>> fb9e3855102d0361d9cb531d795d8edc2d37c028
