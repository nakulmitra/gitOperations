# gitOperations

# Step 1: Create New Repositery
  Step 1.1: Click New 

![](GitImg/new.PNG)

  Step 1.2: Give Repositery a name and click Create

![](GitImg/repoName.PNG)

  Step 1.3: Copy the repositery link

  Code --> Copy repositery link

![](GitImg/copyLink.PNG)

# Step 2: If your git bash is not configure with your github

$ git config --global user.name "Abc Xyz"

$ git config --global user.email abcxyz@example.com

# Step 3: Go to the folder where you want to make your local repositery
$ cd folderPath

![](GitImg/goToFolder.PNG)

# Step 4: Clone repositery
$ git clone repositeryLink

Local Repositery will be created.

![](GitImg/cloneRepo.PNG)

# Step 5: Go to local repositery
$ cd localRepositeryName

![](GitImg/localRepoFolder.PNG)

# Step 6: Do changes on local repositery

![](GitImg/tempFile.PNG)

# Step 7: Add files to staging area
$ git add .

Above command is used to add all the files to staging area.

![](GitImg/gitAdd.PNG)

# Step 8: Check the status of add files
$ git status

![](GitImg/gitStatus.PNG)

# Step 9: Commit the changes
$ git commit -m "Message"

![](GitImg/gitCommit.PNG)

# Step 10: Push changes of local repositery to github repositery
$ git push origin branchName

Make sure pointer should points to that particular branch.

![](GitImg/gitPush.PNG)

# See the changes

![](GitImg/changes.PNG)

# Some other operations

![](GitImg/structure.PNG)

# Remove File
$ git rm fileName

![](GitImg/removeFile.PNG)

# See the Commit History of particular file
$ git log -- fileName  

![](GitImg/history.PNG)

# Recover the Deleted File
$ git checkout hashCode(first 5 characters) -- fileName

![](GitImg/recoverFile.PNG)

# Make New Branch
$ git branch branchName

![](GitImg/makeBranch.PNG)

# Change Branch
$ git checkout branchName 

![](GitImg/changeBranch.PNG)

# See All Branches
$ git branch

![](GitImg/allBranch.PNG)

# Delete Branch
$ git branch -d branchName  

![](GitImg/deleteBranch.PNG)

 