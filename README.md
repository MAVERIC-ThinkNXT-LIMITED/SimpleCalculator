# Assignment

Build a simple calculator application using HTML5, CSS3, Javascript and Bootstrap4.
You are not expected to know HTML, CSS, JS and Bootstrap4 inorder to complete this assignment.
Copy paste the code for respective branches from this template repo for completing this assignment.

### Goal of this assignment is to learn:
1.	Creating Github account and configuring SSH key for working with remote 
2.	Creating a new git repository from scratch
3.	Linking local repo with the remote repo
4.	Pushing local branches to the remote repo and making remote branch as the upstream branch 
5.	Working with multiple branches by creating separate feature branch for each of the application features like
   - header 
   - footer
   - add
   - subtract
   - multiple
   - divide
6.	Creating pull requests, doing code reviews and merging branches on remote github repo
7.	Synchronizing local repo with remote repo via git pull & git fetch and git merge commands
8.	Resolving merge conflicts and updating pull requests by pushing the local branch to remote tracking branch after conflict resolution
9.	Tagging the source code in master branch for release


## Pay attention to the following points:
1.	Repo name must be “SimpleCalculator”. It can’t be something else
2.	Branch names must be master, develop, feature/header, feature/footer, feature/add, feature/subtract, feature/multiply, feature/divide
3.	Commit messages must be same as what has been mentioned in the below steps
4.	Number of pull requests must match and the content in those pull request must match
5.	File contents in respective branches must match
6.	Number of commits in each branch must match

<b/>Note:</b> 
Make your repo public. Submitted assignments will be evaluated through a script and not adhering to the above mentioned guidelines will lead you to fail in the test. 
Your completed assignment should look exactly same as this repo except the README file. 

## Steps for completing the assignment:
1.	Create a new repository with name “SimpleCalculator” in your Github account. (Name of the repository must be “SimpleCalculator”)
2.	Create an directory on your local machine with name SimpleCalculator (you can’t use any other name for your repository)
3.	Add 3 empty files with names calculator.html, calculator.js and calculator.css into the SimpleCalculator directory
4.	Convert SimpleCalculator into a git repository 
5.	Stage all the newly added files and commit with message “Initial commit containing empty files for html, css and js” (Note: Use the exact message)
6.	Setup Github SimpleCalculator repository as the remote repository for the local SimpleCalculator repo
7.	Push local “master” branch to the remote repository by making remote “master” branch as the upstream branch
8.	Create a new branch with name “develop”
9.	Update calculator.html file with 3 input elements and commit with message “Added card layout with 3 input elements, 2 for operands and 1 for result”
Note: Get the contents from the second commit of the template repo
10.	Push the local develop branch to remote repo with remote “develop” branch as the upstream branch
11.	 Create 6 separate branches from the develop branch for header, footer, add, subtract, multiply and divide features. All feature branches must have “feature/” as prefix i.e, feature/header, feature/footer etc
12.	Switch to header branch to add the header related code 
13.	Stage all the changes and commit with message “Adding application header”
14.	Push the feature/header branch to remote repo by setting up the upstream branch
15.	Raise pull request with feature/header as source branch and develop as the target/destination branch
16.	Checkout to footer branch and add footer feature related code
17.	Stage all the changes and commit with message “Adding application footer”
18.	Push the feature/footer branch to remote repo by setting up the upstream branch
19.	Raise pull request with feature/footer as source branch and develop as the target/destination branch
20.	Checkout to add branch and add the addition related code
21.	Stage all the changes and commit with message “Adding addition feature to the app”
22.	Push the feature/add branch to remote repo by setting up the upstream branch
23.	Raise pull request with feature/add as source branch and develop as the target/destination branch
24.	Checkout to subtract branch and add the subtraction related code
25.	Stage all the changes and commit with message “Adding subtract feature to the app”
26.	Push the feature/subtract branch to remote repo by setting up the upstream branch
27.	Raise pull request with feature/subtract as source branch and develop as the target/destination branch
28.	Checkout to multiply branch and add the addition related code
29.	Stage all the changes and commit with message “Adding multiply feature to the app”
30.	Push the feature/multiply branch to remote repo by setting up the upstream branch
31.	Raise pull request with feature/multiply as source branch and develop as the target/destination branch
32.	Checkout to divide branch and add the addition related code
33.	Stage all the changes and commit with message “Adding divide feature to the app”
34.	Push the feature/divide branch to remote repo by setting up the upstream branch
35.	Raise pull request with feature/divide as source branch and develop as the target/destination branch
36.	Merge feature/header branch into develop branch after code review
37.	Resolve merge conflicts in feature/footer branch and push the code to the upstream feature/footer branch
38.	Merge remote feature/footer branch to remote develop branch 
39.	Resolve merge conflicts in feature/add branch and push the code to the upstream feature/add branch
40.	Merge remote feature/add branch to remote develop branch 
41.	Resolve merge conflicts in feature/subtract branch and push the code to the upstream feature/subtract branch
42.	Merge remote feature/subtract branch to remote develop branch 
43.	Resolve merge conflicts in feature/multiply branch and push the code to the upstream feature/footer branch
44.	Merge remote feature/multiply branch to remote develop branch 
45.	Resolve merge conflicts in feature/divide branch and push the code to the upstream feature/footer branch
46.	Merge remote feature/divide branch to remote develop branch 
47.	Raise a pull request with develop as source branch and master as destination branch
48.	Merge the pull request
49.	Update local develop and master branches
50.	Checkout to master branch
51.	Create an annotated tag with name “v1.0” and message “First version of SimpleCalulator app with add, subtract, multiply and divide features”
52.	Push the tag to the remote repo


## Steps for resolving merge conflict:
Suppose there is a merge conflict in the feature/footer branch then you need to follow below mentioned steps for resolving the merge conflict:

1. Checkout to develop branch using “git checkout develop”
2. Execute “git pull” to update your local develop branch (assuming develop branch is setup to track origin/develop)
3. Execute “git checkout feature/footer” to switch to footer branch
4. Execute “git merge develop”
5. Resolve merge conflicts locally
6. Execute “git add <file-name>” to stage all the resolved files
7. Execute git commit -m “Commit message” to commit the changes
8. Execute “git push” to push changes to the remote feature branch after conflict resolution
9. Merge the pull request in Github

