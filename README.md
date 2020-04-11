# My Github Guide

### For a new repository (with existing files)

```
git init
git remote add origin git@github.com:suishidan/reponame
git status // to check what is changed
git add .
git commit -m “intitial set up”
git push origin master
```

### After you make a change:

```
git status
git add .
git commit -m “this is my change”
git push origin master
```
Create a new repository on GitHub. You can also add a gitignore file, a readme and a licence if you want
 Open Git Bash
Change the current working directory to your local project.
Initialize the local directory as a Git repository.



git init


Add the files in your new local repository. This stages them for the first commit.


git add .


 Commit the files that you’ve staged in your local repository.
 
 
 
git commit -m "initial commit"



 Copy the https url of your newly created repo
In the Command prompt, add the URL for the remote repository where your local repository will be pushed.



git remote add origin remote repository URL



git remote -v


 Push the changes in your local repository to GitHub.



git push -f origin master



That’s all
