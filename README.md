# 2020-07-git-dan

# The basics

- 'git init' : create repository in your current folder
- 'git add <path>': put a path to the staging
- 'git commit': will open an editor to write a commit message
- 'git commit -m "<message>"': write the <message> to commit in one step 
- 'git status': everything you need to know about current status
- 'git log': will show the git log
- 'git log --online': will give the oneline version of git log
- 'git diff': diff the current state with the last known git state
- 'git diff --staged': diff files in the staging area
- 'HEAD': where you are currently looking (i.e., what the files on your are)

# Remotes

- `git remote add origin <URL>`: add a remote URL
example: git remote add origin https://github.com/HarderE/2020-07-git-dan.git
- `git push origin master`: local -> remote
- `git pull origin master`: remote -> local
