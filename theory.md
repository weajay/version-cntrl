  


Revision and practice Question

1.	What is Git: Git is a free and open-source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. Git is a distributed version control system that tracks versions of files. It is often used to control source code by programmers collaboratively developing software.
2.	What is GitHub: 
GitHub allows users to create, store, change, merge, and collaborate on files or code in a "repository". A repository is like a folder for files that groups together items that belong to the same project. This allows users to collaborate on a shared project without worrying that their changes will impact the work of their collaborators before they're ready to integrate them. 
GitHub also provides access control and several collaboration features, such as wikis and basic task management tools for every project. Developers can change, adapt, and improve software from its public repositories for free, but it charges for private repositories.
3.	What is the difference between git/github: The key difference between Git and GitHub is that Git is a free, open-source version control tool that developers install locally on their personal computers, while GitHub is a pay-for-use online service built to run Git in the cloud. Git is a piece of software. GitHub is an online SaaS service.
Git is a version control system that allows developers to track changes in their code. GitHub is a web-based hosting service for git repositories. In simple terms, you can use git without Github, but you cannot use GitHub without Git
4.	Explain the importance of git/github: While Git is a tool that’s used to manage multiple versions of source code edits that are then transferred to files in a Git repository, GitHub serves as a web-based location for uploading copies of a Git repository. Git/GitHub as far as their function, they complement rather than compete with each other in this space.
5.	Examples of Git best practices
Make incremental, small changes.
Keep commits atomic.
Develop using branches.
Write descriptive commit messages
Obtain feedback through code reviews 
Push work to remote repos before logging out for the day
Identify a branching strategy 

Explain/define the following Terminologies
1.	Working directory: Working Directory A working directory contains both tracked and untracked files. In contrast, the Git directory contains only tracked files. It's typically the folder that contains the . git folder. That is the working directory.
2.	Difference between local repo and remote repo: A local repository is hosted on a local machine for an individual user whereas a remote repository is hosted on a remote (this could be on the internet or an off-site server; it could even be the same machine in a different path) and is shared among multiple team members.
3.	Staging: Staged means that you have marked a modified file in its current version to go into your next commit snapshot
4.	Git init: The git init command creates a new Git repository. It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository.
5.	Diff between git clone and git pull: git clone is dependent on git init. git clone is used to create a copy of an existing repository. Internally, git clone first calls git init to create a new repository. It then copies the data from the existing repository and checks out a new set of working files. The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. (The git pull command is a combination of two other commands, git fetch followed by git merge. The git pull command first runs git fetch which downloads content from the specified remote repository. Then a git merge is executed to merge the remote content refs and heads into a new local merge commit).

What is the function of git config: The git config command is a convenience function that is used to set Git configuration values on a global or local project level.  
What is commit message: The commit message is (a descriptive text) used to explain the function of the commit. The message should be a short description of the changes being committed and should be wrapped in quotations when calling git commit.
Also, a commit serves a reminder (a short text) you left when you saved your work on Git. This message aims to identify your work.
Explain the advantages of distributed version control: 
Most popular version control system adopted across the world per www.geeksforgeeks.org
Allows you to work offline and gives flexibility. You have the entire history of the code in your own hard drive.
No need to communicate with remote server since everything is done locally (on your local machine).
Working on branches is easy since every developer has an entire history of the code, so developers can share their changes before merging all the ‘sets of changes to the remote server.
If main server goes down or it crashes, you can still get the backup or entire history of the code from your local repository or server where the full revision of the code is already saved.
Merge conflicts with other developer’s code are less because every developer work on their own piece of code.



Part 2
Using visual studio code as IDE and Git/Github
Create public repository/folder with the name version-control.
Create a file called theory.md within version-control folder and record all your answers from part1 onto the file.

NB: At the end of exercise commit all the work done and publish it in GitHub and send the link (URL) either on the whatsup, telegram or email for review.

devopsacademygrp@gmail.com 
NB :You can also create a separate file for this and publish your answers on Github

Good Luck



1.	Explain the Git workflow
git flow involves isolating your work into different types of Git branches. Git workflows encourage developers and devops teams to leverage Git effectively and consistently. Git offers a lot of flexibility in how users manage changes

2.	How do you clone a repository? 
git clone <repository url> [directory]
3.	How do you check the status of your Git repository?  
git status 
4.	How do you stage and commit changes?  git add and git commit
5.	How do you create a new branch?  git branch <branch name>
6.	Explain the concept of git branching strategy. Systematic way to manage branches in a repository. It helps streamline development workflows, making it easier to manage feature development, bug fixes, and releases. Strategies like these are essential as they help in keeping project repositories organized, error free and avoid the dreaded merge conflicts when multiple developers simultaneously push and pull code from the same repository.
7.	Encountering merge conflicts can impede the swift delivery of code, thereby obstructing the establishment and upkeep of an efficient DevOps workflow. DevOps aims to facilitate a rapid process for releasing incremental code changes. Therefore, implementing a structured branching strategy can alleviate this challenge, enabling developers to collaborate seamlessly and minimize conflicts. This approach fosters parallel workstreams within teams, promoting quicker releases and reduced likelihood of conflicts through a well-defined process for source control modifications.
8.	How do you switch to a different branch? git switch <branch name>
9.	How do you merge one branch into another? git merge <branch you want to merge into branch>
10.	What is a merge conflict and how do you resolve it? 
Merge conflict is when two branches are being merged  to have changes to the same parts of the same file and git cannot automatically reconcile the difference. You resolve git conflict by: 
a. attempting to merge branches first. 
b. identify conflict files. 
c. open conflict files. 
d. resolve the conflicts. 
e. mark conflict as resolved. 
f. git add filename.exit 
11.	Why is branching important in Git? 
Provides a systematic way to manage branches in a repository. It helps streamline development of workflows, making it easier to manage feature development, bug fixes, and releases. 

12.	What is a pull request (PR) and what is its purpose?
Pull requests, otherwise known as PRs, is used to initiate the process of integrating new code changes into the main project repository. Pull requests are sent through git systems, like GitHub, to notify the rest of your team that a branch or fork is ready to be reviewed.
13.	Explain the concept of 'forking' in GitHub.
A fork is a new repository that shares code and visibility settings with the original “upstream” repository. Forks are often used to iterate on ideas or changes before they are proposed back to the upstream repository, such as in open-source projects or when a user does not have write access to the upstream repository. 
14.	How do you find a specific commit in the history?
git log
