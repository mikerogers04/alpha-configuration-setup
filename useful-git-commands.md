# GitHub Notes

## Useful Git commands

- git clone file-name
- git status
- git add file-name
- git commit -m "meaningful message here"
- git push origin main

### Vocabulary
- repository (repo) - a named folder on GitHub
- git - version control software
- GitHub - online platform for git, GUI for sharing code and collaboration
- local - you personal computer
- commit - adding a tracking number and message to your version
- diff - the difference between states of your local and GitHub repository
- markdown (.md) - a text-based language used on GitHub for code documentation

#### Git Process Notes
- create a new repo on GitHub
- clone the repo to your local
- add a new file
- add code to the file
- use git status to see where you are at in the process
- add, commit, push code to GitHub

### Notes about Branching
- Branching protects your code from errors that can cause your app to be down in production
- Branching allows multiple people to work on code at the same time
- Branching is a best practice for all developers on all projects
- The main branch is the source of truth and should only ever have working code

### Branching Vocabulary 

- branch: an alternative timeline where a developer can code safely
- main: the branch that is the source of truth, only working code allowed
- checkout: command to navigate between branches
- checkout -b: creates a new branch that doesn't currently exist
- deleting a branch: has to be deleted on local as well as GitHub
### Branching Commands

- $ `git checkout -b branch-name` :creates a new branch that doesn't exist
- $ `git branch` : lists all of the current branches on your local
- $ `git branch -d branch-name` : deletes a branch, you cannot delete the branch you are currently on
- $ `get chouckout main` : navigates back to main branch








