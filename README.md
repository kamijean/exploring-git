# Exploring-Git

This exercise will give you a chance to explore basic use of Git and GitHub.
Note: The pull request you submit should not involve this repo (USUCS2610/exploring-git). Do not create a pull request to this repository, but to your own.

## Quick Lookup
Git command | Description
--- | ---
**git clone REPO** | Make a copy of a repository. A typical repository address is https://github.com/USUCS2610/exploring-git.
**git add FILE** | This can do one of two things. If FILE is not in the repository, it adds it to the repository. If FILE is already in the repository, it marks it as being part of the current set of files to be committed. (Often, you only want to commit only a subset of the files you've modified, so you use git add on each of those.)
**git status** | Get the status of your repository. What files have been modified? Which are staged for commit? Which are just new?
**git diff** | Shows how your files differ from the staging area
**git commit** | Commits all of the files you're added. Typically, pops up an editor. If vi pops up, use i to switch to insert mode, type the text for the commit, and then type the escape key to get out of insert mode. Then, type :wq to write the file and quit vi.
**git commit -m "MESSAGE"** | Commits the files you've added, using the given message. (A nice way to avoid the editor.)
**git merge BRANCHNAME** | To merge a different branch into your active branch. Join two or more development histories together
**git rebase** | Reapply commits on top of another base tip
**git log / less** | Shows a log of the changes that have been made. (less lets you page through those changes.)
**git push** | Send your commits to the primary repository.
**git pull** | Grab other people's commits from the primary repository.
**git stash** | Stashing takes the dirty state of your working directory — that is, your modified tracked files and staged changes — and saves it on a stack of unfinished changes that you can reapply at any time.
**git stash list** | List all the stashes on the stack
**git stash show** | Shows a specific stash or the last one
**git stash ( pop / apply )** | Pops off the last stash on the stack
**git reset** | Reset current HEAD to the specified state -- git reset —soft HEAD^ to remove uncommited changes
**git rm --cached FILE** | To stop tracking a file by removing it from the index of the git repo

### Preparation
If you have not already done so, set up a GitHub account

## Assignment
1) Fork this repo.

2) In your forked repo, go to Settings and click Collaborators & teams.

3) At the bottom, add kamijean as a collaborator.

4) Clone the forked repo locally.

5) Create a .gitignore file in the main section of the project

6) Ignore all the .txt files and .orig files (and if you have a mac ignore the DS_Store files)

7) Use git commit to commit your change. Use a meaningful message like "Added .gitignore file.”

8) Use git push to send your change to the primary repository.

9) Run “git rm --cached *.txt” to clear out already pushed up .txt file

10) Use git add to add the changes of the file to the repository

11) Verify the .txt file has been removed from the repository

12) Add some text to the mergeConflict p tags in the index.html file

13) Add and commit if there are any changes to the repo

14) Look online to see if your change has been pushed.

15) Checkout the merge_conflict branch and see the differences of the branches

16) Merge the merge_conflict branch into the master branch — because you forked you may need to use origin/merge_conflict

17) Fix the conflicts by keeping both texts

18) Add and commit if there are any changes to the repo

19) Add some text to the rebase p tags

20) Add and commit your changes to the repo

21) Checkout the rebase branch and see the differences of the branches

22) Rebase the rebase branch into master (make sure to view the changes made to the repo, it should have text added to it)

23) Fix the conflicts by only keeping the text you wrote, not the text from the branch (This text will disappear :()

24) Add and commit your changes to the repo

25) Put text into the stash p tags and then stash the changes

26) Merge the merge branch into the master branch (make sure to view the changes made to the repo, it should have text added to it)

27) Add and commit if there are any changes to the repo

28) Pop from the stash

29) Add and commit if there are any changes to the repo

30) Put text into the remove p tags

31) Reset the repository

32) Add and commit if there are any changes to the repo

### Extra Learning
Free Git Tutorials
https://try.github.io/levels/1/challenges/1
http://gitreal.codeschool.com/

Series of Git Training
https://www.youtube.com/watch?v=FyfwLX4HAxM&list=PLg7s6cbtAD15G8lNyoaYDuKZSKyJrgwB-

### References
List of some basic Git commands to get you going with Git
https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html

A collection of useful .gitignore templates
https://github.com/github/gitignore

The official and comprehensive man pages that are included in the Git package itself
https://git-scm.com/doc

### Submitting
Github has a timestamp and will show if the work has been done.

### Extra Learning
1) Learn something about git

2) Add a new file to the repository

3) Tell me about something useful you've learned
