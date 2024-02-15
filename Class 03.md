# Code-102-Class-3

*[Code Fellow Lewis Main Page](https://lewable3d.github.io/Reading-Notes/)*
       
*[Lewis H. Ables III github profile](https://github.com/Lewable3d)*

*[Markdown Guide](https://www.markdownguide.org/getting-started/)*        

*[Basic Syntax](https://www.markdownguide.org/basic-syntax/)*

*[Cheat Sheet](https://github.com/ohmyzsh/ohmyzsh/wiki/Cheatsheet)*

# git 

- git is a version control system
- git lets multiple developers work on the same code
- git keeps a history of changes to your files
- git gives the ability to view, apply, and remove those files
- keep all of your project files in one repository
- each repository is a project

### Sharing Code and Collaboration: dvcs *"distributed visual control system"* for the masses

## Snapshots in time

*git takes snapshots of your project over time*

- Commits represent each successive version of a file or files.
- Commits are the equivalent of *"Save As"*
- Each successive version creates a new snapshot on the timeline of the project.
- Git keeps track of what the file looked like at different points in time.

## Keeping Track

- Each commit (snapshot) has a label that points to it
- HEAD = The label meaning "You Are Here"
- You can also assign messages to commits
- Messages are like writing a caption for your snapshot.

## Git Summary

- Git takes snapshots of your code at points in time
- Git keeps a history of what those snapshots look like
- Git has a special label called *Head*, that means *"You Are Hare"*
- Usually you will want to give your snapshot a label called a message to give detail of your changes.

## GitHub: *Your Code, in the Cloud*

*GitHub and Git not the same.* 

- GitHub is not Git
- Its a way to share your code with others.
- GitHub is an online place to store your code. (Backup is Important)
- Github uses Git to help manage your team's work:
  - Version Tracking
  - reviewing changes
  - keep changes separate until you want to add them in 

### Git is the sport and GitHub is one place, where you play the sport. 
*You can use Git in other places.*
- With Git (Version Control) and GitHub (online Code Storage), you can:
  - teamwork without messing each other up.
  - keep history of each file
  - work on code on your own computer and sync it with whats online.

## Repositories aka *Repos*

- it is a collection of files that Git is paying attention to.
  - Usually, one project = one repository
  - Large projects may have multiple repositories for different parts of their system (Repo for front end code vs Repo for back end code)
  - *Repos* (Repositories) can live on GitHub and/or your computer.

## Cloning: Copying repo to terminal

copying Repos from your GitHub to your computer: connecting information between GitHub and your computer.

- command in terminal: *git clone* then paste link
- command in terminal: *git remote -v*  git (main) link

 ## Terminal File Navigation for cloning linking github VS code and your terminal

1. ls where I am username
2. cd
3. pojects
4. code-102
5. Infinite80

## gitflow: acp add, commit, push 

1. make changes 
2. git status
3. git add README.md or git add * (ALL FILES)
4. git commit -m to changes
5. git push origin main
6. git staus

- Adding committing to changes and sending them back to github.
- command in terminal: *git status* tells you what files have changed since your last commit.
- command in terminal: *code* . open current folder in VS Code Editor
- command in terminal: *git add* <file> to update what will be committed
- command in terminal: *git restore* <file> to discard changes in working directory.
- command in terminal: *git add*" and/or "*git commit -a*"
- command in terminal: *git restore --staged <file>*... to unstage
- command in terminal: *git commit -m "message here"*  takes the snapshot -m (argument) means include message
- command in terminal: *git push origin main* sends any new commits (snapshots of your code) to Github.
- Command in terminal: *git pull* pull changes from github before you can push changes from terminal.
- Command in terminal: *git config pull* 
- command in terminal: *git add* . : commit changes made to multiple files at once
- command in terminal: *git add* * : commit changes made to multiple files at once

## Terminal File Navigation

1. ls where I am username
2. cd
3. pojects
4. code-102
5. Infinite80

- **[Code Fellow Lewis Main Page](https://lewable3d.github.io/Reading-Notes/)**

## NOTES

- **[Code-102-Class-1](https://lewable3d.github.io/Reading-Notes/Class%2001)**

- **[Code-102-Class-2](https://lewable3d.github.io/Reading-Notes/Class%2002)**

- **[Code-102-Class-3](https://lewable3d.github.io/Reading-Notes/Class%2003)**


