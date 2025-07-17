# Git Commands

Initialize your folder to be a repository, first go in your repository directory.  
```git init```


After creating the repository, type this command to allow to use the commands to push and pull:  
```git remote add origin <git repository URL>```

Check if remote origin is connected for testing purposes.  
```git remote -v ```

Show commits and if they are pushed or not.  
```git status```

Show commits ready to be pushed.  
```git log```

# Making Commits
Making the stage for the files to be committed.  
```git add .```

Create a message for that specific version of our project. A common initial message is “Initial commit, **[filename]** created”  
```git commit -m "[your initial commit message]"```

Push the commit to your main in Github.  
```git push origin main```


