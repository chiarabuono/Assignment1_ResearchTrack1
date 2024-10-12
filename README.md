# Basic commands
## Make your changes

```powershell
git add <file1_name> <file2_name>
git commit -m "my_commit"
git push --set-upstream origin my-branch
```

1. Stage the changed files
2. Take a snapshot of the staging area (and consequently update your local repository)
3. Push changes to github

## Create a branch
```
git branch my-branch
git checkout my-branch
git checkout -b my-branch
git branch
```
1. Create new branch Switch to new branch 
2. Switch to new branch
3. Create and switch directly to the new branch 
4. Check the active branch to ensure you are on the new branch


## Merge changes into the Master branch

```powershell
git checkout main
git merge my-branch
git push
```

1. Switch to the Master branch
2. Merge the branch my-branch on the Master branch
3. Push changes to github

# Manage C files
```powershell
gedit file.c
gcc file.c -o file
chmod +x file.sh
./file.sh
```
1. Create a file
2. Compile it
3. Make it executable
4. Execute it