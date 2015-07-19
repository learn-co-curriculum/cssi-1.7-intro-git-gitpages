---
tags: cssi, git workflow, github
level: 1
languages: git
---
#Intro to Git and GitHub Pages

#Prior Knowledge:
+ Intro to the web
+ GitHub account setup
+ Learn.co walkthrough
+ Intro to HTML
+ Intro to CSS
+ Intro to Command Line

#Student Objectives:
+ Understand the purpose of GitHub and learn how to fork and clone repositories.
+ Deploy to GitHub pages


#Motivation:
GitHub is like Facebook for developers. Developers created tools for source and version control - programs to help them manage the history of files and help share across teams. We'll also use a GitHub feature called Pages to publish our first site for the world to see!

#Forking and Cloning
We will practice forking a repository here https://github.com/octocat/Spoon-Knife
  1. Click “Fork” button to copy the GitHub repository

  <img src= "https://raw.githubusercontent.com/learn-co-curriculum/cssi-1.7-intro-git-gitpages/master/images/clone.png" width="300">
  2. At “Where should we fork this repository?” popup, select own account.
  3. GitHub then redirects to a page with your username/lab-name in URL. Your account now has a copy on GitHub but you can’t edit it on your computer in Atom just yet.
  4. In the right sidebar of the repository page on GitHub, click to copy the http URL for the repository.

  <img src= "https://raw.githubusercontent.com/learn-co-curriculum/cssi-1.7-intro-git-gitpages/master/images/fork.png">
  5. In terminal, in your Dev directory, enter "git clone" and paste the URL.Cloning a repository just means it is copied onto your computer from your GitHub account.
  6. Terminal will prompt you to enter your GitHub username and password.

#GitHub pages
Let's get a page online for the world to see!
GitHub, which is so cool for storing our files and the history of our commits, also has an awesome Pages feature, which lets us publish simple websites for free, all from the command line.

  1. Open Chrome and go to www.github.com
  2. At the top right click the “+” new repository
  3. Name your repository ““username.github.io”, make the repository public, and initialize with a README
  4. In the right sidebar of the repository page on GitHub, click to copy the http URL for the repository.
  5. Open your terminal
  6. cd into your dev folder
  7. git clone https://github.com/username/username.github.io.git
  8. cd into your my_profile_project
  9. mv your html and css page into your “username.github.io.git” repository
  10. cd into your “username.github.io.git” repository
  11. git add .
  12. git commit -m “first commit”
  13. git push 
  14. You will be prompted to enter your username and password
  15. Check out http://username.github.io/ for your webpage!



#Conclusion
Two words: Open Source. There are over eight million people who use GitHub to store their code. Having a free account on GitHub means that anyone in the community can fork or clone your repositories and make changes to or contribute to your codebase. It’s all about people building publicly accessible applications together.
