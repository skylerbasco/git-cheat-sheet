# Git Cheat Sheet
My go-to cheat sheet for Git commands! Photo created by REBELLABS by ZEROTURNAROUND.

## 📸 Photo:

![unknown](https://user-images.githubusercontent.com/58148243/172987445-00ecdebf-bea7-4fb4-a0a5-2fb49029015f.jpeg)

## 💭 Text:

### Create a Repository

From scratch -- Create a new local repository
<br>
```$ git init [project name]```

Download from an existing repository
<br>
```$ git clone my_url```

### Observe your Repository
List new or modified files not yet committed
<br>
```$ git status```

Show the changes to files not yet staged
<br>
```$ git diff```

Show the changes to staged files
<br>
```$ git diff --cached```

Show all staged and unstaged file changes
<br>
```$ git diff HEAD```

Show the changes between two commit ids
<br>
```$ git diff commit1 commit2```

List the change dates and authors for a file
<br>
```$ git blame [file]```

Show the file changes for a commit id and/or file
<br>
```git show [commit]: [file]```

Show full change history
<br>
```$ git log```

Show change history for file/directory including diffs
<br>
```$ git log -p [file/directory]```
