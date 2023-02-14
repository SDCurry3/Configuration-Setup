# Useful Git Commands

## Learning git n stuff

### Useful Commands

- git clone file-name.wevr
- git status
- git add file-name.wevr
- git commit -m "meaningful message here"
- git push origin main

### Vocabulary
- repository (repo) - a named folder on Github
- git - version control software
- Github - online platform for git, GUI for sharing code and collaboration
- local - your personal computer
- commit - adds a tracking number and message to your version
- diff - the difference between states of your local and Github repository

### Notes About Branching

- Branching protects your code from errors that caan cause your app to be down in production
- Branching allows multiple people to work on code at the same time
- Branching is a best practice for all developers on all projects
- The main branch is the source of truth and should only ever have working code

### Branching Commands
- $ `git checkout -b branch-name`
creates a new branch that doesn't yet exist
- $ `git branch` - lists all the current branches on your local
- $ `git branch -d branch-name`
deletes a branch when you are done
- $ `git checkout main` navigates back to the main branch
