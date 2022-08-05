# Assignment

Let's learn day to day git commands and concepts by building a simple calculator application using HTML5, CSS3, Javascript and Bootstrap4.
If you don't know HTML, CSS, JS and Bootstrap4 don't worry. This repo has all the code that is required to build the application. You just need to copy paste the code for respective branches from this template repo in order to complete this assignment.

## Goal of this assignment is to make you learn:
- [x] Creating Github account & configuring SSH key 
- [x] Creating new local git repository from sratch 
- [x] Linking local repo to the remote github repo 
- [x] Working with feature branches 
- [x] Setting upstream branches
- [x] Raising pull requests 
- [x] Using pull requests for doing code reviews 
- [x] Merging of branches on remote repo
- [x] Pulling latest changes from the remote repo
- [x] Resolving merge conflicts
- [x] Tagging source code for the release
- [x] Learn day to day git commands vit git command line interface
## Pay attention to the following points:
1.	Make sure name of your repo in Github is “SimpleCalculator”. Don't use some other name. Pay attention to the case sensitivity
2.	Make sure your repo has following branches ('feature/' suffix is mandatory for each of the feature branches):
   - master
   - develop
   - feature/header
   - feature/footer
   - feature/add
   - feature/subtract
   - feature/multiply
   - feature/divide
3.	Make sure commit messages matches with the respective message in the below mentioned steps
4.	Number of pull requests in your repo must match with this template repo. Also the pull request content must also match
5.	Content of latest commit in each of your feature, develop and master branch must match with the respective branches in this repo
6.	Number of commitsin each of your feature, develop and master branch must match with the respective branches in this repo

#### Note:
Make your repo public. Submitted assignments will be evaluated through a script and not adhering to the above mentioned guidelines will lead you to fail in the test. 

Your completed assignment should look exactly same as this repo except the README file. 
## Prerequisite for completing the assignment:
1. Candidates must have a account on [Github](https://github.com/join)
2. SSH key is configured on Github
   - [Github link to setup ssh](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)
   - [Medium article on setting up ssh](https://medium.com/devops-with-valentine/2021-how-to-set-up-your-ssh-key-for-github-on-windows-10-afe6e729a3c0)
3. [Gitbash CLI is installed](https://github.com/git-for-windows/git/releases/download/v2.37.0.windows.1/Git-2.37.0-64-bit.exe) has to be installed

## Steps for completing the assignment:

#### Note: Follow the exact sequence for the steps mentioned below
#### Create new remote repo on github for collaboration
   1. Create a new repository with name “SimpleCalculator” (name must be “SimpleCalculator”) in your Github account 
#### Create local git repo and make your first commit
   2. Create a new directory on your local machine with name SimpleCalculator (name must be “SimpleCalculator”)
   3. Add 3 empty files with names calculator.html, calculator.js and calculator.css into the SimpleCalculator directory
   4.	Convert SimpleCalculator folder into a git repository 
   5.	Stage all the newly added files and commit with message “Initial commit containing empty files for html, css and js” (Note: Use the exact message)
#### Linking local repo to the remote repo on github
   6.	Setup Github SimpleCalculator repository as the remote repository for the local SimpleCalculator repo
#### Push local branch to remote repo and set it as upstream branch 
   7.	Push local “master” branch to the remote repository by making remote “master” branch as the upstream branch
#### Create develop branch and add common code
8.	Create a new branch with name “develop”
9.	Update calculator.html file with a card layout containing 3 input elements.Commit the changes with message “Added card layout with 3 input elements, 2 for operands and 1 for result”
10.	Push the local develop branch to the remote repo and set the remote “develop” branch as the upstream branch
#### Create separate feature branches for header, footer, add, subtract, multiply, divide
11.	 Create 6 separate branches from the develop branch for header, footer, add, subtract, multiply and divide features. All feature branches must have “feature/” as prefix i.e, feature/header, feature/footer etc
#### Complete the header feature
12.	Switch to header branch to add the header related code. Copy code from this repo's header branch
13.	Stage all the changes and commit with message “Adding application header”
14.	Push the feature/header branch to the remote repo and set the remote feature/header branch as the upstream branch
15.	Raise pull request with feature/header as source branch and develop as the target/destination branch
#### Complete the footer feature
17.	Checkout to footer branch and add footer feature related code
18.	Stage all the changes and commit with message “Adding application footer”
19.	Push the feature/footer branch to the remote repo and set the remote feature/footer branch as the upstream branch
20.	Raise pull request with feature/footer as source branch and develop as the target/destination branch
#### Complete the add feature
21.	Checkout to add branch and add the addition related code
22.	Stage all the changes and commit with message “Adding addition feature to the app”
23.	Push the feature/add branch to the remote repo and set the remote feature/add branch as the upstream branch
24.	Raise pull request with feature/add as source branch and develop as the target/destination branch
#### Complete the subtract feature
25.	Checkout to subtract branch and add the subtraction related code
26.	Stage all the changes and commit with message “Adding subtract feature to the app”
27.	Push the feature/subtract branch to the remote repo and set the remote feature/subtract branch as the upstream branch
28.	Raise pull request with feature/subtract as source branch and develop as the target/destination branch
#### Complete the multiply feature
29.	Checkout to multiply branch and add the addition related code
30.	Stage all the changes and commit with message “Adding multiply feature to the app”
31.	Push the feature/multiply branch to the remote repo and set the remote feature/multiply branch as the upstream branch
32.	Raise pull request with feature/multiply as source branch and develop as the target/destination branch
#### Complete the divide feature
33.	Checkout to divide branch and add the addition related code
34.	Stage all the changes and commit with message “Adding divide feature to the app”
35.	Push the feature/divide branch to the remote repo and set the remote feature/divide branch as the upstream branch
36.	Raise pull request with feature/divide as source branch and develop as the target/destination branch
#### Merge header branch with develop
37.	Merge feature/header branch into develop branch after code review
#### Merge footer branch with develop
38.	Resolve merge conflicts in feature/footer branch and push the code to the upstream feature/footer branch
39.	Merge remote feature/footer branch to remote develop branch 
#### Merge add branch with develop
40.	Resolve merge conflicts in feature/add branch and push the code to the upstream feature/add branch
41.	Merge remote feature/add branch to remote develop branch 
#### Merge header subtract with develop
42.	Resolve merge conflicts in feature/subtract branch and push the code to the upstream feature/subtract branch
43.	Merge remote feature/subtract branch to remote develop branch 
#### Merge header branch with multiply
44.	Resolve merge conflicts in feature/multiply branch and push the code to the upstream feature/footer branch
45.	Merge remote feature/multiply branch to remote develop branch 
#### Merge header branch with divide
46.	Resolve merge conflicts in feature/divide branch and push the code to the upstream feature/footer branch
47.	Merge remote feature/divide branch to remote develop branch 
#### Merging develop branch to master branch 
48.	Raise a pull request with develop as source branch and master as destination branch
49.	Merge the pull request
50.	Update local develop and master branches
51.	Checkout to master branch
#### Tagging code on master branch for the release
52.	Create an annotated tag with name “v1.0” and message “First version of SimpleCalulator app with add, subtract, multiply and divide features”
#### Note: Tag has to be annotated tag not a lightweight tag
53.	Push the tag to the remote repo

## Branching Guidelines

![Maveric Git Branching Stratergy](./branching-guideline.png)

![Maveric Git Branching structure](./branching-explained.png)

## Steps for resolving merge conflict:
Suppose there is a merge conflict in one of the feature branch then you need to follow below mentioned steps for resolving the merge conflict:

1. Checkout to develop branch using (assuming develop branch is the target branch for the pull request)
2. Execute “git pull” to update your local develop branch (assuming develop branch is setup to track origin/develop)
3. Switch to the feature branch 
4. Merge develop branch changes to the feature branch via “git merge develop”
5. Resolve all the merge conflicts by opening the files having conflict in your favourtie editor
6. Stage all the resolved files via “git add <file-name>” 
7. Complete the merge by commiting the staged changes git commit -m “Commit message” 
8. Push the merged changes to the corresponding remote feature branch via “git push” (assuming upstream branch has been already setup for your local feature branch)
9. Merge the pull request in remote github repo

## Some of the most commonly used git commands with useful options:
   
### Command for initial setup:
- git config --global user.name <Your name>
- git config --global user.email <Your email>

### Command to get help on any particular git command:
- git help <command-name>
- git <command-name> --help
- man git-<command-name>


### Command to get a new repo or an already existing repo:
- git init - command to initialise a new git repo inside a non git folder
- git clone - create or download a already existing git repo by using url


### Command to make changes to the git repo:
- git add - move the changes from working directory to staging already
- git commit  - commit the changes in staging area to git repo
- git status - check the status of git repo for modified, deleted or added files
- git log - to see the commit history
- git diff - to see the contents of the changed files

### Commands to work with git branches:
- git branch <branch-name> - to create a new branch
- git branch -  to view the list of branches in local repo
- git branch -r - to see the list of remote branches
- git branch  -d <branch-name> - to delete a already merged branch
- git branch -D <branch-name> - to forcefully delete a unmerged branch
- git checkout -b <branch-name> - to create a new branch and checkout to the newly created branch
- git checkout --track -b <branch-name> origin/<branch-name> - to create a new branch tracking the remote origin branch and checkout into newly created branch

### Command for undoing changes:
- git reset HEAD * - unstage all the staged changes
- git restore --staged * - unstage all the staged changes
- git checkout -- <file> - to revert back any changes to the file 

### Command to synchronise local repo with remote repo
- git remote add origin <github-repo-url>
- git push - push your changes from local to remote repo
- git pull - update you local current branch with the latest changes in the reemote tracking branch
- git push origin --delete branch-name - to delete a remote branch
- git fetch - to update remote tracking branches and to get any new branches added in the remote repo

### Command to merge branches two branches:
- git merge <source-branch> - to merge changes from source branch to current branch
- git rebase <source-branch> - to rebase current branch changes on top of source branch commits(creates a new commit id for the feature branch commits)


### Command to tag code for releases:
- git tag -a <tagname> -m <msg> - to create a annotated tag pointing to current branch head
- git tag <tagname>  - creates lightweight tag with the given name
   
### Ignoring unwanted folders and files:
- .gitignore - file containing the  list of all files and folders that needs to be ignored by git

 
   
## References:
 - [One of the best free youtube git turtorial by Kunal Khushawa](https://www.youtube.com/watch?v=apGV9Kg7ics&t=2729s)
 - [Free 1 hr youtube video for Git beginner. Teaches key concepts and commands](https://www.youtube.com/watch?v=8JJ101D3knE)
 - [Free 1.45 minutes youtube video for beginners teaching key concepts and commands](https://www.youtube.com/watch?v=8JJ101D3knE)
 - [Edureka video on youtube covering most of the commands](https://www.youtube.com/watch?v=b5oQZdzA37I)
 - [Free 25 minutes youtube video for beginners teaching  Git & Gitbash](https://www.youtube.com/watch?v=iGutIN5t9Mo)
 - [Cheat sheet containing key concepts and everyday used git commands](https://training.github.com/downloads/github-git-cheat-sheet.pdf)
 - [Git book. Candidates are expected to go Chapters 1, 2, 3, 6](https://git-scm.com/book/en/v2)


 
