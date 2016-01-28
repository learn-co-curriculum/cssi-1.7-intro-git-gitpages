
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

#GitHub Pages for First-time Users
Let's get a page online for the world to see!
GitHub, which allows us to  store our files and the history of our commits, also has an awesome Pages feature, which lets us publish simple websites for free, all from the command line.



  1. Open Chrome and go to www.github.com
  2. At the top right click the “+” new repository
  3. Name your repository “username.github.io”, make the repository public
      * make sure to  replace username with your username
  4. In the right sidebar of the repository page on GitHub, click to copy the http URL for the repository.
  5. Open your terminal
  6. cd into your dev folder
  7. git clone **https://github.com/username/username.github.io.git** 
    * make sure to  replace username with your username
  8. cd into your my_profile_project
  9. mv your html and css page into your “username.github.io.git” repository
  10. cd into your “username.github.io.git” repository
  11. git add .
  12. git commit -m “first commit”
  13. git push 
  14. Check out http://username.github.io/my_profile.html for your webpage!
    * if your html file is named index.html, you do not need the full path.
  
# Github Pages for Additional Projects
The previous steps will only work if you don't already have a username.github.io already. If you DO have a page that is hosted in that repo, you can follow the directions below to publish a new project.

1. Make a new repo for your project by clicking the "+" sign on top of github.com
2. In the right sidebar of the repository page on GitHub, click to copy the http URL for the repository.
3. In your terminal, clone your new repo: `git clone my_new_repo url` where `my_new_repo_url` is the url you copied in Step 2
4. In your terminal, move into your newly cloned directory: `cd my_new_repo`
5. In that directory checkout a new branch called gh-pages:  `git checkout --orphan gh-pages`
6. Add your files into your repository
7. Add everything in your folder to git: `git add .`
7. Commit your changes: `git commit -m "added files"
8. Push the gh-pages branch to github: `git push origin gh-pages`


[Reference](https://help.github.com/articles/creating-project-pages-manually/) 


#Conclusion
Two words: Open Source. There are over eight million people who use GitHub to store their code. Having a free account on GitHub means that anyone in the community can fork or clone your repositories and make changes to or contribute to your codebase. It’s all about people building publicly accessible applications together.

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/cssi-1.7-intro-git-gitpages' title='Intro to Git and GitHub Pages'>Intro to Git and GitHub Pages</a> on Learn.co and start learning to code for free.</p>
