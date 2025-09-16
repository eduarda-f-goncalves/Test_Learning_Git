# Learning how to use Github :)

Some info...

Git CRASH COURSE:

TERMS:
- directory : folder
- CLI : Command line interface
- cd : change directory
- Repository : project, or the folder/place where your project is kept
- GitHub : A website to host your repositories online

GIT COMMANDS:
- clone : bring a repository that is hosted somewhere like GitHub into a folder on your local machine
- add : track your files and changes in Git
- commit : save your files in Git
- push : upload Git commits to a remote repo (short for repository), like GitHub
- pull : download changes from remote repo to your local machine, the opposite of push

Note: when crating a new file, if we use the termination : README.md, the .md is for formatting the fila as a mark down file, where we can write whatever we want.
In this case a README file is just a file where it is explained how the code works and what it does.

Using VSCode:
1) Open Vscode and choose a folder to open and where to store locally all the codes etc.
2) To open a repository from GitHub, for example this one, use the followig prompt: git clone git@github.com:eduarda-f-goncalves/Test_Learning_Git.git   (clone)
3) Atfer doing changes, or adding new files or anything at all, we have to save it locally, using the prompt:  git add .  This saves all the changes locally. The dot means it saves everything on the folder, or we can swap it by the name of the file we want to save.
4) After this we have to commit: git commit -m
5) And lastly to save not onky locally, but also on GitHub, we use the following command: git push   and it will sync both.
