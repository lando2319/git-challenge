# GIT CHALLENGE

The Git Challenge is a challenge originally presented to the Developers of ChangEd Apps.

Here is the Challenge:
- Go through this tutorial [Git From The Inside Out](https://codewords.recurse.com/issues/two/git-from-the-inside-out)
- Recreate each command. As the author says, "The user creates alpha", you should enter the command as shown. Avoid coping and pasting.
- Explore the contents of the .git file

This repo is the end result of completing the challenge. Unfortunately there isn't a clean way to include all the repos created, therefore I'm just including the alpha directory. I'm open to other ideas on best to show the files and maintain the setup.


Here are some helpful commands I learned

show git log with nice graph
`git log --graph`

show git objects, which blob object is pointing to
`git rev-list --objects --all`

see tree object
`git cat-file -p master`

see commit tree
`git log --oneline --decorate --all --graph`

merge disjointed branchs with commit, aka merge commit 
`git merge master -m 'b4'`
