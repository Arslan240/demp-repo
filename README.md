    #Demo

Description:
I am learning to use git and github that's why this demo-repo thingy is being made. So I hope it all goes well.

After deleting the previous line Now I am adding a new line

    ##Subheader

Adding subheader and new line of code potentially.

1- git status = this command will show us all the untracked or saved  files that we have created but not saved or commited, something like that.

2- git add . = this command will tell the git to track all the untracked files and save them. 
    '.' the period here is used for all the files. Alternatively we could write the name of the specific file that we want to commit.

3- git commit -m = This command will commit the saved changes to the github repository. 
    '-m' after this inside "" we write the title of the commit.
    '-m' if we want to add the description of that commit we then add another , -m "description of the commit". 

4- git push origin master = this is something I have no idea what it is.

    ##GIT BRANCHING
    
Git branching is a technique where we create a branch at a certain point of our repository progress. This is separate from the main branch and we merge them later  at a point where we want it to merge.
    This is used when we want to develope a feature in our app but we don't want to add it to our main branch/ production app unless it is completely bug free. So we develope it on the side and then merge it into our main branch.
    
5- git branch = this command will show you the total branches in the repository and there will be a '*' before the name of the branch in which you currently are.

    ##Creating a new branch

6- git checkout -b description/name = git checkout is actually the command that is used to switch between branches, but when we add -b it means create a new branch. and add name as feature/description.

    ##Changing branches

7- git checkout branchName = this command will switch between branches.

    ##Merging branches

8- git diff featureBreanchName = To merge a feature branch and main branch we use this command.
9- git merge featureBranchName = We can also use this command to merge but then we have to make a PR (I don't know what it means)