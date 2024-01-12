# assignment-learnable
Git and Vision Control assignment on Learnable-23 Tobechukwu Onwuegbuzia (F)

## Explain Version Control
Version control, also known as revision control or source control, is a software development practice that involves keeping track of multiple different versions of software, content, documents, websites, and other information in development. Any system that provides change tracking and control over programming source code and documentation can be considered version control software.

## Explain the difference between git and github
1. Git is a command line tool while Github is a Graphical user interface
2. Git is installed locally in the system for use and does not require the internet while Github can be accessed on the web. it needs internet connection
3. Git Majorly focused on version control and code conserving while Github is majorly focused on Web hosying and code sharing.

## List 3 other github alternatives
1. GitLab
2. Gitea
3. Apache Allura

## Explain the difference between git fetch and Git pull
git fetch really only downloads new data from a remote repository - but it doesn't integrate any of this new data into your working files. Fetch is great for getting a fresh view on all the things that happened in a remote repository.
Due to it's "harmless" nature, you can rest assured: fetch will never manipulate, destroy, or screw up anything. This means you can never fetch often enough.
git pull, in contrast, is used with a different goal in mind: to update your current HEAD branch with the latest changes from the remote server. This means that pull not only downloads new data; it also directly integrates it into your current working copy files. This has a couple of consequences:
  - Since "git pull" tries to merge remote changes with your local ones, a so-called "merge conflict" can occur. Check out our in-depth tutorial on How to deal with merge conflicts for more information.
  - Like for many other actions, it's highly recommended to start a "git pull" only with a clean working copy. This means that you should not have any uncommitted local changes before you pull.

## Explain in simple terms git rebase and the command for it
Git rebase is a command used in Git version control to integrate changes from one branch into another.
The Rebase command syntax is 
git rebase <branch-name>;

## Explain in simple terms git cherry-pick and the command for it
Git cherry-pick is a command that allows you to apply the changes introduced by a specific commit to your current working tree. It’s useful when you want to isolate a specific fix or feature from a branch and apply it to another branch without merging the entire branch. "git cherry-pick"

