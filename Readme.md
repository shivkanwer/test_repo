# Git Commands

https://www.edureka.co/blog/git-commands-with-example/

```bash
# Following commands set the author name and email address respectively to be used with your commits.
git config –global user.name "[name]"
git config –global user.email "[email address]"
```

```bash
git init # Initialize a git repository
```

```bash
git add [file] # Add changes to the staging area for the next commit
git add * [git add .] # Stage all the changes
git add -p index.html # -p stands for patch level - This allows us to partially select the changes from a file that we want to stage
```

```bash
git status # See all the tracked and untracked changes
```

```bash
git commit -m "This is a new commit" # Commit staged changes to local repo
```

```bash
git reset # Un-stage the changes/
get reset [file]
```

```bash
git branch # list all the branches
git branch [branch name] # Create a new branch
git checkout [branch name] # Switch from one branch to another
git checkout -b [branch name] # Create a new branch and also switch to it
```

```bash
git merge [source branch name] # Merge another branch with the current branch
```

```bash
git remote add [variable name] [Remote Server Link] # Connect your local repository to the remote server
git push [variable name] master # Push changes in the local branch to remote repository, name the branch as master in the remote repo.

git push -u origin master # -u is used for saving the settings so that next time you can just run git push
```
