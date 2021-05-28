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
$ git clone pasteRepositeryLink
Local Repositery will be created.

![](GitImg/cloneRepo.PNG)

# Step 5: Go to local repositery
$ cd localRepositeryName

![](GitImg/localRepoFolder.PNG)

# Step 6: Do changes on local repositery

![](GitImg/tempFile.PNG)

# Step 7: Add files to Staging state
$ git add .
Above command is used to add all the files to stage tree
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



 