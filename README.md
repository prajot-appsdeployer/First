# **Git and GitHub**

## 1. Get started
To use Git on the command line, you will need to download, install, and configure Git on your computer.
>By using the commands

```
git config user.name "your GitHub username"
git config user.email "your GitHub email"
```

## 2. Create Repo 
Create repo online on GitHub.

## 3. Initialize git
Initialize git by using ```git init```

## 4. Create Clone
Create a clone of the online repo to the local system.
> By using command the ```git clone "the repo url "```

## 5. Create a file locally
Creat a file locally in our case the file _first day.txt_ and input some text inside it.

## 6. Adding the files to the staging area
Add the files to the staging area by using ```git add .``` for stagin all the files in the local repo.

## 7. Commit the files
Finalize the changes to upload to the git repo by using ```git commit -m "message"```

## 8. Branching
> It is done by using the command ```git checkout -b <branch-name>```

## 9. Merging
> It is done by using the command ```git merge <branch-name>```

## 10. Push the code
Finally push the code or files to the remote repo by using
```
git remote add origin <REMOTE_URL>
git push <REMOTE-NAME> <BRANCH-NAME>
```

These are the basic funcitions that are used for version controll and pushing the builds.  
