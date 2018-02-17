##### Globally configure the username for all repos

`git config --global user.name "kumawat55"`


##### Globally configure the userEmail for all repos

`git config --global user.email "rhtkumawat55@gmail.com"`

##### Initialize a git repo

`git init test`

##### -->Create any file here test.txt<--

`vim test.txt`

##### Add file to staging Arena

`git add test.txt`

##### Remove file from staging Arena

`   git rm test.txt`


##### Permanently save changes in file

`   git commit -m "REPO COMMITTED"`

##### To Shows you the status of files in the index versus the working directory. 
It will list out files that are untracked (only in your working directory), modified (tracked but not yet updated in your index), and staged (added to your index and ready for committing).
          
    git status 
##### To Reset your index and working directory to the state of your last commit.
    git reset      

##### Command will push the local branch to remote branch(https://github.com/kumawat55/test)

`   git push origin master`

##### Intializing origin with remote link

`   git remote add origin https://github.com/kumawat55/test`

##### The output of this command will display everything the git log command displays for the HEAD commit, 
plus all the file changes that were committed.

`   git show HEAD`

##### It will permanently cache the user credentials for a period of time

`   git config --global credential.helper 'cache --timeout 7200'`

##### To Create a GIT repository copy from a remote source
    git clone <link>



git tag git pull
git archive git diff

    git merge git log
