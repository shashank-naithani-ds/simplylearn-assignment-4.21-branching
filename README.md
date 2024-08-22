 # 4.21 Assignment 1 Branching

<br>
<strong>Problem</strong><br>

Create a branch "featureONe" and view the commit history in this branch. Make a change to a file and merge it back into the master branch. THen , Make simultaneous changes to the same file to cause conflict and do the merge again.

<strong>Solution</strong> <br> <br>

- Create a repo and add some files
- now make a branch with $ git branch [branch name]  or git checkout -b [branch name]  <br>
- now edit the file and merge to main by going to main branch by $ git checkout main then $ git merge featureOne <br>
- Now edit same file in both branches and merge it with main. You will see conflict appeared. <br>
- Manually remove the conflits in the file and commit. <br>
