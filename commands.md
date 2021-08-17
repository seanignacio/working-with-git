# Config
- <code>git config --global core.editor "code --wait"</code>
> Make VS Code the default editor for the .gitconfig file.
 
- <code>git config --global -e</code>
> Open .gitconfig file.
> (My alias: git openconfig)

# Workflow
- <code>git clone URL</code> (or <code>SSH</code>)
> Clone a repo locally.

- <code>git checkout -b new-branch-name</code>
> Create and enter a new branch.

- <code>git pull origin branch-name</code>
> Pull/update files from branch.

- <code>git log --oneline</code>
> Retrive a simplified list of commit entries made to a repo.
> (My alias: git lo)

- <code>git status</code>
> Check the state of the directory and staging area.

- <code>git diff "file name.extension"</code>
> View changes to file.

- <code>git add "file name.extension"</code>
> Adds a file or change in the working directory to the staging area.

- <code>git commit -m "commit title"</code>
> Create snapshot of staged changes and label the commit.

- <code>git push origin branch-name</code>
> Push changes to branch.

# Checkout
- <code>git branch</code>
> Check which branch you are in.

- <code>git checkout commit-hash</code>
> Enter detached mode: Revert the repo to its directory state after a specific commit was made. Good for looking around – NOT working.

- <code>git checkout branch-name</code>
> Enter a specific branch.

- <code>git checkout -b new-branch-name</code>
> Create and enter a new branch.
