# learnable-wk2-task

## Git & Github Basic Version Control

### Assignment Q&A
---

__1. Explain version control__
> __Version control__ is a process for tracking and managing changes to files over time. The basic idea is to create a repository for your files, and then use version control to track any changes made to the files in the repository. This allows you to go back and view previous versions of the files, and even restore previous versions if need be. So, multiple contributors to collaborate on a project are able to keep history of modifications, and providing the ability to revert to previous states if needed. Example of a widely used version control system is Git.

__2. Explain the difference between Git and Github__
> In simple terms, __Git__ is the version control system, while __Github__ is a website and service that uses Git. As explained above, Git manages and tracks changes to your source code during development. It operates locally on your computer and allows you to create branches, commit changes and merge them. Github on the other hand, is a web-based platform that provides hosting for Git repositories. It offers features like pull requests, issue tracking and a graphical interface for managing repositories.

__3. List three other Github alternatives__
+ __[GitLab](https://about.gitlab.com)__
+ __[Bitbucket](https://bitbucket.org)__
+ __[SourceForge](https://sourceforge.net)__

__4. Explain the difference between git fetch and git pull__
+ __git fetch:__ it is a command that retrieves new changes from the remote repository without merging them into your local branch. So this is suitable when you want to see what changes have been made to the remote repository without affecting your local branch. 

+ __git pull:__ it does the same thing as git fetch but it merges the changes into your local branch. This is suitbale when you want to update your local branch with latest changes. Do note that conflicts may occur if changes have been made both locally and remotely.

__5. Explain in simple terms git rebase and the command for it__
> __git rebase__ is a command used to change the base of your current branch. It integrates changes from one branch into another. Any commits that were made after the point where you rebase will be lost.  `git rebase <remote branch name>`

__6. Explain in simple terms git cherry-pick and the command for it__
> __git cherry-pick__ is a command that allows you to "pick" specific commits from a branch and apply them to another branch. It is similar to rebase but it doesn't affect the entire history of the branch. `git cherry-pick <commit-hash>`