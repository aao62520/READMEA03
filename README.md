# A03-aao62
## Git Tutorial
### Step 1- Install Git onto your device 
Download link [here](https://git-scm.com).
### Step 2-Ensure proper installation of git 
make sure its installed in an easy to access file location 


### Step 3-New Directory
Make the correct directory for git, have it organzied too

### Step 4- Test for functionality


## GitHub Tutorial
### Step 1-Making your account 
Create a [github account](github.com)
### Step 2-Creating a repository
On the top left of the github website, click the dropdown menyu next to your profile. There should be an option that says "new repository"
![Repo Creation](https://www.w3schools.com/git/img_github_new_repo.png)
Fill in the info for your repository. This one is for a W3 Schools [tutorial](https://www.w3schools.com/git/git_remote_getstarted.asp?remote=github). We will be following that tutorial for the rest of this.
![Repo Info](https://www.w3schools.com/git/img_github_new_repo_create.png)
### Step 3-It's time to Push
Now the first time is going to be tough but we are going to **push** that repo we created in the GIT tutorial to your new GitHub account. Now breathe with me as we take our GitHub username and the GitHub repo name and combine into a URL like the one below.
> https://github.com/cc756/A03.git
Now we take this URL and breathe out as we head back to our command line.
```
git remote add origin https://github.com/cc756/A03.git
```
`git remote add origin URL` specifies that you are adding a **remote** repository, with the specified `URL`, as an `origin` to your local Git repo.
Okay it's time for that big push! I'll hold your hand if you need it as if this is your first time you will get a notification to authenticate.

**3**

**2**

**1**

**PUSH!**
```
git push --set-upstream origin master
Enumerating objects: 22, done.
Counting objects: 100% (22/22), done.
Delta compression using up to 16 threads
Compressing objects: 100% (22/22), done.
Writing objects: 100% (22/22), 92.96 KiB | 23.24 MiB/s, done.
Total 22 (delta 11), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (11/11), done.
To https://github.com/cc756/A03.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
```
### Step 5-Awwww, It's Connected
Go back to your repository on GitHub to see if the **merge** happened or if there was a **merge conflict**.
![Successful Push](https://www.w3schools.com/git/img_github_merged.png)




## Glossary
**Branch**: a new/separate version of the main repository. Allows to developers to edit the code without effecting the main branch, allowwing for mulititasking among the teams.

**Clone**: `git clone` creates a local copy of a project that already exists remotely. The clone includes all the project's files, history, and branches.

**Commit**: `git commit` saves the snapshot to the project history and completes the change-tracking process. In short, a commit functions like taking a photo. Anything that's been staged with `git add` will become a part of the snapshot with `git commit`.

**Fetch**: allows users to download files and changes from the remote to their local repository. Generally good practice to run `git fetch` before you start

**GIT**: a version control system tracks the history of changes as people and teams collaborate on projects together. Unlike once popular centralized version control systems, distributed version control systems don't need a constant connection to a central repository. Git is the most popular distributed version control system. Also used to start commands when using Git directly from the command line

**Github**: a website that hosts Git repositories and provides developers with tools to ship better code through command line features, issues (threaded discussions), pull requests, code review, or the use of a collection of free and for-purchase apps in the GitHub Marketplace.

**Merge**: `git merge` joins two or more branches together and incorporates the changes from the named commits into the current branch the user is working in.

**Merge Conflict**: when two branches have commits that conflict with each other and you attempt to merge them, Git needs to decide which commits to actually use in the final merge. This is usually done automaticaly but sometimes Git needs your help.

**Push**: `git push` updates the remote repository with any commits made locally to a branch.

**Pull**: `git pull` updates the local line of development with updates from its remote counterpart. Developers use this command if a teammate has made commits to a branch on a remote, and they would like to reflect those changes in their local environment.

**Remote**: a repository that is hosted on a server that is accessible to all team members. Code hosting services such as Github can serve as storage for remote repositories.

**Repository**: a collection of files that are compiled together into a project, along with the commit/file revision history of that project

## References
<details><summary>Click for references</summary> 
<p>
  
  - [Jet Brains](https://www.jetbrains.com/help/webstorm/getting-started-with-webstorm.html)
  - [GitHub Docs](https://docs.github.com/en)
  - [W3 Schools Git Tutorial](https://www.w3schools.com/git/)
  - Past classes
  
</p>
</details>
