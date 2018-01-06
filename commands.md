##Globally configure the username for all repos

`git config --global user.name "kumawat55"`


##Globally configure the userEmail for all repos

`git config --global user.email "rhtkumawat55@gmail.com"`

##Initialize a git repo

`git init test`

-->Create any file here test.txt<--

`vim test.txt`

#Add file to staging Arena

`git add test.txt`

#Permanently save changes in file

`git commit -m "REPO COMMITTED"`

#Command will push the local branch to remote branch(https://github.com/kumawat55/test)

`git push origin master`

#Intializing origin with remote link

`git remote add origin https://github.com/kumawat55/test`

##The output of this command will display everything the git log command displays for the HEAD commit, 
plus all the file changes that were committed.

`git show HEAD`

##It will permanently cache the user credentials for a period of time

`git config --global credential.helper 'cache --timeout 7200'`

