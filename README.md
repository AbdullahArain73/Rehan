# Rehans Instructions

## Installing Programs

```powershell
winget search git
winget install --id Git.Git
winget install --id GitHub.Cli
```

## Opening VS Code

```powershell
code .
```

## Git

```powershell
# Start a git repository
git init
# Clone an existing repository
git clone https://github.com/AbdullahArain73/Rehan.git

# What is happening?
git status

# Add a file to git staged changes
git add README.md
# Add all files to git staged changes
git add .

# Remove a file from git staged changes
git reset README.md

# Commit staged changes
git commit -m "Comment"

# See past commits
git log --oneline
```