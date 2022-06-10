# Git Cheat Sheet
My go-to cheat sheet for Git commands! Photo created by REBELLABS by ZEROTURNAROUND.

## 📸 Photo Version

![unknown](https://user-images.githubusercontent.com/58148243/172987445-00ecdebf-bea7-4fb4-a0a5-2fb49029015f.jpeg)

## 💭 Text Version

### 🛠 Create a Repository

From scratch -- Create a new local repository
<br>
```git init [project name]```

Download from an existing repository
<br>
```git clone my_url```

### 🔎 Observe your Repository
List new or modified files not yet committed
<br>
```git status```

Show the changes to files not yet staged
<br>
```git diff```

Show the changes to staged files
<br>
```git diff --cached```

Show all staged and unstaged file changes
<br>
```git diff HEAD```

Show the changes between two commit ids
<br>
```git diff commit1 commit2```

List the change dates and authors for a file
<br>
```git blame [file]```

Show the file changes for a commit id and/or file
<br>
```git show [commit]: [file]```

Show full change history
<br>
```git log```

Show change history for file/directory including diffs
<br>
```git log -p [file/directory]```

### 🌴 Working with Branches
List all local branches
<br>
```git branch```

List all oranches, local and remote
<br>
```git branch```

Switch to a branch, my _branch, and update working directory
<br>
```git checkout my_branch```

Create a new branch called new branch
<br>
```git branch new_branch```

Delete the branch called my_branch
<br>
```git branch -d my_branch```

Merge branch _a into branch_b
<br>
```git checkout branch_b```
```git merge branch_a```

Tag the current commit
<br>
```git tag my_tag```

### 👛 Make a change
Stages the file, ready for commit
<br>
```git add [file]```

Stage all changed files, ready for commit
<br>
```git add .```

Commit all staged files to versioned history
<br>
```git commit -m "commit message"```

Commit all your tracked files to versioned history
<br>
```git commit -am "commit message```

Unstages file, keeping the file changes
<br>
```git reset [file]```

Revert everything to the last commit
<br>
```git reset --hard```

Overwrite commit history with your own local history (force push):
```git push --force```

### 🚰 Synchronize
Get the latest changes from origin (no merge)
<br>
```git fetch```

Fetch the latest changes from origin and merge
<br>
```git pull```

Fetch the latest changes from origin and rebase
<br>
```git pull --rebase```

Push local changes to the origin
<br>
```git push```

### 🎬 Finally!
When in doubt, use git help
<br>
```git command --help```

Or visit https://training.github.com/ for official GitHub training.
