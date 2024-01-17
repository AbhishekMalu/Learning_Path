## <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSAAU0AmFU2Dl800ntVCg_LLdocDQgV8bQT8Jg0l3-8aQ&" alt="Git" width="65" height="25">  👈
#### _Git is a distributed version control system (VCS). It's a tool that helps developers track changes in their source code over time. Git allows multiple people to work on a project simultaneously and merge their changes efficiently._

<div><b><u>KeyFeatures</u> : </b></div> 

+ Version Control: Git tracks changes to files, allowing you to access previous versions and see the history of the code.
+ Branching: Git enables the creation of branches for parallel development, making it easy to work on new f eatures or bug fixes without affecting the main codebase.
+ Merging: Git facilitates the merging of changes from different branches back into the main branch.
+ Distributed: Each developer has a full copy of the project's history, which makes it robust and allows for offline work.

##### _Developers use Git for managing and tracking changes in their codebase. Git is primarily a command-line tool, but it also has graphical user interfaces available._

## <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub" width="45" height="40"> <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Logo.png" alt="GitHub" width="55" height="25">  👈
#### _GitHub is a web-based platform built on top of Git. It adds a social and collaborative aspect to version control. It's used for hosting and sharing Git repositories, collaborating with others, and managing projects._

<div><b><u>KeyFeatures</u> : </b></div> 

+ Remote Repository Hosting: GitHub provides a place to host Git repositories on the cloud, making it easy to share code with others.
+ Collaboration: Multiple developers can work on the same project simultaneously, making changes through pull requests and discussions.
+ Issue Tracking: GitHub has built-in issue tracking for managing and prioritizing tasks and bugs.
+ Web-Based Interface: GitHub offers a user-friendly web interface for interacting with Git repositories, in addition to Git's command-line tools.

##### _GitHub is a platform where developers collaborate on open-source and private projects, share code, manage issues, and contribute to various software projects. It's widely used for open-source contributions and collaborative development._

##    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSAAU0AmFU2Dl800ntVCg_LLdocDQgV8bQT8Jg0l3-8aQ&s" alt="Git" width="65" height="25"> V/S <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Logo.png" alt="GitHub" width="55" height="25"> <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRrx85c1BCMfU1d9p3JFYplq0s1920-73056g&usqp=CAU" alt="GitHub" width="40" height="35">



Git  | GitHub
------------- | -------------
It is a software.  | It is a service.
First released in 2005  | Company launched in 2008
Maintained by The Linux Foundation  | Purchased in 2018 by Microsoft
It is installed and maintained locally on the system.  | It is Exclusively cloud-based (hosted on the web).
It is a distributed version control system, a tool to manage the source code history.  | It is a cloud-based hosting service for git repositories to bring team together.
It create a local repository to track changes locally rather than store then on a centralized server.  | It is open-source which mean code is stored in a centralized server and is accessible to everybody.


### 👉 Basic Terminal Command

- `ls` : List down data of current working directory.
- `ls -a` : List down the hidden repo.
- `pwd` : Path of current working directory.
- `cd` : Change directory to given path.
- `clear` : To clear the terminal.
- `cd ..` : Go back one step.
- `cd /` : Go back to into the root directory.
- `cd ~` : Go back to home directory.
  
- `touch <filename.type>` : To create the file.
- `touch <filename.type> <filename2.type>` : To create the multiple file.
- `mkdir <folder_name>` : To create the folder.
- `mkdir <folder1> <folder2>` : To create the multiple folder.
- `rm <filename.type>` : To delete file.
- `rmdir <folder_name>` : To delete the directory.
- `rm -r <folder_name>` : To delete directory having data.
- `nano <filename.type>` : To create and edit file in nano editor.(ctrl+x)
- `vi <filename.type>` : To create and edit the file in vi editor.(esc + (shift+z+z))
- `cat <filename.type>` : Display file content.

### 👉 Git/GitHub commands

- `git --version` : To check the version of git.
- `git config --global user.name "<your_name>"` : Setup the Git username.
- `git config --global user.email "<your_email>"` : Setup the Git email Id.
- `git config user.name` : To get the Git username.
- `git config user.email` : To get the Git Email Id.
- `git init` : Initialize a new Git repository in the current directory.
- `git clone <repository_url>` : Clone a remote Git repository to your local machine.
- `git status` : To get the status of working directory and staging area.
- `git add .` : Add all changes in the working directory to the staging area.
- `git add <filename.type>` : Add a single file to the staging area.
- `git reset HEAD <file name>` : Unstage changes for a specific file in the Git staging area.
- `git checkout -- <file name>` : To discard changes in a specific file and revert it to the state it was in the last commit.
- `git restore --staged <file name>` : To unstage changes for a specific file in the Git staging area.
- `git restore <file name>` : To restore files in your working directory.
- `git commit -m"your commit message"` : Saving changes to git.
- `git commit --amend` : Modify the last commit in Git.
- `git log` : To display the commit history of a Git repository. 
- `git log -2` : To display the last two commit.
- `git log -p` : To display the commit history and each commit along with the corresponding diff.
- `git log --graph` : To display the commit history of a Git repository in a graphical format, showing the relationships between different branches and merges. 
- `git diff ` : To show all Changes in Working Directory.
- `git diff --staged` : To show all Changes in Staging Area.
- `git reset <commit id>` : To move the current branch and the HEAD pointer to a specified commit.
- `git stash clear` : To delete all saved stashes in Git.
- `git branch` : To show all local branches and show the current branch.
- `git branch -r` : To show all remote branches.
- `git branch -a` : To show all branches in a Git repository, including both local branches and remote branches.
- `git branch <branch_name>` : To create the branch.
- `git checkout <branch_name>` : Switch to a different branch.
- `git checkout -b <new_branch>` : To create and switch to a new branch.
- `git branch -m <old_branch_name> <new_branch_name>` : To rename a Branch.
- `git rebase <branch_name>` : To integrate changes or reapply commits from one branch into another while maintaining a linear commit history.
- `git merge <other_branch>` : To merge all change from one branch into the current branch
- `git branch -d <branch_name>` : To delete a local branch in Git.
- `git push origin -d <branch_name>` : To delete a branch in a remote repository.
- `git remote add <remote_name> <repository_url>` : To add a new remote repository to your Git configuration. This command establishes a connection between your local repository and the remote repository.
- `git remote -v` : To display the remote URL's.
- `git remote show origin` : To display information about the remote named "origin" and the specified remote repository.
  
- `git push <remote_name> <branch_name>` : Pushes the changes from your local branch to the specified branch on the remote repository.
- `git fetch <remote_name>` : Fetches all changes from the remote repository without automatically merging them into your working directory.
- `git pull <remote_name> <branch_name>` : Fetches all changes from the remote repository and automatically merges them into your working directory.
- `git pull --rebase` : This command combines the fetch and rebase operations into a single command, used to update the local branch with changes from the remote repository while incorporating any local commits.