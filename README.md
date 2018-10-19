# VGDC Git Workshop

## Basic `git` Concepts:

- `git clone <repository-url-here>` - clone a remote repository into a new folder in the current directory.
- `git status` - show current status of the repo.
- `git pull` - pull remote changes. This updates your local repository to match the remote repo.
- `git add .` - add everything in the working directory. Adding a file makes it **tracked**, allowing git to manage changes to that file. You can also add specific files or directories using `git add <file>` or `git add <directory>`.
- `git commit` - commit changes. This uses the vim text editor for writing a commit message. vim may be difficult to use for beginners so using the inline form `git commit -m "<message-here>"` may be preferrable.
	- Note: if get stuck in vim, press `Esc` then type :q! and press enter in order to exit.
- `git push` - push your commits to remote.
