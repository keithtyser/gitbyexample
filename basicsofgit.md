Configuring git
`git config --global user.name "username"`

Initializing a repository
`git init`

Add files to staging area
`git add .`

Check status
`git status`

Remove a file
`git rm file1.txt`

Commit changes
`git commit -m "message"`

Opens vi to write a message
`git commit`

Add a remote repository
`git remote add origin https://github.com/username/repository.git`

Cloning a remote repository
`git clone https://github.com/username/repository.git`

Bring in changes from remote repository
`git pull`

Fetch changes from remote repository (doesn't merge)
`git fetch`

Use `git fetch` and `git merge` to merge changes from remote repository instead of `git pull`. It is best practice.

Create a new branch and switch to it
`git branch feature-1`
`git checkout feature-1`

# this is a comment