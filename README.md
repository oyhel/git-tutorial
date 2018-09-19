# A very gentle introduction to git and Github covering the very basics.

## Basics

- Create a local repository named after yourself separated by underscore, eg. *oyvind_helgeland*

- Create a file called README.md where you write a short text snippet about yourself. I want you to use markdown for this. It is a simple formatting language used by many tools, including Github and Rstudio (this text is written in markdown!). Use the two resources below to generate the text that you paste into the file (or just write it into the README.md directly):

  -  [Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
  -  [Online parser](https://dillinger.io/)

- Check the status (git status). What does git tell you about the current status of the file?

- Add the file (git add) README.md and check the status. What does git tell you about the file?

- Commit (git commit) the file README.md and check the status. What does git tell you?

- Check the log. What do you see?
  
- Add some more info to the README.md

- Check what's changed (git diff) 
 
- Add and commit README.md and check the log again. What do you see?

## Github

We now want to push our file/repo to Github.

- Log in to your Github account and create a new repository (make it public). Read the instructions carefully. We want to push an existing repository. Follow the instructions to add a remote and push.

- What happened when we added a remote origin? (hint look at .git/config)

- View your README.md in Github. Is the formatting as expected? Add some info to the README.md using the editing capabilities of Github.

- Pull down the changes you just added to the remote to your local repository (git pull).

## Branching

- List the current branches of your repo (git branch)

- Create a new branch (git branch \<new branch>)

- List branches again

- Switch to your newly created branch (git checkout \<new branch>)

- Check the status. Confirm you are on the right branch.

- Add a new file called _branchfile1.txt_ with som stuff in it.

- Add and commit the file

- Push the repo to Github

- Check in Github that you have two branches (master and \<new branch>) and inspect the contents.

- Switch back to the master branch

## Merge conflicts

- Pair up and select one of your repos for you both to work on.

- Both of you pull down the repo.

- Both of you add a file called conflict.txt with the content
  _my name is: \<your name>_

- Both push the file to the repo

- Fix the merge conflict
